📊 P2P Merchant Dashboard

A lightweight web app for managing crypto P2P trading inventory, pricing, and profit calculation.

Built with pure HTML, CSS, and JavaScript — no frameworks, no backend, no installation needed.

Open the file → start trading.

🚀 Why I built this

In P2P trading, speed and pricing matter more than prediction.

Spreadsheets were too slow.

So I built a small dashboard to:

track layered buys (inventory)

calculate average cost automatically

suggest profitable sell prices

manage spreads like a market maker

This app helps me think like a merchant, not a gambler.

✨ Features

✅ Add multiple buy layers (different prices)
✅ Automatic average cost calculation
✅ Suggested sell price based on target profit %
✅ Total inventory tracking
✅ Clean light theme UI
✅ Works offline
✅ Saves data automatically (localStorage)
✅ Mobile + desktop friendly
✅ No internet required

📂 Tech Stack

HTML

CSS

Vanilla JavaScript

Browser localStorage (for saving data)

No:

frameworks

databases

servers

dependencies

Super lightweight ⚡

🖥️ How to Use
1. Download

Clone or download this repo:

git clone https://github.com/yourusername/p2p-dashboard.git

2. Open

Simply open:

p2p-dashboard.html


in your browser.

That’s it. No setup needed.

📈 How it works
Add Buy Layers

When you buy USDT at different prices:

Example:

12.60 → 500 USDT

12.70 → 700 USDT

12.80 → 800 USDT

Add each as a layer.

The app calculates:

Total quantity

Total cost

Average price

Suggested sell price

Set Target Profit %

If you set:

0.5%


The app automatically shows:

Sell Price = Average Cost × 1.005


So you always sell with profit.

🧠 Strategy Behind This Tool

Designed for:

P2P merchants

high-volume traders

spread-based trading

market makers

Not for:

price speculation

leverage trading

futures

Goal:
Small profit × many trades = consistent income

📱 Tips
Install like an app (mobile)

On Chrome/Edge:

Menu → Add to Home Screen

Now it behaves like a real app.

Backup your data

Because it uses localStorage:

same browser keeps your data

clearing browser storage deletes it

Tip: export or copy data if needed.

🔮 Future Improvements (ideas)

Live market price input

Daily profit tracker

Trade history

Import/export data (CSV)

PWA install support

Dark/light toggle

Binance/OKX price API integration

📄 License

Free to use and modify.

Built for learning + personal trading tools.
