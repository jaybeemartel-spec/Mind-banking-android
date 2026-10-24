# Mind Banking Android Demo v0.3

This is an **Android Studio source project** that packages the Mind Banking mobile prototype in a simple Android app shell. It is not a compiled APK yet.

## What it does
- Opens the Mind Banking demo UI directly from local app assets.
- Includes the overview, accounts, simulated card requests, simulated transfers, transactions, savings, invitation, security, help, and demo-admin screens present in the prototype.
- Does not request internet access, contacts, SMS, location, or other sensitive Android permissions.
- Keeps the interface local; no server or financial-service API is connected.

## Open and run on Android
1. Install Android Studio on a computer and open this project folder (`MindBankingAndroid`).
2. Let Android Studio sync Gradle and install any prompted Android SDK components (compile SDK 35).
3. Connect an Android phone with USB debugging enabled, or create an emulator.
4. Press **Run** to install the demo on the selected device.
5. To create an APK in Android Studio, select **Build → Build Bundle(s) / APK(s) → Build APK(s)**. Android Studio will show the output path when finished.

## Demo safety limits
- All banking, cards, balances, transfers, and account actions are simulated.
- No real money moves, no account is opened, and no genuine Visa card is issued.
- Do not enter real banking details, card details, passwords, or identity documents.
- No backend, authentication service, or encrypted remote database is included.
- This project is a prototype, not a regulated banking service or a production-ready financial app.

## Project details
- App ID: `com.mindbanking.demo`
- Version: `0.3.0`
- Minimum Android version: Android 8.0 (API 26)
- Working project name only; trademark/name availability and IP registration have not been established.

Before real-world launch, the project needs professional security review, secure authentication and backend services, privacy/legal review, authorized financial partners, and compliance approval.
