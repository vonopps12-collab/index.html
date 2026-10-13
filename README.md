# 🦓 Zebra Tracker — Business Accounting & Multi-Task Hub

A full-stack, authentic business accounting application based on [Zebra Tracker](https://euphonious-gecko-973694.netlify.app/) seamlessly merged with **Flask Session Authentication**, **SQLite Database Storage**, and an integrated **Web Scraper (Quotes Sandbox)**.

---

## 🌟 Modules & Features

### 1. 📊 Executive Dashboard
* **Today's Summary:** Sales, Cost of Goods Sold, and Gross Profit.
* **This Month's Summary:** Total Sales, Gross Profit, Total Expenses, and Net Profit.
* **Month-End Forecast:** Live projections based on days elapsed.
* **Last 7 Days Visual Chart:** Interactive CSS bar chart tracking daily sales.
* **Top Products:** Best revenue drivers for the month.
* **Inventory Stock Alerts:** Instant warnings for low stock ($\le 5$) and out-of-stock items.

### 2. 💰 Sales Tracker
* Record sales with automatic inventory deduction.
* Product autocomplete linking to your product catalogue.
* Tracks customer name, customer phone, and payment methods (`Cash`, `M-Pesa / Lipanamba`, `Bank Transfer`, `Card`).
* Date navigation to view past sales.

### 3. 💸 Expenses Tracker
* Track operational costs by category (`Rent`, `Transport`, `Stock purchase`, `Staff wages`, `Utilities`, `General`, `Other`).
* Log vendor details and receipt reference numbers.
* Filter and search expenses in real-time.

### 4. 📦 Product & Inventory Catalogue
* Manage items with selling price, cost price, category, unit (`Piece`, `Kg`, `Litre`, `Pack`, `Box`), and stock level.
* Color-coded stock badges: **Good** (green), **Low Stock** (orange), and **Out of Stock** (red).

### 5. 📈 Reports & Tax Estimator
* **Daily & Monthly Breakdowns:** Revenue, cost of goods, gross profit, expenses, and net profit.
* **Tax Estimator:** Calculates estimated business tax reserves (18%) on net profit.
* **Export & Print:** One-click CSV export and printer-friendly reports (`@media print`).

### 6. 🦓 Zara — AI Business Accountant
* Connects directly to your live SQLite financial data.
* Quick questions: "How's business today?", "Best selling product?", "Any problems I should fix?", "How much tax should I save?", "Where is my money going?".
* Chat directly in English or Swahili (`Habari!`).

### 7. 🕷️ Integrated Quotes Scraper Hub
* Pulls live quotes from `quotes.toscrape.com` with deduplication.
* Store inspirational quotes in SQLite.
* Download `scraped_quotes.csv` straight to your browser.

### 8. 🌙 Dark Mode & Theme
* Built-in dark mode toggle (`🌙` / `☀️`) matching the original Netlify Zebra Tracker styling.

---

## 🚀 Running the App

The server is currently running at:
👉 **http://127.0.0.1:5000**
