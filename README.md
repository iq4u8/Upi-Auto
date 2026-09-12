# 💳 Paytm All-in-One QR Payment Gateway (Frontend)

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Semantic_UI-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-Responsive_Tokens-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+_Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JS" />
  <img src="https://img.shields.io/badge/Deploy-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Paytm-Business_Verified-00B9F1?style=for-the-badge&logo=paytm&logoColor=white" alt="Paytm" />
</p>

A modern, ultra-sleek, and responsive **Paytm Business UPI Payment Interface** built for **iq4u8** (`paytm.s3qmd4q@pty`). 

Engineered with authentic Paytm All-in-One QR standee branding, official vector SVGs, and automated connection to an AI OCR transaction verification backend.

---

## 🌟 Key Product Features

### 1. 🎨 Authentic Paytm Business Aesthetics
- **Official Paytm Branding**: Centered top merchant header with verified badge: `[Paytm] FOR BUSINESS | iq4u8 ✓`.
- **Vector Brand Assets**: Official vector SVGs for **Paytm**, **Google Pay**, **PhonePe**, and **BHIM UPI** (zero pixelated raster images).
- **Paytm Standee Ribbon**: Realistic gradient badge replicating official Paytm All-in-One merchant soundbox/standees.

### 2. 📱 100% Single-Screen Viewport Architecture
- Designed with compact, mathematical scaling so the complete payment flow (QR, UPI app buttons, Screenshot drop zone, UTR input, and Support button) fits on a **single screen without vertical scrolling**.

### 3. 🌓 Dynamic OS Theme Adaptation
- Automatically detects and matches the user's operating system **Light / Dark Mode** using `prefers-color-scheme`.
- Includes tailored slate/navy dark mode tokens with zero color flashing on first load.

### 4. ⚡ Instant Payment Workflows
- **Dynamic 165px QR Code**: High-contrast QR for lightning-fast scanning from any UPI banking app.
- **1-Click UPI Launchers**: Instant deep-links triggering Google Pay (`gpay://`), PhonePe (`phonepe://`), and Paytm.
- **Copy UPI Bar**: 1-click clipboard copy with visual feedback for `paytm.s3qmd4q@pty`.

### 5. 📷 Drag & Drop AI Screenshot Verification
- Users can drop or select their payment confirmation screenshot (`.jpg`, `.jpeg`, `.png`).
- Sends the image directly to the Railway OCR backend to extract the 12-digit UTR and amount automatically.

### 6. 🎧 Interactive Micro-Interactions & Direct Support
- **Web Audio API Chime**: Plays a crisp payment verification tone without external MP3 dependencies.
- **Physics Canvas Confetti**: Custom celebratory particle explosion on successful payment confirmation.
- **Smart Support Button**: Bottom footer includes a direct **`✉ Support`** button linking to `iq4u8@hotmail.com`:
  - **Mobile**: Launches the native Gmail / Mail app with pre-filled subject and payment details.
  - **Desktop**: Automatically opens Gmail Web Compose in a new tab.

---

## 🔗 Connecting to Railway Backend

In [`index.html`](file:///c:/Users/iq4u8/Desktop/payment/payment-frontend-vercel/index.html) around **Line 963**, simply set your Railway backend domain:

```javascript
// =========================================================================
// BACKEND API CONFIGURATION (For Vercel + Railway Deployment)
// =========================================================================
const RAILWAY_BACKEND_URL = "https://your-railway-app.up.railway.app";
```

*When running locally or on the same domain, leave it empty `""` and it will automatically default to `http://localhost:8000`.*

---

## 🚀 1-Click Deployment on Vercel

1. **Push this folder** to a new GitHub repository (e.g. `payment-frontend`).
2. Go to [Vercel](https://vercel.com/) and click **"Add New Project"**.
3. Import your GitHub repository.
4. Keep the default settings (Framework Preset: **Other** / **Static Site**).
5. Click **Deploy**!
6. Your payment frontend is live globally on Vercel edge CDN.

---

## 📁 Repository Structure

```
payment-frontend-vercel/
├── assets/
│   ├── gpay.svg        # Official Google Pay vector logo
│   ├── paytm.svg       # Official Paytm vector logo
│   ├── phonepe.svg     # Official PhonePe vector logo
│   └── upi.svg         # Official NPCI Unified Payments Interface logo
├── index.html          # Unified responsive single-screen frontend
├── vercel.json         # Clean URL and static routing configuration
├── .gitignore          # Git exclusion rules
└── README.md           # Documentation
```

---

## 💼 Resume / Portfolio Description (Copy & Paste)

> **Paytm All-in-One QR Payment Gateway UI (HTML5, Vanilla CSS, Modern JavaScript, Vercel)**
> - Developed a single-screen responsive payment frontend for Paytm Business with zero-scroll viewport geometry.
> - Integrated official SVG vectors, 1-click UPI app deep-linking intents, and dynamic QR generation.
> - Built client-side screenshot capture handling for AI OCR backend verification with interactive feedback modals.
> - Implemented Web Audio API synthesis for auditory payment confirmation, HTML5 canvas confetti physics, and dynamic OS color scheme detection.
> - Deployed as a high-availability decoupled static application on Vercel edge infrastructure.

---

## 📄 License
MIT License. Built for **iq4u8**.
