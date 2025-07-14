# BedsideOne

**A wearable-first platform for hands-free Epic access and bedside care delivery.**

---

## Overview

**BedsideOne** is an open-source project designed to unify clinical workflows into a single, secure, wearable interface — powered by AR devices like the ThirdEye X2. It enables clinicians to stay fully engaged at the bedside while accessing patient charts, vitals, secure messaging, and hospital systems via Citrix or Azure-hosted environments.

The system is modular, shift-oriented, and supports secure authentication (badge/NFC/biometric) along with lightweight peripherals like Bluetooth keyboards. Built with real-time care delivery in mind, it bridges fragmented clinical tools into one seamless experience — directly in the provider’s field of view.

---

## Key Goals

- Secure Epic access from wearable HUD (via Citrix/Azure)
- Hands-free workflows: charting, vitals, orders, messaging
- Real-time HUD alerts from Philips & Epic Haiku
- Shift-based authentication and session management
- Open-source, modular development model

---

## Repo Structure (Modules)

| Folder | Description |
|--------|-------------|
| `/launcher-module` | Custom Android launcher in kiosk mode |
| `/citrix-config` | Citrix Workspace configs and deployment policies |
| `/azure-vm` | Scripts for setting up Azure Virtual Desktops |
| `/nfc-login-module` | Badge or NFC-based login system |
| `/ai-assistant-module` | Voice-to-text dictation + NLP command layer |
| `/session-sync-module` | Session resume across devices (hot swap) |
| `/support-tools` | Battery, crash, network overlays |
| `/admin-dashboard` | Live monitoring for IT staff |
| `/deployment` | One-click setup scripts for devices |
| `/fhir-overlay` | Real-time vitals in HUD (via FHIR API) |
| `/bluetooth-mapper` | Epic-specific keyboard mapping |
| `/training-mode` | AR simulation mode for onboarding |
| `/philips-bridge` | Listener for fall/call alerts from Philips |
| `/epic-haiku-listener` | Listener for Epic Haiku mobile alerts |
| `/overlay-hud` | Core renderer for HUD notifications |
| `/biometrics-engine` | Seizure, fall detection, SpO2, heart rate |
| `/hardware-guides` | Specs and recommendations for wearables |
| `/docs` | Project summary, setup guides, timelines |

---

## Project Status

This repo currently contains the full architecture and documentation framework. Development is underway module-by-module, with hardware testing expected to begin shortly.

---

## Contributing

BedsideOne is an open-source project built to support clinical innovation. Contributions are welcome once core modules are published. Security, compliance, and patient privacy are foundational to the design.

---


