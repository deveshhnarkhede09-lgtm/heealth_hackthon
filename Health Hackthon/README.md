# BloodBridge 2.0 — Predictive, Stock-First Coordination & Smart Matching Network

**Event:** VITB – JHU Health Hack 2027  
**Track:** Healthcare Delivery & Emergency Coordination Systems  
**Live URL:** `http://localhost:3000` or open `index.html` directly in browser  
**Formal Project Report:** [PROJECT_REPORT.md](file:///c:/Users/deves/OneDrive/Desktop/Health%20Hackthon/PROJECT_REPORT.md)

---

## What’s New in BloodBridge 2.0

### 1. Moving from Reactive to Predictive
- **Seasonal Demand Forecaster:** Predicts blood component shortages 3–7 days ahead based on vector-borne outbreaks (Dengue platelet surge), monsoon trauma trends, and scheduled surgery calendars.
- **Proactive Donor Mobilization:** Nudges eligible voluntary donors before hospital reserves fall below critical thresholds.

### 2. Real-Time Blood Stock & Component Layer
- **Component Breakdown:** Granular tracking of Whole Blood, Packed Red Blood Cells (PRBC), Platelets (RDP/SDP), and Fresh Frozen Plasma (FFP).
- **Expiry Countdown:** Alerts for platelet batches (< 48 hrs) and routes near-expiry units to prevent wastage.
- **Inter-Hospital Surplus Transfers:** Hospital A out of stock checks Hospital B surplus and arranges transfer before disturbing donors.
- **New Pipeline:** `1. Check Local Stock ➔ 2. Inter-Hospital Transfer ➔ 3. Smart Donor Alert`.

### 3. Smarter Matching Engine
- **NBTC Eligibility Guard:** Enforces 90-day (males) and 120-day (females) minimum donation intervals. Ineligible donors are never spammed.
- **Traffic-Aware ETA:** Calculates actual road travel time across congested urban routes.
- **Donor Reliability Index:** Weights candidates by verified show-up history.
- **Rare Blood Group Protocol:** Cross-city registry mode for **Bombay Phenotype (hh)** and Rh-Null.

### 4. Standing Patient Module (Thalassemia & Oncology)
- Dedicated "Life Circles" pre-matching chronic transfusion patients with small, trusted donor rotations weeks in advance.

### 5. Visible Trust & Compliance
- **Tamper-Evident SHA-256 Hash Chain:** Cryptographic blocks linking clinical state changes and pathologist approvals.
- **Tokenized QR Code Check-In:** Ephemeral encrypted QR token scanned upon donor arrival to close the verification loop.
- **DPDP Act 2023 Portal:** Coarse geohash masking, consent managers, and one-click data erasure.
- **e-RaktKosh Sync:** Bidirectional alignment with India's national blood bank portal.

### 6. Universal Accessibility
- **WhatsApp Front Door Simulator:** AI triage bot converting unstructured WhatsApp pleas into structured hospital requests.
- **Two-Way SMS & IVR:** `Reply 1 to Accept, 2 to Decline` for non-smartphone users.

### 7. Hackathon Demo Story Mode
- Click **"⚡ 30s Hackathon Demo Story"** in the top navbar to showcase the step-by-step resolution of a critical trauma crisis!
