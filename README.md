# SecureID AI - Fake Identity & Document Screening System

**Smart India Hackathon 2026 (SIH26188)**  
Government-grade frontend portal for AI-powered document forgery detection, OCR extraction, circular risk scoring, and facial verification.

---

## 🏛️ Government Design System

- **Sidebar Background:** Slate-900 (`#0F172A`)
- **Main App Background:** Slate-50 (`#F8FAFC`)
- **Card Elements:** Pure White (`bg-white`) with Slate-200 borders (`border-slate-200`)
- **Risk Indicator System:**
  - 🟢 **LOW RISK (0–40):** `text-green-600` / `bg-green-50`
  - 🟡 **MEDIUM RISK (41–70):** `text-amber-500` / `bg-amber-50`
  - 🔴 **HIGH RISK (71–100):** `text-red-600` / `bg-red-50`

---

## 🚀 Quick Start Instructions

```bash
# 1. Navigate into the frontend project directory
cd frontend

# 2. Install dependencies
cmd /c npm install

# 3. Launch the development server
cmd /c npm run dev
```

Open your browser at `http://localhost:3000` (or the port indicated in terminal).

---

## 🔑 Phase 1 Operational Demo Features

- **Authentication Guard (`/login`):** Professional security login UI with mock officer credentials and validation.
- **Security Operations Dashboard (`/dashboard`):**
  - Stat cards for Scanned, Flagged, High Risk, & Processing speed.
  - Recharts Risk Distribution pie chart.
  - Live screening audit log table with direct report inspection trigger.
- **Axios & Mock Fallback Layer:** Pre-configured to communicate with `http://localhost:8000/api/v1`, falling back seamlessly to realistic mock data.
