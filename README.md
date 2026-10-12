# 🛡️ TraceX Frontend & Browser Interceptor

[![Next.js](https://img.shields.io/badge/Next.js-14.2-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18-blue?style=flat-square&logo=react)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

> **TraceX Frontend**: An edge-optimized, dark-mode cybersecurity analytics dashboard, real-time interactive sandboxing scanner, threat watchlist manager, and Manifest V3 browser extension for pre-socket lexical phishing defense.

---

## 🚀 Key Features

- **Lexical Sandbox Scanner:** Paste arbitrary URLs to execute instant lexical feature extraction & ONNX model inference without making external DNS queries.
- **Interactive Risk Gauge:** Visual real-time SVG threat severity score meter with latency metrics breakdown.
- **12-Vector Feature Matrix:** Detailed inspection of Shannon entropy, punycode/IDN homographs, suspicious token distributions, raw IP routing, and sub-domain structures.
- **Threat Watchlist & Rule Engine:** Full CRUD operations backed by Supabase with live search and threat classification filters.
- **Manifest V3 Browser Extension:** Pre-socket URL interceptor that blocks zero-day malicious lures before socket establishment.
- **Strict Architecture Constraint:** Built in **100% Pure JavaScript (`.js`, `.jsx`)** with strictly zero TypeScript.

---

## 🌐 Production Deployment (Vercel)

This frontend repository is optimized for **Zero-Configuration 1-Click Deployment on Vercel**:

1. Import this repository (`mukhesh88/TraceX-Frontend`) into Vercel.
2. The root contains `package.json` directly—**no root directory configuration needed**.
3. Framework Preset: Automatically detected as **Next.js**.
4. Configure Environment Variables (or use the pre-bundled `.env.production`):
   ```env
   NEXT_PUBLIC_API_URL=https://tracex-backend-s6kq.onrender.com
   NEXT_PUBLIC_SUPABASE_URL=https://dpuxpbiaxxkrjmwbewjp.supabase.co
   NEXT_PUBLIC_SUPABASE_ANON_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
   ```
5. Click **Deploy**.

---

## 💻 Local Development

```bash
# 1. Clone repository
git clone https://github.com/mukhesh88/TraceX-Frontend.git
cd TraceX-Frontend

# 2. Install dependencies
npm install

# 3. Start local development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🧩 Browser Extension Installation

1. From the live website, click **"ADD EXTENSION"** in the top navigation or hero banner to download `tracex-extension.zip`.
2. Extract the downloaded zip file.
3. Open `chrome://extensions` (or `edge://extensions`) in your browser.
4. Toggle **"Developer mode"** in the top-right corner.
5. Click **"Load unpacked"** and select the extracted folder.
6. TraceX is now active across all browser tabs!

---

## 🔗 Related Repositories

- **Backend Microservice:** [TraceX-Backend](https://github.com/mukhesh88/TraceX-Backend) (Java 17, Spring Boot 3, ONNX Runtime)
- **Live API Endpoint:** `https://tracex-backend-s6kq.onrender.com`
