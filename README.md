# 🧮 Math Calculator Hub

A fully client-side, zero-dependency math calculator hub built in a single HTML file. It covers **35+ calculators** across 7 categories — from basic arithmetic to statistics, geometry, finance, and fun tools.

---

## ✨ Features

- **35+ calculators** organized into categories with tab filtering
- **Live search** — find any calculator instantly by name or description
- **No dependencies** — pure HTML, CSS, and vanilla JavaScript
- **Single file** — everything lives in one `math.html` file
- **Responsive grid layout** — works on desktop and mobile
- **Glassmorphism UI** with smooth hover animations and focus states

---

## 📂 Calculator Categories

| Category | Calculators |
|---|---|
| **General** | Percentage, Percentage Change, Average, Weighted Average, Rounding, Ratio, Proportion, Fraction↔Decimal |
| **Number Theory** | Prime Check, Prime Factorization, LCM, GCD/HCF, Divisibility, Even/Odd, Perfect Number, Palindrome, Armstrong Number, Fibonacci Check |
| **Algebra** | Linear Equation, Quadratic Equation, Exponent, Logarithm |
| **Geometry** | Triangle Area (Heron's), Rectangle, Circle, Cylinder, Sphere, Pythagorean Theorem, 2D Distance |
| **Statistics** | Mean/Median/Mode, Standard Deviation, Probability, Combination nCr, Permutation nPr, Z-Score |
| **Everyday** | Tip Calculator, Discount, Profit/Loss, Markup, Bill Split, Simple Interest, Compound Growth |
| **Fun & Logic** | Base Converter (Bin/Oct/Dec/Hex), Random Number Generator, Dice Roller, Coin Flip, Numerology |

---

## 🚀 Getting Started

No installation needed. Just open the file in any browser.

```bash
# Clone the repository
git clone https://github.com/ihtouhid/mathCalculator-hub.git

# Open in browser
open math.html
```

Or simply download `math.html` and double-click it.

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3** — CSS variables, glassmorphism, grid layout, smooth transitions
- **Vanilla JavaScript** — no frameworks, no libraries

---

## 📸 UI Highlights

- Fixed **Home** button for navigation within a larger site
- **Search bar** with live filtering across all calculators
- **Category tabs** to browse by topic
- **Card grid** with hover lift effect
- **Slide-in panel** with inputs and a styled result box per calculator

---

## 🤝 Contributing

Pull requests are welcome. To add a new calculator:

1. Add an entry to the `CALCS` array with `id`, `title`, `cat`, `icon`, and `desc`.
2. Add the HTML UI string for that `id` inside `buildUI()`.
3. Write a corresponding `calc<Name>()` function that calls `showResult()`.

---

## 📄 License

MIT — free to use, modify, and distribute.
