# Harsh Bansal — Portfolio & Panda Apps Hub

Static, zero-build web hub hosted on GitHub Pages for **Harsh Bansal** (Hardware, Embedded Systems & Operations Engineer) and **Panda Apps** Google Play closed beta testing.

## Repository Structure

| File | Purpose |
|------|---------|
| `index.html` | Engineering portfolio, hardware lab matrix, contact console, and Panda Apps privacy policy modal |
| `testing.html` | Mobile-first Google Play Closed Testing onboarding hub for Panda Apps |

## Key Features & Routes

### 1. Engineering Portfolio (`index.html`)
- **Live Telemetry Hero:** Displays target stack (`ESP32-S3 / C++ / BLE / Linux / Homelab`), location, availability, and live session uptime.
- **Active Deployments:** Expandable architecture notes for ESP32-S3/SK6812 WLED controllers, Qualcomm CSR8670 BLE reverse-engineering, self-hosted TrueNAS/Proxmox clusters, and system automation.
- **Hardware Lab & Systems Matrix:** Workbench tooling and infrastructure stack overview.
- **Transmission Console:** One-click clipboard copy for email (`harshbansal8520@proton.me`), GitHub (`github.com/Harshmf`), and PGP key.
- **Privacy Policy Deep Link:** Opening `/#privacy` automatically launches the Panda Apps Privacy Policy modal.

### 2. Closed Beta Testing Hub (`testing.html`)
A sequential 3-step onboarding flow designed to prevent the Play Store *"App not available"* error by guiding testers through joining the Google Group first.

- **Google Group:** [`https://groups.google.com/g/synth-app`](https://groups.google.com/g/synth-app)
- **URL Parameter Routing:** Link directly to a specific app from inside production apps using `?app=<slug>`:

| App | Slug | Package ID | Direct URL |
|-----|------|------------|------------|
| SH-101 | `sh101` | `com.panda.sh101` | `testing.html?app=sh101` |
| Juno-106 | `juno106` | `com.panda.juno106` | `testing.html?app=juno106` |
| TB-303 | `tb303` | `com.panda.tb303` | `testing.html?app=tb303` |
| TR-606 | `tr606` | `com.panda.tr606` | `testing.html?app=tr606` |
| TR-808 | `tr808` | `com.panda.tr808` | `testing.html?app=tr808` |
| TR-909 | `tr909` | `com.panda.tr909` | `testing.html?app=tr909` |
