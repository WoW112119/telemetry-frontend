# 🖥️ Microfleet Telemetry Dashboard

## 🚀 Project Overview
This is the official frontend for the Microfleet ecosystem. It is a real-time, high-performance dashboard built with **Angular 19** to visualize lift truck telemetry data. The dashboard provides fleet managers with instant visibility into vehicle health, speed violations, and battery status.

## 🎯 Product Vision
To provide a reactive, zoneless user interface that transforms raw backend telemetry into actionable safety alerts through intuitive color-coded status indicators.

## 🛠️ Global Tech Stack
* **Framework**: Angular 19 (Standalone Components)
* **State Management**: Angular Signals (Zoneless Change Detection)
* **Styling**: Modern CSS3 with dynamic status mapping
* **Environment**: Node.js & npm

## 🗺️ Project Roadmap (Frontend)
* **✅ Sprint 4: Live Data Visualization** (Completed!)
    * Built reactive table with Signal-based data fetching.
    * Implemented dynamic "Violation" vs "Normal" color logic.
* **⏳ Sprint 5: Security & OAuth2 Integration** (Planned)

## 📂 Project Ecosystem
This frontend works in tandem with the backend services:
* ⚙️ **Backend**: [Telemetry Service](https://github.com/WoW112119/telemetry-service)
* 🗄️ **Database**: PostgreSQL (Dockerized)