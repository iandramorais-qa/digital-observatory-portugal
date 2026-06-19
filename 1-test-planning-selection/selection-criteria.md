# 📋 Test Planning & Lead Selection Criteria (Sampling Strategy)

## 1. Objective & Business Vision
This document outlines the requirements and logic used to define the testing scope and select the target businesses (leads) for the Digital Observatory framework. 

**Vision & Scalability:** While this pilot batch focuses on a localized sample, the infrastructure is engineered for horizontal scalability. The long-term product roadmap involves expanding this framework to multiple municipalities and national-level data collection, building an interactive maturity map to be commercialized as an auditing service for Municipal Chambers (Câmaras Municipais) and public tourism/trade entities.

## 2. Target Scope & Location
*   **Industry Sector:** Hospitality / Food & Beverage (Restaurants, Cafés, and Local Gastronomy).
*   **Geographic Focus:** Alcobaça, Leiria District, Portugal (Pilot Batch).
*   **Sample Size:** `n = 25` verified active business establishments.

## 3. Selection Methodology (The Star-Rating Benchmark)
Rather than picking businesses at random, the selection process followed a strict reverse-engineering logic based on public validation data:
1.  **Search Query Initialization:** Initial lead discovery was conducted using localized keywords (e.g., "Restaurante Alcobaça") via Google Maps and Google Business Profile indexing.
2.  **Reputation Filtering (The Control Variable):** Only businesses with a **public rating equal to or higher than 4.0 stars (out of 5.0)** and a minimum of 50 organic user reviews were shortlisted. 
3.  **The Hypothesis:** Companies with high public ratings possess excellent physical/on-site service quality. Therefore, their primary digital conversion channels should theoretically match this standard of excellence.

## 4. Multi-Channel Discovery & WhatsApp Execution Matrix
For each selected business, a multi-channel matrix was mapped to verify the existence of digital touchpoints, followed by an active black-box communication test focused exclusively on their primary conversion endpoint:

*   **Discovery Mapping (Passive Verification):** 
    *   **Google Business Profile:** Verified vs. Unverified profiles, correctness of active business hours, and active contact links.
    *   **Web & Social Presence:** Existence of an institutional website, domain security compliance (HTTPS), and active links to Facebook/Instagram profiles.
*   **Active Communication Testing (Functional Execution):**
    *   **WhatsApp Business Lifecycle:** Active communication was simulated strictly via WhatsApp. Tests evaluated the existence of a business account, availability of instant catalogs, presence of native auto-responders, and exact message delivery logs (response time). *Note: Active messaging via social media inboxes or landline voice calls was excluded from this pilot scope.*

## 5. Output for Next Stages
The final output of this selection phase was a structured list of 25 unique leads, each assigned a specialized Tracking ID (e.g., `ALC-RES-001` to `ALC-RES-025`), ensuring total traceability for the execution phase (`2-test-execution-evidence`).

