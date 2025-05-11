# Stress Manager

A browser-based stress tracking app that visualizes HRV-derived stress levels, integrates with Bluetooth HRV monitors, and helps users understand and manage their stress over time.


## 🚀 Features

- 📊 **Chart.js Integration** — Visualize daily stress trends over time.
- 💙 **Bluetooth HRV Monitor Sync** — Connects via the Web Bluetooth API to devices like Garmin HRM.
- 🧠 **HRV Parsing & Scoring** — Uses RMSSD-based calculations to derive stress levels from RR intervals.
- 🧠 **Educational Content** — Expandable/collapsible tabs provide insights into stress, HRV, and wellness.
- 🗂️ **Local History Storage** — Saves historical data using `localStorage` for persistence across sessions.

---

## 📦 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Charts**: [Chart.js](https://www.chartjs.org/)
- **Bluetooth**: [Web Bluetooth API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Bluetooth_API)
- **Storage**: `localStorage` for offline persistence

---

## 🔧 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/stress-tracker.git
cd stress-tracker
