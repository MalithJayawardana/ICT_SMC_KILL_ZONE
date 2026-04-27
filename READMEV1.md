# 📊 SessionBoxes MT5 Indicator

**SessionBoxes** is a professional MetaTrader 5 (MT5) indicator designed to visually frame major trading sessions (Asian, London, New York, and Overlap). It automatically identifies the High and Low of each session and draws clean, transparent boxes to help traders identify liquidity zones and session ranges.

---

## ✨ Features
* **4 Customizable Zones:** Pre-configured for Asian, London, New York, and the Lon/NY Overlap.
* **High/Low Accuracy:** Dynamically calculates the highest high and lowest low within the specific time window.
* **Strategy Tester Fix:** Optimized to work perfectly during backtesting (Visual Mode).
* **Non-Intrusive Design:** Transparent boxes (border-only) ensure your candles and price action remain clearly visible.
* **Auto-Cleanup:** Automatically removes all drawings when the indicator is removed from the chart.

---

## 🛠 Installation
1.  **Download** the `SessionBoxes.mq5` file.
2.  Open your MT5, go to **File > Open Data Folder**.
3.  Navigate to `MQL5 > Indicators`.
4.  **Paste** the file into the Indicators folder.
5.  **Restart** MT5 or **Refresh** the Indicators list in the Navigator.
6.  Drag the indicator onto your chart and allow **DLL imports** if prompted.

---

## ⚙️ Default Settings
| Session | Start Time | End Time | Default Color |
| :--- | :--- | :--- | :--- |
| **Asian Range** | 00:00 | 08:00 | Lavender |
| **London Session** | 08:00 | 16:00 | Cornflower Blue |
| **NY Session** | 13:00 | 21:00 | Salmon |
| **Overlap** | 13:00 | 16:00 | Medium Sea Green |

---

## 🚀 How to Use
This indicator is perfect for traders using:
* **ICT / SMC Concepts:** To identify Asian Range liquidity or Killzones.
* **Breakout Strategies:** To trade London or NY open breakouts.
* **Volatility Analysis:** To see how price reacts during session overlaps.

---

## 📝 License
This project is open-source. Feel free to modify the code and adapt it to your own trading style.

---
*Developed for MetaTrader 5*
