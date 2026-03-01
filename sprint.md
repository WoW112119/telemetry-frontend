# Sprint 4 Technical Archive: Data Visualization

## 🎯 Revised Sprint Goal
The original goal was pivoted to focus on **Real-Time Data Visualization**. This sprint successfully established the bridge between the PostgreSQL data engine and a modern Angular user interface.

## 🛠️ Technical Implementation
* **Framework**: Angular 19 (Standalone & Zoneless).
* **Reactivity**: Leveraged **Angular Signals** (`signal<any[]>()`) to bypass traditional Zone.js change detection, ensuring the UI remains performant on low-memory hardware.
* **Logic Mapping**: Implemented a dynamic CSS class binder that reads the `highSpeedViolation` boolean from the Java backend and applies `status-violation` or `status-normal` styling.

## 🚧 Challenges & Solutions
* **Data Desync**: Fixed a "blank table" bug by correctly mapping the PostgreSQL snake_case (`high_speed_violation`) to the Java camelCase (`highSpeedViolation`).
* **Zoneless Async**: Solved a UI rendering lag by utilizing `.set()` within the service subscription to force a signal update.

## ✅ Definition of Done
* [x] Established end-to-end connectivity (DB -> API -> UI).
* [x] Rendered live truck status with color-coded alerts.
* [x] Cleanly separated frontend and backend repositories.