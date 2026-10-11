# 🎨 BroTech Painting Quote Calculator

A lightweight, offline-friendly painting service estimator built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies — just open and use.

![BroTech Quote](https://img.shields.io/badge/status-live-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## 🌐 Live Demo

👉 **[Try it here](https://yourusername.github.io/brotech-quote/)**

Replace `yourusername` with your GitHub username.

---

## ✨ Features

- **Interior & Exterior painting** quotes
- **Live calculation** — labour, travel, and paint costs
- **Custom paint cost** input (since paint prices vary by supplier)
- **Room & area-based pricing** with surcharges
- **Print-friendly** quotation layout
- **Fully offline** — works without internet after loading
- **Mobile responsive** — works on phones, tablets, and desktops

---

## 🧮 How the Quote is Calculated

| Component | Formula |
|---|---|
| **Base Labour** | R600 (interior) / R750 (exterior) |
| **Area Surcharge** | R6–R7 per m² above 30 m² |
| **Room Surcharge** | R250 per room beyond 2 rooms |
| **Travel** | R10 per km |
| **Paint** | User-entered amount |

---

## 🚀 How to Use

1. Open the [live link](https://yourusername.github.io/brotech-quote/)
2. Enter customer name and job details
3. Adjust paint cost to match your supplier's price
4. Click **Calculate Quote**
5. Click **Print Quote** to save as PDF or print

---

## 🛠️ Run Locally

Since this is a single-file app, just:

```bash
git clone https://github.com/yourusername/brotech-quote.git
cd brotech-quote
# Open index.html in any browser
