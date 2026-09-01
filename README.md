# LottoMac releases

Public download host for the LottoMac GT90EZ wrapper app.

This repository exists only so agent devices can install the app without a
Google sign-in. Firebase App Distribution requires one, Firebase Storage is
unavailable on this project, and Firebase Hosting refuses `.apk` files on the
Spark plan. A file in a public repo is served by `raw.githubusercontent.com`
to anyone, with no account.

The app is a WebView wrapper around https://tecla-international.web.app — it
holds no credentials. Agent logins and Firestore rules guard all real data.

Source lives in the private `tecla_international` repository.

| Build | File |
|---|---|
| 1.0.14 (`20260901-printer-localhost`) | `lottomac-1.0.14.apk` |
| 1.0.13 (`20260901-printer-text-frames`) | `lottomac-1.0.13.apk` |
