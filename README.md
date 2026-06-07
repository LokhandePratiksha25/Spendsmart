
# 💰 SpendSmart — Personal Expense Tracker

> A free, private, and fully-featured personal finance web app built with HTML, CSS & JavaScript.  
> **No server. No subscription. No data sharing. Just you and your money.**

🌐 **Live Website:** [lokhandepratiksha25.github.io/Spendsmart](https://lokhandepratiksha25.github.io/Spendsmart/)

---

## 📸 Preview

| Dashboard | Charts | Budget Alerts |
|---|---|---|
| Dark mode dashboard with summary cards | Live monthly trend charts | Budget progress with alerts |

> *Try the live site to see it in action!*

---

## ✨ Features

### 💳 Transaction Management
- Add **income & expense** transactions manually
- Separate categories for Income and Expense
- Edit or delete any transaction anytime
- Mark transactions as **🔁 Recurring** — re-add monthly in one click

### 📊 Live Charts & Analysis
- **Monthly Trends** — Line chart of income vs expenses over time
- **Category Split** — Donut chart showing spending distribution
- **Top Spends** — Ranked table of highest expense categories
- All charts **update instantly** as you add transactions

### 💡 Auto-Generated Insights
- Spending trend vs last month (up/down %)
- Top spending category this month
- Daily average spend + projected monthly total
- Savings rate — are you hitting the 20% goal?
- Biggest single transaction
- Most frequent spending category
- Budget health summary

### 🔔 Smart Budget Alerts
- Set monthly budget limits per category
- **Yellow warning** at 80% of budget
- **Red alert** at 100% (over budget)
- Visual progress bars for every category

### 🔍 Search & Filter
- Search transactions by description
- Filter by category, type (income/expense)
- Results update instantly — no page reload

### 🌙 Dark / Light Mode
- Beautiful dark theme (default)
- Clean light theme
- Preference saved per user account

### 💱 Multi-Currency Support
- 9 currencies: ₹ INR, $ USD, € EUR, £ GBP, ¥ JPY, ₩ KRW, ₽ RUB, AED, C$ CAD
- Switch anytime — all amounts update instantly
- Saved per user account

### 📂 CSV Import & Export
- Import bank transactions from any CSV file
- Export all your data as CSV anytime
- Compatible with most bank statement formats

### 📱 Progressive Web App (PWA)
- Install on Android or iPhone — no Play Store needed
- Works **fully offline** after first visit
- Looks and feels like a native mobile app

### 🔐 User Accounts
- Signup & Login system
- Each user's data is completely private and separate
- Data saved securely in browser localStorage
- Demo account available to try without signing up

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript (ES6+) |
| **Charts** | Chart.js v4.4.1 |
| **CSV Parsing** | PapaParse v5.4.1 |
| **Storage** | Browser localStorage API |
| **Offline** | Service Worker + Web App Manifest |
| **Hosting** | GitHub Pages |
| **Design** | Custom CSS with CSS Variables (dark/light themes) |

---

## 📁 Project Structure

```
📁 SpendSmart/
├── index.html        → Entire app — HTML + CSS + JavaScript
├── manifest.json     → PWA configuration (name, icons, theme)
├── sw.js             → Service Worker for offline support
├── icon-192.png      → App icon (192×192)
├── icon-512.png      → App icon (512×512)
├── _redirects        → Netlify routing config
└── README.md         → You are here!
```

---

## 🚀 How to Run Locally

No installation needed!

```bash
# Step 1: Clone the repository
git clone https://github.com/LokhandePratiksha25/Spendsmart.git

# Step 2: Open the folder
cd Spendsmart

# Step 3: Open index.html in your browser
# Just double-click index.html OR drag it into Chrome/Edge
```

That's it — the app runs completely in your browser. No npm, no server, no setup.

---

## 📖 How to Use

**1. Sign Up**
- Click *Get Started* on the landing page
- Enter your name, email, and password
- You're in!

**2. Add Transactions**
- Click *Add Transaction* on the dashboard
- Select Income or Expense
- Fill in date, description, amount, account, category
- Click *Add Transaction* — charts update instantly!

**3. Set Budgets**
- Scroll to *Budget Management*
- Add a monthly limit for any category (e.g. Food ₹5000)
- Watch the progress bar fill as you spend

**4. View Insights**
- Check the *💡 Spending Insights* section
- See auto-generated observations about your spending habits

**5. Install as App (optional)**
- Android: Chrome shows an *Install* banner — tap it!
- iPhone: Safari → Share → Add to Home Screen

---

## 🎯 Modules Overview

| Module | Description |
|---|---|
| Authentication | Login, Signup, Demo login, per-user data isolation |
| Dashboard | Summary cards — Total Income, Expenses, Net Savings, Rate |
| Add Transaction | Manual entry with income/expense categories |
| Charts | Monthly trends, category donut, bar chart, top spends |
| Budget Management | Set limits, track progress, get alerts |
| Spending Insights | 8 auto-generated financial observations |
| Search & Filter | Real-time search and category/type filtering |
| Recurring | Mark & re-add monthly recurring expenses |
| CSV Import/Export | Upload bank CSV, download your data |
| Dark/Light Mode | Theme toggle saved per user |
| Multi-Currency | 9 currency options saved per user |
| PWA | Offline support, installable as mobile app |

---

## 👩‍💻 Developer

> 💪 *This project was ideated, designed, developed, and deployed entirely by **Pratiksha Lokhande** — from scratch, independently.*

---

## ⚠️ Known Limitations

| Limitation | Details |
|---|---|
| **localStorage Security** | Passwords and user data are stored in browser localStorage which is accessible via browser dev tools — not recommended for production use |
| **No cross-device sync** | Data is saved only in the browser you use — switching devices or browsers shows empty data |
| **Data loss risk** | Clearing browser cache or storage deletes all saved transactions and budgets permanently |
| **No email verification** | Users can sign up with any email — no verification is done |
| **No forgot password** | Password reset via email is not available in this version |
| **Single browser only** | App works only in the browser it was first used — no cloud backup |

> 🔧 **All of these limitations will be fixed in the next version** by integrating **Firebase Authentication** for secure login and **Firestore** as a real cloud database.

---

## 🔮 Future Plans

- [ ] Firebase integration — real cloud database + secure auth
- [ ] Data sync across multiple devices
- [ ] Forgot password / email verification
- [ ] Savings Goals tracker
- [ ] EMI / Loan calculator
- [ ] PDF report export
- [ ] Calendar heatmap view
- [ ] Year in Review summary

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🌟 Show Some Love

If you found this project helpful or impressive, please consider:
- ⭐ **Starring** this repository
- 🍴 **Forking** it to build your own version
- 📢 **Sharing** it with friends who need an expense tracker

---

<div align="center">

**Built with ❤️ solely by Pratiksha Lokhande**

🌐 [Live Demo](https://lokhandepratiksha25.github.io/Spendsmart/) • 💻 [GitHub Repo](https://github.com/LokhandePratiksha25/Spendsmart)

</div>
