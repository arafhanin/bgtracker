# SpendWise — Daily Expense Tracker

SpendWise is a responsive, feature-rich, client-side daily expense tracker built as a zero-dependency single-file web application. It features real-time financial analytics, budget tracking, multi-currency support, custom period filtering, and an interactive spend simulator.

---

##  Features

###  Dashboard & Financial Intelligence
* **KPI Metrics:** Monitor period totals, active daily spend averages, remaining budget targets, and top spending categories at a glance.
* **Visual Analytics:** Interactive Chart.js bar graphs for spending trends and doughnut charts for category breakdowns.
* **Timeframe Spend & Run-Rate Converter:** Switch between actual totals and projected 7-day, 30-day, and 365-day run-rates.
* **What-If Spend Simulator:** Drag the interactive slider to simulate daily spending choices and project long-term impact.

###  Quick Logging & Recurring Bills
* **Inline Quick-Add:** Record daily transactions in seconds directly from the main view.
* **1-Tap Templates:** Save frequent bills (e.g., commute, coffee, subscriptions) and log them with one click.
* **Categorization:** Categorize by Food & Dining, Groceries, Transport, Bills & Utilities, Shopping, Health, Entertainment, Education, and Other.
* **Payment Methods:** Track payments via Cash, Mobile Wallet (bKash/Nagad), Debit Card, Credit Card, or Bank Transfer.

###  Budgets & Category Limits
* **Target Caps:** Set custom daily and monthly budget ceilings with auto-scaling targets.
* **Category Monthly Caps:** Assign individual spending caps per category with visual progress indicators.

###  Search, Filter & Export
* **Flexible Date Filters:** View history by Daily, Weekly, Monthly, Yearly, Custom Date Ranges, or All Time.
* **Advanced Filters:** Real-time keyword search, category filtering, payment method filtering, and multi-criteria sorting.
* **Data Export:** Download filtered or full transaction logs as standard CSV files for Excel/Spreadsheets.

###  Privacy, Storage & Customization
* **100% Client-Side:** All data remains strictly in your browser's `localStorage` — no backend server required.
* **JSON Backup & Restore:** Export complete state backups as `.json` files or import existing data.
* **Multi-Currency Support:** Seamlessly switch between `BDT (৳)`, `USD ($)`, `EUR (€)`, `GBP (£)`, `INR (₹)`, and `JPY (¥)`.
* **Dark / Light Theme:** Toggle between light and dark modes with a single click.
* **Mobile-Optimized:** Fully responsive UI with a dedicated bottom navigation bar on mobile devices.

---

## 🛠️ Built With

* **HTML5 / ES6 JavaScript** (Vanilla JS)
* **[Tailwind CSS v3.4](https://tailwindcss.com/)** (Styling via CDN)
* **[Chart.js v4.4](https://www.chartjs.org/)** (Data Visualization)
* **[Lucide Icons](https://lucide.dev/)** (UI Iconography)
* **[Google Fonts (Inter)](https://fonts.google.com/specimen/Inter)** (Typography)
---

##  Quick Start

Because SpendWise is built into a single self-contained `index.html` file, no build tools, terminal commands, or `node_modules` installations are required.
