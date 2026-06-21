# 💱 Currency Converter

A simple, clean and responsive Currency Converter web app built with pure HTML, CSS and Vanilla JavaScript. No frameworks, no backend, no API key required.

---

## 📸 Screenshot

> _Add your screenshot here after running the project_

![Currency Converter Screenshot](screenshot.png)

---

## ✨ Features

- 🔄 Real-time exchange rates via Frankfurter API
- 🌍 15+ world currencies with flag emojis
- 📈 30-day historical rate chart (Chart.js)
- ⭐ Save favourite currency pairs
- 🕐 Recent conversion history
- 🔁 Swap From/To currencies instantly
- 🌙 Dark / Light mode toggle
- 📱 Fully responsive — works on mobile and desktop
- 💾 History and favourites saved in browser (localStorage)

---

## 🚀 How to run

No installation needed!

1. Download or clone this repository
2. Open `index.html` in any browser
3. That's it — no server, no setup required

```bash
git clone https://github.com/YOUR_USERNAME/CurrencyConverter.git
cd CurrencyConverter
# Just open index.html in your browser
```

---

## 🛠️ Technologies used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling and responsive layout |
| Vanilla JavaScript | Logic, API calls, localStorage |
| Chart.js | 30-day historical rate chart |
| Frankfurter API | Free exchange rate data |

---

## 🌐 API

This project uses [Frankfurter](https://www.frankfurter.app/) — a free, open-source exchange rate API. No API key required.

| Endpoint | Usage |
|---|---|
| `/latest?from=USD&to=EUR` | Live exchange rate |
| `/2024-01-01..2024-01-30?from=USD&to=EUR` | Historical rates range |
| `/currencies` | List of all supported currencies |

---

## 📁 Project structure

```
CurrencyConverter/
└── index.html      # Everything in one file — HTML, CSS, and JavaScript
```

---

## 📄 License

MIT — free to use, modify, and distribute.
