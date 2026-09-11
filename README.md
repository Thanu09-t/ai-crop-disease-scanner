<div align="center">

# 🌿 AgriScan Pro
### AI-Powered Crop Disease Detection & Precision Agriculture Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Status](https://img.shields.io/badge/Status-Active%20%26%20Ready-brightgreen.svg)]()

*Empowering farmers, agronomists, and agricultural specialists with instant AI-driven crop diagnostics, actionable treatment recommendations, and comprehensive field health tracking.*

[Features](#-key-features) • [Application Flow](#-application-modules--screens) • [Quick Start](#-quick-start) • [Project Structure](#-project-structure) • [Contributing](#-contributing) • [License](#-license)

---

</div>

## 📖 Overview

**AgriScan Pro** is a modern, responsive web application engineered to diagnose crop health issues directly from leaf and plant imagery. By combining high-speed visual scanning with agronomical decision engines, the platform identifies pathogens, blight, and nutrient deficiencies while providing tailored treatment pathways and long-term field management tracking.

---

## ✨ Key Features

- **🔍 Smart Scan Portal**: Instant camera capture or high-resolution image upload for real-time plant pathology analysis.
- **🔬 Precision AI Diagnostics**: Detailed disease identification complete with confidence ratings, severity metrics, and infected area mapping.
- **💊 Multi-Tiered Treatment Guides**: Actionable remediation protocols covering:
  - **Biological Controls**: Eco-friendly biopesticides and organic solutions.
  - **Chemical Interventions**: Precise active ingredient dosages and application schedules.
  - **Cultural & Preventative Practices**: Soil adjustments, irrigation schedules, and crop rotation tactics.
- **📊 Comprehensive Farm Dashboard**: Centralized view of overall crop health index, active field warnings, recent activity feeds, and environmental metrics.
- **📜 Historical Diagnostic Archive**: Longitudinal scan records with date filtering, severity tags, and recurrence tracking.
- **🔐 Secure Farm Profile & Onboarding**: Multi-step farmer onboarding including account verification, GPS-aware field profiling, and personalized crop selection.

---

## 📱 Application Modules & Screens

The application includes an end-to-end user journey across dedicated modules:

| Step | Module | Description | Entry File |
| :---: | :--- | :--- | :--- |
| **0** | **Interactive Hub** | Master launchpad and screen switcher | [`stitch_ai_crop_disease_scanner/index.html`](stitch_ai_crop_disease_scanner/index.html) |
| **1** | **User Login** | Secure credentials portal with remember-me & recovery | [`stitch_ai_crop_disease_scanner/login/code.html`](stitch_ai_crop_disease_scanner/login/code.html) |
| **2** | **Account Verification** | Security code verification step | [`stitch_ai_crop_disease_scanner/create_account_verification/code.html`](stitch_ai_crop_disease_scanner/create_account_verification/code.html) |
| **3** | **Farm Profile Setup** | Farm acreage, soil type, and primary crop configuration | [`stitch_ai_crop_disease_scanner/create_account_farm_profile/code.html`](stitch_ai_crop_disease_scanner/create_account_farm_profile/code.html) |
| **4** | **Farm Dashboard** | Health metrics, field alert center, quick action triggers | [`stitch_ai_crop_disease_scanner/agriscan_dashboard/code.html`](stitch_ai_crop_disease_scanner/agriscan_dashboard/code.html) |
| **5** | **Scan Portal** | Interactive image uploader & camera capture interface | [`stitch_ai_crop_disease_scanner/scan_portal/code.html`](stitch_ai_crop_disease_scanner/scan_portal/code.html) |
| **6** | **Analysis & Diagnosis** | AI pathogen breakdown, severity meter, and visual inspection | [`stitch_ai_crop_disease_scanner/analysis_diagnosis/code.html`](stitch_ai_crop_disease_scanner/analysis_diagnosis/code.html) |
| **7** | **Treatment Guides** | Organic and chemical application recipes & best practices | [`stitch_ai_crop_disease_scanner/treatment_guides/code.html`](stitch_ai_crop_disease_scanner/treatment_guides/code.html) |
| **8** | **History Log** | Searchable audit trail of previous diagnoses and resolution states | [`stitch_ai_crop_disease_scanner/history_log/code.html`](stitch_ai_crop_disease_scanner/history_log/code.html) |

---

## 🚀 Quick Start

### Prerequisites
No complex toolchains or heavy dependencies are required. Any modern web browser or lightweight HTTP server is sufficient.

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/stitch_ai_crop_disease_scanner.git
cd stitch_ai_crop_disease_scanner
```

### 2. Run Locally

#### Option A: Python Built-in Server (Recommended)
```bash
# Python 3
python -m http.server 8000
```
Open **[http://localhost:8000](http://localhost:8000)** in your browser.

#### Option B: Node.js `npx serve`
```bash
npx serve . -p 8000
```
Open **[http://localhost:8000](http://localhost:8000)** in your browser.

#### Option C: VS Code Live Server
1. Open the folder in VS Code.
2. Right-click on `index.html`.
3. Select **"Open with Live Server"**.

---

## 📁 Project Structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   ├── feature_request.md
│   │   └── config.yml
│   ├── workflows/
│   │   ├── ci.yml
│   │   └── deploy.yml
│   └── PULL_REQUEST_TEMPLATE.md
├── stitch_ai_crop_disease_scanner/
│   ├── account_created_success/
│   │   └── code.html
│   ├── agriscan_dashboard/
│   │   └── code.html
│   ├── analysis_diagnosis/
│   │   └── code.html
│   ├── create_account_farm_profile/
│   │   └── code.html
│   ├── create_account_verification/
│   │   └── code.html
│   ├── earthy_modern/
│   ├── history_log/
│   │   └── code.html
│   ├── login/
│   │   └── code.html
│   ├── scan_portal/
│   │   └── code.html
│   ├── treatment_guides/
│   │   └── code.html
│   └── index.html                # Master Hub / Launchpad
├── index.html                    # Root entry point with redirect
├── .gitignore                    # Git exclusions
├── CONTRIBUTING.md               # Guidelines for contributors
├── CODE_OF_CONDUCT.md            # Community code of conduct
├── LICENSE                       # MIT License
├── README.md                     # Documentation
└── SECURITY.md                   # Security vulnerability policy
```

---

## 🛠️ Technology Stack

- **Markup & Layout**: Semantic HTML5 with accessible ARIA landmarks.
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) via official CDN with custom brand color palettes (`#012d1d`, `#116c4a`, `#a1f4c8`).
- **Typography**: [Google Fonts (Inter)](https://fonts.google.com/specimen/Inter).
- **Iconography**: [Google Material Symbols Outlined](https://fonts.google.com/icons).
- **Architecture**: Zero-build static web application, fully hostable on GitHub Pages, Netlify, Vercel, or AWS S3.

---

## 🌐 Deploy to GitHub Pages

This project is pre-configured with a GitHub Actions workflow in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

To publish your own live deployment:
1. Push this repository to GitHub.
2. In your repository settings, navigate to **Settings** > **Pages**.
3. Under **Build and deployment** > **Source**, choose **GitHub Actions**.
4. Any push to `main` will automatically build and publish your site at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

---

## 🤝 Contributing

Contributions are welcome! Please review our [Contributing Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) before submitting pull requests.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.
