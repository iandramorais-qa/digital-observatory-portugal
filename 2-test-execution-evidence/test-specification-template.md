# 🧪 Test Execution Framework & Field Audit Specification

## 1. Internal Audit Regulations & Guidelines
To guarantee compliance and eliminate evaluation bias during the manual black-box testing phase, every cartographer must adhere to the following strict operational rules:
*   **Time-Stamp Logging:** The exact system time when the initial WhatsApp user message is triggered must be recorded down to the minute.
*   **Response Window (SLA):** Any response received past 24 hours (or a complete failure to deliver) is instantly classified as a **Critical Defect / System Silence**.
*   **Cross-Channel Validation:** Information found on the Google Business Profile acts as the 'Single Source of Truth' (SSOT) to be benchmarked against active websites and social media channels.

---

## 📋 Standard Test Case Template (Field Sheet Model)
*Based on Internal Field Sheet: Observatório Digital BIGWave*

### 🔍 TEST IDENTIFIER: [e.g., ALC-RES-001]
*   **Business Name:** [e.g., António Pedro Padeiro - Since 1983]
*   **Location/City:** Alcobaça, Portugal
*   **Audit Execution Date:** [e.g., 14/05/2026]

---

### 🛠️ LAYER 1: STRUCTURAL MATURITY (Passive Asset Verification)

| Test Step / Verification Point | Expected Result | Actual Result (Pass/Fail) | Notes / Observations |
| :--- | :--- | :--- | :--- |
| **1.1 Google Business Profile (GBP)** | Profile exists and is active. | [ ] Pass  [ ] Fail | e.g., Ratings: 4.7 (3,586 reviews). |
| **1.2 Verification Badge** | Blue verification badge present. | [ ] Pass  [ ] Fail | e.g., Profile is Unverified. |
| **1.3 Proprietary Website** | Active domain and fully functional. | [ ] Pass  [ ] Fail | e.g., Custom domain functional. |
| **1.4 Online Menu Accessibility** | Menu/Catalog easily accessible. | [ ] Pass  [ ] Fail | e.g., Outdated Facebook menu link (2023). |
| **1.5 Media Optimization** | Updated high-quality photos (<6 months).| [ ] Pass  [ ] Fail | e.g., Only user-submitted photos active. |

---

### 💬 LAYER 2: DIGITAL HOSPITALITY (Active Mystery Shopping Log)
*   **Target Endpoint:** Primary WhatsApp Conversion Channel.
*   **Message Timestamp Sent (Log In):** [e.g., 10:04 AM]
*   **Message Timestamp Received (Log Out):** [e.g., 10:21 AM]

**⏱️ Latency Calculation Matrix:**
*   [ ] **Low Latency:** < 30 minutes
*   [ ] **Medium Latency:** 30 - 60 minutes
*   [ ] **High Latency:** > 1 hour
*   [ ] **Critical Timeout / Defect:** No Response / Unavailable [e.g., WhatsApp Status: Unavailable]

*   **Public Interaction Quality:** Does the business actively reply to Google/Social reviews? 
    `[ ] High  [ ] Medium  [ ] Low`

---

### 🔄 LAYER 3: SYNCHRONICITY & DIGITAL BLIND SPOTS (Data Consistency)

| Verification Check | Expected Result | Match? (Y/N) |
| :--- | :--- | :--- |
| **3.1 Contact Information** | Phone numbers match perfectly across GBP, Website, and Instagram. | [ ] Yes  [ ] No |
| **3.2 Operational Hours** | Closing/Opening hours are identical on all online platforms. | [ ] Yes  [ ] No |
| **3.3 Bio Redirection Link** | The WhatsApp bio link on Instagram works and redirects properly. | [ ] Yes  [ ] No |
| **3.4 Brand Identity** | Name and logo branding are consistent everywhere. | [ ] Yes  [ ] No |
| **3.5 Menu Synchronicity** | The Google Business menu matches the Website/In-store catalog. | [ ] Yes  [ ] No |

---

### 🗂️ LAYER 4: ARCHIVING CHECKLIST (Evidence Folder Requirements)
To log a test case as officially completed, the execution folder must contain:
1. `Screenshot_01_GBP`: Main view with hours and verification status.
2. `Screenshot_02_Social`: Instagram/Facebook bio with the contact link visible.
3. `Screenshot_03_Website`: Mobile homepage showing direct CTA/contact buttons.
4. `Screenshot_04_Error_Proof`: Captured bugs (e.g., broken links, empty menus).
5. `Chat_Log_Receipt`: Screenshot of the conversation timestamp showing latency.

