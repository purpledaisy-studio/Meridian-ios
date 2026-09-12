# Meridian: Private, Offline-First Medical Records for iOS

by [PurpleDaisy](https://bypurpledaisy.com/) | A privacy-first iOS software engineering studio

Welcome to the public hub and issue tracker for **Meridian**: an independent, 100% offline iOS medical records and lab-tracking application.

We got tired of clunky web-based patient portals, proprietary testing subscriptions, and constant medical data breaches. We engineered Meridian to transform scattered paper lab reports and PDFs into clean, interactive health dashboards entirely on your iPhone.

---

### Official Resources & Documentation

* 🌐 **Official Website:** [bypurpledaisy.com](https://bypurpledaisy.com/)
* 📱 **App Store:** [Download Meridian on iOS](https://bypurpledaisy.com/meridian)
* 🔬 **Biomarker Database:** [500 Clinical Biomarker Encyclopedia](https://bypurpledaisy.com/biomarkers)
* 🧮 **Clinical Tools:** [Biological Age & Health Calculators](https://bypurpledaisy.com/calculators)
* 📖 **Research Journal:** [Preventive Medicine & Engineering Blog](https://bypurpledaisy.com/blog)
* 𝕏 **Twitter / X:** [@bypurpledaisy](https://x.com/bypurpledaisy)

---

### The Zero-Cloud Architecture

Your health data is your most sensitive personal information. Meridian is architected without cloud compromises:

| Principle | How Meridian Operates |
| :--- | :--- |
| **Zero Cloud Servers** | Your medical records never leave your iPhone. No remote databases, no tracking pixels. |
| **On-Device VisionKit OCR** | Apple VisionKit reads and extracts lab results locally without sending document scans to third parties. |
| **AES-256 Hardware Encryption** | Lab files are encrypted on-device with keys anchored in the Apple Secure Enclave. |
| **Total Patient Ownership** | Export, delete, or back up your data locally. Zero vendor lock-in. |

---

### Core Capabilities

* **On-Device Lab Scanning:** Point your camera at any paper lab report or import a Quest/Labcorp PDF. Meridian extracts biomarker values, units, and reference ranges in under one second.
* **Longitudinal Trends:** Plot multi-year trajectory charts for glucose, lipidology, inflammation, and metabolic markers. Compare results directly against our [500 Biomarker Reference Matrix](https://bypurpledaisy.com/biomarkers/reference).
* **Biological Age Telemetry:** Built-in clinical models (including Yale PhenoAge) evaluate healthspan trajectories locally. Test your metrics with our [Free Clinical Calculators](https://bypurpledaisy.com/calculators).
* **Side-by-Side Comparison:** Compare multiple historical lab panels side-by-side to review changes over time.
* **Physician Requisitions:** Review routine testing requirements with curated [Doctor Lab Panel Checklists](https://bypurpledaisy.com/panels).

---

### Architectural Comparison

| Feature | Meridian (PurpleDaisy) | Apple Health | Epic MyChart |
| :--- | :--- | :--- | :--- |
| **Data Storage** | 100% On-Device | iCloud Synced (Default) | Hospital Cloud |
| **Paper Lab OCR** | Apple VisionKit (Local) | Not Available | Not Available |
| **Data Ownership** | Patient-Controlled | Device Ecosystem | Hospital Network |
| **Processing** | On-Device Neural Engine | Apple Cloud Servers | Epic Systems Servers |
| **Offline Support**| Full Offline Access | Partial | Requires Internet |
| **Revenue Model** | Transparent Subscription | Ecosystem Lock-in | Enterprise Health License |

---

### Technology Stack

* **Platform:** iOS exclusive (Native SwiftUI)
* **Computer Vision:** Apple VisionKit & Core ML on Neural Engine
* **Cryptography:** AES-256-GCM backed by Apple Secure Enclave
* **Architecture:** Local-first, zero-knowledge
* **Standards:** Designed to exceed HIPAA and GDPR consumer health privacy standards

---

### Community & Feedback

Found a bug or have a feature request? Please feel free to open an [Issue](https://github.com/purpledaisy-studio/Meridian-ios/issues) in this repository.
