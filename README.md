# ZeroSignal Rescue AI Framework

# 🚨 ZeroSignal Rescue AI

An offline-first, brand-agnostic Progressive Web App (PWA) engineered to turn any smartphone into a life-saving disaster management tool when cellular networks, Wi-Fi, and power grids fail completely.

Live Demo Link: [👉 INSERT YOUR LIVE VERCEL/NETLIFY URL HERE]

---

## ⚡ Core Features

*   **🩹 PocketDoc (Offline AI Triage):** A fast, embedded string-matching and intent classification engine that delivers immediate first-aid medical protocols for life-threatening injuries without hitting an external server.
*   **📡 LocalBeacon (P2P Bluetooth Mesh):** Leverages the native Web Bluetooth API to broadcast encrypted telemetry signals and last-known GPS coordinates over BLE, allowing rescue teams to map survivors even in Airplane Mode.
*   **🩺 VitalScan (On-Device PPG Engine):** Uses the smartphone's camera lens and flashlight to calculate a patient's real-time heart rate (BPM) entirely on the client-side using red-channel pixel density analysis.

---

## ⚙️ Tech Stack & Hardware Integration

*   **Frontend:** Pure HTML5, Vanilla JavaScript (ES6+), Advanced CSS Grid/Flexbox variables.
*   **Offline Resilience:** Service Worker API caching lifecycle architecture.
*   **Hardware APIs:** Web MediaDevices API (Camera access), Web Bluetooth API (BLE mesh networking), Geolocation API.
*   **PWA Framework:** Web App Manifest standard compliance for native mobile installation.

---

## 🛠️ Quick Start & Installation

To run this project locally or test it on your device:

1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Serve the directory using an HTTPS connection (required for camera and Bluetooth sensor permissions):
   ```bash
   npx serve -s .
   ```
3. Open the link on your mobile phone, select **"Add to Home Screen"**, turn on **Airplane Mode**, and test the capabilities completely offline.

This package bundles everything required to assemble a fully operational offline, zero-signal emergency triage Progressive Web App (PWA).

## Files Included
1. `index.html` - Complete web client interface containing embedded custom high-contrast dark UI styling rules, local diagnostic engines, browser BLE telemetry broadcasting handlers, and on-device hardware optical pulse processing pipelines.
2. `manifest.json` - Device shell config layout determining deployment configurations, launch parameters, color modes, and branding endpoints to enable complete app dashboard installs.

## Development Deployment Instructions
1. Save `index.html` and `manifest.json` into the exact same folder context on your environment workspace.
2. Deploy the local directory onto secure cloud server structures utilizing easy web deployment vectors such as Vercel, Netlify, or Surge.sh to establish an HTTPS environment.
3. Access the deployed web engine with an iPhone or Android phone browser client, add the framework address to your mobile dashboard, toggle **Airplane Mode**, and test the end-to-end processing loops under 100% offline network configurations.
