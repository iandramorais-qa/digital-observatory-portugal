# 📊 Test Analysis Metrics & Data-Driven Scoring Algorithm

## 1. Objective & Operational Integrity
This document outlines the strict mathematical modeling, binary parameters, and business logic used to compute the digital health indices across the sample ecosystem ($N=25$). 

To comply with data privacy standards and enterprise-grade testing protocols, all input calculations rely strictly on anonymized, tracking variables linked to a unique Tracking ID (e.g., `ALC-RES-001` to `ALC-RES-025`), ensuring zero exposure of sensitive corporate metadata.

---

## 📈 2. The Global Digital Maturity Index (GDM / IMD) Framework
The global architectural score is a composite index built on three independent pillars, each evaluated on a strict **0 to 10 points scale**. The Global Index is derived using the arithmetic mean of the three pillars:

$$\text{Global GDM Index} = \frac{\text{Visibility Score} + \text{Digital Autonomy Score} + \text{Digital Hospitality Score}}{3}$$

### 🛑 Pillar 1: Visibility & Attraction Score (Max 10 Points)
Measures the brand's verified real estate and public interaction footprint across third-party indexers:
*   **Google Business Profile (GBP) Verification (Weight: 40%):** Claimed/Verified Profile = `4.0 pts` | Unverified = `0.0 pts`.
*   **Content Freshness & Posting Regularity (Weight: 30%):** Active updates on GBP/Instagram = `3.0 pts` | Inactive = `0.0 pts`.
*   **Public Interaction Quality (Weight: 30%):** Reviews response rate. High/Active = `3.0 pts` | Medium = `1.5 pts` | Low/No Reply = `0.0 pts`.

### 🌐 Pillar 2: Digital Autonomy Score (Max 10 Points)
Measures the business's independence from aggregator platforms and ownership of their digital funnel:
*   **Proprietary Website Infrastructure (Weight: 50%):** Active standalone domain = `5.0 pts` | Missing/Redirected = `0.0 pts`.
*   **Digital Menu Usability & Accessibility (Weight: 30%):** Active menu functional in <2 clicks = `3.0 pts` | Outdated/Broken = `0.0 pts`.
*   **Conversion Redirection Link (Weight: 20%):** Operational, unbroken WhatsApp link on Instagram Bio = `2.0 pts` | Broken/Missing = `0.0 pts`.

### 💬 Pillar 3: Digital Hospitality & Conversational Score (Max 10 Points)
Measures the end-to-end user experience, communication infrastructure readiness, and response precision:
*   **Direct Chat Availability (Weight: 40%):** WhatsApp channel active for customer contact = `4.0 pts` | Landline phone only = `0.0 pts`.
*   **SLA Response Time / Latency Log (Weight: 60%):** Real-time conversational delay logging:
    *   `< 15 minutes` $\rightarrow$ `6.0 points`
    *   `15 to 60 minutes` $\rightarrow$ `4.0 points`
    *   `> 60 minutes / High Latency` $\rightarrow$ `2.0 points`
    *   `Critical SLA Timeout / No Response` $\rightarrow$ `0.0 points`

---

## ⚠️ 3. Strategic Vulnerability & Operational Risk Index (0% to 100%)
To optimize B2B lead triage and target high-friction candidates for automated solutions, a separate **Strategic Vulnerability Index** is calculated by assessing security and structural operational risks:

*   **Platform Dependency (Weight: 50%):** Absence of a proprietary website (forcing total dependency on third-party aggregators or social nets) = `50% Risk` | Active website = `0% Risk`.
*   **Brand Exposure & Hijack Vulnerability (Weight: 50%):** Unverified Google Business Profile (exposing the brand to data hijacking or community edit vulnerabilities) = `50% Risk` | Officially Verified = `0% Risk`.

$$\text{Strategic Vulnerability} = \text{Platform Dependency} + \text{Brand Exposure}$$

*   **Triage Matrix:** Leads tracking an overall score of `High Risk (Vulnerability > 75%)` are instantly prioritized as hot targets for automated AI conversational onboarding (BIGWave SDR pipeline), whereas high-scoring leads (`Low Risk`) are benchmarked as optimized environments ready for advanced multi-agent deployment.
