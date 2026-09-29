# ☕ Coffee Sales Analysis using Google Sheets

Analysis of real world coffee shop sales analysis in **Google Sheets**  using formulas, pivot tables and charts to find top products, peak time slots, payment trends and weekday vs weekend sales..

**Prepared by:** Kashish Tripathi

## 📖 Overview

The raw dataset (Date, Date & Time, Payment Method, Money, Coffee Name, card IDs anonymized) was enriched with new columns and then analyzed to answer business questions on products, timing, payments and weekday vs. weekend sales.

**Total revenue:** ₹115,432 | **Average order value:** ₹32 | **Period:** 12 months (March – February)

## 🛠️ Data Enhancement

| Column | Functions Used |
|---|---|
| Day, Month | `TEXT()` |
| Weekday / Weekend | `WEEKDAY()` + `IF()` |
| Time Slot (Morning / Afternoon / Evening / Night) | `HOUR()` + nested `IF()` |
| Order Value Category (Low / Medium / High) | `IFS()` |

## 📊 Key Findings

| Question | Answer |
|---|---|
| Top revenue product | **Latte** – ₹27,866 |
| Best time slot | **Afternoon** – ₹39,018 |
| Preferred payment method | **Card** – 97.2% of revenue |
| Weekday vs. weekend | **Weekdays** – ₹82,114 vs ₹33,317 |
| Sold > 35 units on weekends | Latte (188), Cappuccino (110), Hot Chocolate (79), Cocoa (63) |

## 📈 Charts

Column (revenue by product) • Line (monthly trend) • Pie (payment method) • Bar (time slot) • Stacked column (daily revenue by time slot)

## 🧰 Tools

Google Sheets • `SUM` `AVERAGE` `SUMIF` `IF` `IFS` `INDEX` `MATCH` `TEXT` `HOUR` `WEEKDAY` • Pivot Tables • Charts

## 🎓 Learnings

- Breaking down timestamps reveals peak sales periods and weekday/weekend behavior.
- Built in Sheets functions are powerful enough for real world EDA.
- Clean, well labelled data is the first step to any meaning insight.

## 🔗 Links

- Google Sheet: https://docs.google.com/spreadsheets/d/1HXJIeO-ejWNahLodHfLABxHIdrvkdKeTghzm6ZKfQes/edit?usp=sharing
- Contact: www.linkedin.com/in/kashish-tripathi-1a604525b / kashishtripathi1635@gmail.com
