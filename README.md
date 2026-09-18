# Privacy Policy for AURA – The Sovereign Registry

**Effective Date:** September 18, 2026  
**Last Updated:** September 18, 2026  
**Developer:** Junaid Akmal  
**Application:** AURA – The Sovereign Registry (iOS)

---

## 1. Introduction
Welcome to **AURA – The Sovereign Registry** ("AURA", "we", "our", or "us"). We are committed to protecting your privacy and ensuring the confidentiality of your personal information. This Privacy Policy explains how information is collected, used, disclosed, and safeguarded when you use our mobile application on iOS.

By downloading, accessing, or using AURA, you agree to the collection and use of information in accordance with this policy.

---

## 2. Information We Collect

We only collect information necessary to provide the core services of AURA—namely, verifying lifetime Sovereign status and displaying member records in the Global High-Society Registry.

### A. Information You Provide Voluntarily
When you claim membership and set up your Sovereign profile, you may provide:
* **Display Name / Moniker:** The name you choose to represent your entry on the registry.
* **Nation / Country of Registry:** Your selected country or jurisdiction of affiliation.
* **Sovereign Statement / Motto:** An optional personal motto or philosophy displayed on your 3D digital pass.
* **Avatar Style:** Your selected crest or insignia.

### B. In-App Purchase & Transaction Information
* All financial transactions and payments are handled directly by **Apple StoreKit 2**.
* **We never receive, access, or store your credit card, bank account, or payment credentials.**
* We receive an anonymized, cryptographically signed JSON Web Signature (JWS) transaction token from Apple confirming that the one-time $999.99 StoreKit tier was completed. This token is used solely to verify your sequence number (e.g., `#001`, `#015`) and mint your lifetime registry record.

### C. Push Notification Device Tokens
* If you opt in to receive push alerts, our app registers an anonymous device token via **Apple Push Notification service (APNs)** and **Firebase Cloud Messaging (FCM)**.
* This token is used solely to deliver real-time notifications (such as alerts when a new Sovereign member joins the global registry). You can disable notifications at any time in your iOS Settings.

### D. Automatically Collected Diagnostic Data
* Anonymous crash diagnostics and basic performance telemetry provided by Apple and Firebase to help us maintain system reliability, uptime, and fix bugs.

---

## 3. How We Use Your Information

We use the collected information strictly for the following purposes:
1. **Registry Placement:** To display your rank, country crest, and sequence badge on the permanent Global Sovereign Registry.
2. **Membership Authentication:** To verify your cryptographic transaction token and maintain your access to the 3D Black Diamond Sovereign Pass.
3. **Registry Alerts:** To transmit push notifications when new members claim seats in the registry (if enabled).
4. **Service Reliability:** To diagnose crashes and optimize application performance.

**We do NOT:**
* Sell, rent, lease, or monetize your personal data.
* Share your data with data brokers or advertising networks.
* Use third-party ad tracking or cross-app tracking frameworks (IDFA is not tracked).

---

## 4. Third-Party Service Providers

To operate the application securely, we rely on trusted industry-standard infrastructure providers:

* **Apple Inc. (StoreKit 2 & APNs):** Handles payment processing, transaction verification, and push notification delivery. Subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).
* **Google Firebase (Firestore & Cloud Messaging):** Provides secure, encrypted cloud database hosting for registry records and notification routing. Subject to the [Google Privacy Policy](https://policies.google.com/privacy).

All third-party services process data strictly as service providers in compliance with applicable data protection regulations.

---

## 5. Data Storage and Security

* **Encryption in Transit:** All communications between the AURA app and our backend services use Transport Layer Security (TLS 1.3 / HTTPS).
* **Encryption at Rest:** Registry records stored in Firebase Firestore are encrypted using enterprise-grade 256-bit AES encryption.
* **Access Controls:** Database security rules enforce strict read/write authorization, preventing unauthorized alteration of registry records.

---

## 6. Data Retention and Deletion

* Your Sovereign profile remains active in the registry as long as your membership is in effect.
* **Account / Data Deletion Rights:** You have the right to request deletion of your name, motto, and registry record at any time. To request deletion of your data, please email **support@aura-registry.com** or open an issue on our GitHub repository at [https://github.com/JUNAIDAKMAL/Aura-Privacy-Policy](https://github.com/JUNAIDAKMAL/Aura-Privacy-Policy). Upon receiving your verified request, your personal information will be permanently removed from our active database within 30 days.

---

## 8. Changes to this Privacy Policy

We may update our Privacy Policy from time to time to reflect improvements or regulatory changes. Any modifications will be posted to this page with an updated "Last Updated" date. Continued use of AURA after updates constitutes acceptance of the revised terms.

---

## 9. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact:

* **Developer:** Junaid Akmal
* **Email:** support@aura-registry.com / junaidakmal@gmail.com
* **Privacy Policy Repository:** [https://github.com/JUNAIDAKMAL/Aura-Privacy-Policy](https://github.com/JUNAIDAKMAL/Aura-Privacy-Policy)
