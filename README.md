# 🕓 HTF Candles – Higher Timeframe Visualization

The **HTF Candles** indicator is a custom Pine Script® v6 tool for **TradingView** that visualizes **Higher Timeframe (HTF)** candles next to your current chart.

Instead of overlaying them on price bars, it displays each HTF candle **side-by-side** — offering a clean and structured multi-timeframe view.

---

## ✨ Features

- 📊 Display up to **10 higher-timeframe candles** beside the current chart  
- ⏱️ Built-in **countdown timer** for the active HTF candle  
- 🏷️ Optional **HTF label** (e.g., 1H, 4H, 1D)  
- 🟩 Fully customizable **colors**, **spacing**, and **width**  
- ⚙️ Works with all major timeframes (5m → 1M)

---

## 📸 Preview

![HTF Candles Preview](https://i.imgur.com/UM1q33V.png)

> Example: XAU/USD on 1-minute chart with 1H candles displayed beside the price action

---

## ⚡ Quick Start

1. Open **TradingView → Pine Editor**
2. Copy the code from [`HTF_Candles.pine`](./HTF-Candles.pine)
3. Paste and click **Add to chart**
4. Adjust appearance and timeframe in the indicator settings

---

## 🧩 Technical Notes

- Written in **Pine Script® v6**  
- `overlay = true` (for positioning flexibility)  
- Draws candles using `box` and `line` objects  
- Designed for high visibility without overlapping price bars

---

## 🪪 License

This project is licensed under the **Mozilla Public License 2.0**.  
See the [LICENSE](./LICENSE) file for details.

---

### 👨‍💻 Author

Created by me
If you find this script useful, consider ⭐ starring the repository!
