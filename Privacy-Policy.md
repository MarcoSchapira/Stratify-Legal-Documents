# Privacy Policy

**Effective Date:** December 29, 2025

---

## 1. Introduction

Thank you for using our app (Stratify), a stock market paper trading simulator and backtesting tool.  
We are committed to protecting your privacy and handling your information responsibly.  
By using the App, you agree to the terms described in this Privacy Policy.

---

## 2. Information We Collect

### A. Personal Information (Required for Account Creation)
We collect the following information when you create an account:
- Name
- Email Address
- Password (encrypted via Firebase Authentication)
- A device notification token if notifications are enabled

We do **not** collect sensitive financial details such as bank accounts or payment card information.

### B. Usage Information
We collect analytics data on how you interact with the App, including:
- Which features are used most
- Session length and general interaction patterns
- Basic performance data for error reporting

These analytics are collected using Firebase Analytics.

### C. Trading and Strategy Data
By default, the App does not collect or upload the following data:
- Paper trading transactions and portfolio values
- Backtesting strategies and related simulation results

This information is stored locally on your device using SQLite and is not sent to our servers unless you choose to enable notifications.

If you enable notifications for a strategy, the following limited data will be stored securely in Firebase Firestore:
- The strategy you chose to monitor
- The selected stock symbol
- Required technical indicator values used to evaluate the strategy
- A device notification token (so alerts can be delivered to your device)

This cloud storage is required for a strategy to be checked in the cloud and for notifications to be sent.

---

## 3. How We Use Your Information
We use the information we collect for the following purposes:
- To create and manage your user account
- To provide secure login and authentication services
- To improve App functionality and user experience through feature usage analytics
- To troubleshoot technical issues and maintain security
- To send custom notifications on your strategy status
- When you enable strategy notifications, we use your strategy data and device notification token to deliver notifications based on changes in strategy status

We do **not** sell, rent, or trade your personal information.

---

## 4. Data Storage and Security
- Account data (name, email, encrypted password) is stored securely using Firebase Authentication.  
- Feature analytics data is collected by Firebase Analytics in an aggregated, anonymous form.  
- Portfolio and trading data are stored locally on your device and never uploaded to external servers.
- Strategy data for which notifications are enabled is securely stored in Firebase Firestore.

We use industry-standard security practices to help protect your data, but no method of transmission or storage is 100% secure.

---

## 5. Third-Party Services
We use third-party services to provide some functionality:
- **Firebase Authentication & Analytics** – for secure login and feature usage tracking.
- **Stock market data** is obtained from third-party providers and used for simulation purposes only.
- **Firebase Cloud Messaging** — to send push notifications for strategy status updates.

These providers may collect certain technical data (such as IP address and device information) as part of their normal operation.  
For more information about Firebase, see [Google Firebase Privacy Policy](https://firebase.google.com/support/privacy).

---

## 6. Data Retention and Deletion
- Your personal account information (name, email, password) is retained until you delete your account.  
- You may delete your account at any time within the App or by contacting us.  
- Deleting your account will remove your personal information from Firebase Authentication.  
- Any data stored locally on your device (e.g., paper trades, backtesting strategies) can be deleted by uninstalling the App.
- When you delete your account, any cloud-stored strategy notification data associated with your account will also be deleted from Firebase Firestore.

---

## 7. Children's Privacy
This App is intended for users **13 years of age or older**.  
We do not knowingly collect personal information from children under 13.  
If we learn we have inadvertently collected information from a child, we will delete it promptly.

---

## 8. No Financial Advice
The App is for **educational and simulation purposes only**.  
It does not provide financial, investment, or trading advice.  
Simulation and backtesting results do not guarantee future outcomes.

---

## 9. No Liability for Code Errors
While we strive to ensure that the App functions as intended, we cannot guarantee that all backend code and calculations are free from errors or bugs.  
You acknowledge and agree that we are not liable for any incorrect or unexpected results, performance issues, or data inaccuracies arising from backend code errors or other technical faults.
Notifications may be delayed or fail to send due to connectivity, device settings, or third-party service performance.

---

## 10. Your Rights
Depending on your location, you may have rights under applicable privacy laws, including:
- Requesting access to your data
- Requesting deletion of your data
- Requesting correction of inaccurate data

For any privacy-related requests, please contact us at:  
**Email:** stratify.help@gmail.com

---

## 11. Changes to This Privacy Policy
We may update this Privacy Policy periodically to reflect changes in our practices.  
The updated policy will be posted within the App and on our website, and the “Effective Date” will be updated accordingly.

---

## 12. Contact Us
For questions about this Privacy Policy, contact us at:  
**Email:** stratify.help@gmail.com

---
