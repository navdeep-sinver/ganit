<p align="center">
  <img src="docs/images/icon.png" width="128" height="128" alt="Ganit app icon">
</p>

<h1 align="center">Ganit: the notepad calculator for Mac</h1>

<p align="center">
  <b>Calculate the way you talk.</b><br>
  Type math in plain English and see the answer on the same line as you type.<br>
  It understands Indian money (lakh, crore, GST, EMI, LPA) and works anywhere in the world: currencies, units and time zones.
</p>

<p align="center">
  <a href="https://github.com/navdeep-sinver/ganit/releases/latest/download/Ganit.dmg"><b>⬇️ Download Ganit for Mac</b></a>
  &nbsp;·&nbsp; Free &nbsp;·&nbsp; macOS 14 or newer &nbsp;·&nbsp; Apple silicon and Intel
</p>

<p align="center">
  <a href="https://github.com/navdeep-sinver/ganit/releases/latest"><img alt="Latest version" src="https://img.shields.io/github/v/release/navdeep-sinver/ganit?label=version&color=c8552b"></a>
  <img alt="macOS 14+" src="https://img.shields.io/badge/macOS-14%2B-111111?logo=apple">
  <img alt="Universal: Apple silicon and Intel" src="https://img.shields.io/badge/Apple%20silicon%20%2B%20Intel-universal-111111">
  <a href="https://github.com/navdeep-sinver/ganit/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/navdeep-sinver/ganit/total?color=2f7d4f"></a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/images/hero-dark.png">
    <img src="docs/images/hero-light.png" width="860" alt="Ganit notepad calculator on a Mac. A November budget adds up rent, SIP and groceries in rupees. Below it, Ganit answers ₹2,499 + 18% GST, 20 LPA monthly, $35 billion in INR, a home loan EMI, 6pm in San Francisco in India time, 180 cm in feet and inches, and days until new year.">
  </picture>
</p>

## What is Ganit?

**Ganit** (गणित, Hindi for "maths") is a **notepad calculator for macOS**. It's part notes app, part calculator.

You type a line the way you'd say it out loud:

- `20 LPA monthly`
- `6pm in San Francisco is what time in India`
- `$35 billion in INR`

The answer shows up on the right as you type. There are no formulas to learn, no spreadsheet cells and no buttons to press. Click any answer to copy it.

If you've used **Soulver** or **Numi**, Ganit works the same way. The difference is that it also understands how India talks about money, like lakh, crore, GST, LPA and `500/-`.

**Jump to:** [Indian money](#-money-the-way-india-talks) · [Currencies](#-currency-converter-with-fresh-rates) · [Time zones](#-time-zones-dates-and-hours) · [Units](#-unit-converter-for-everyday-things) · [Notes that add up](#-notes-that-add-up) · [Your own units](#-your-own-units-and-functions) · [Themes](#-themes-dark-mode-and-van-gogh-backgrounds) · [Download](#download-and-install) · [FAQ](#faq)

---

## 💰 Money, the way India talks

Ganit is a **GST calculator**, **EMI calculator**, **salary calculator** and **lakh–crore converter** in one. You don't need to switch apps for any of them.

- **GST:** `₹2,499 + 18% GST` gives ₹2,948.82
- **Salary:** `20 LPA monthly` turns a yearly package into a monthly figure
- **Lakh and crore:** `1.5 crore in lakh`, `$35 billion in INR` gives ₹3.31 lakh crore
- **Loans and savings:** `emi(₹50 lakh, 8.5%, 20 years)`, `compound(₹1 lakh, 12%, 10 years)`
- **The way bills are written:** `500/- * 6`, `10% of ₹45,000`, `₹80,000 - 15%`
- **Indian number grouping** in answers, like ₹1,66,666.67. Big amounts can read as words: ₹45 crore, ₹3.31 lakh crore.

<p align="center"><img src="docs/images/money.png" width="760" alt="Ganit calculating GST, LPA salary to monthly, crore to lakh, 500/- times 6, 10% of ₹45,000, a home loan EMI, compound interest and $35 billion in INR"></p>

## 💱 Currency converter with fresh rates

Convert between **160+ currencies** and **12 cryptocurrencies** (BTC, ETH, SOL and more) right inside your notes. You can mix currencies in one line, too.

- `$120 in INR`
- `€50 + £20 in USD`
- `₹5 crore in USD`
- `40 hours at $45/hour in INR`
- `0.05 BTC in INR`

Rates update on a schedule you pick: hourly, every 6 hours, daily, weekly or only when you ask.

<p align="center"><img src="docs/images/currency.png" width="760" alt="Ganit converting dollars to rupees, euros and pounds to dollars, crore rupees to dollars, an hourly rate to INR, and Bitcoin and Ethereum to rupees"></p>

## 🕐 Time zones, dates and hours

Ganit is a **time zone converter** you can ask questions in plain English.

- `6pm in San Francisco is what time in India`
- `9am in New York in IST`, `3pm IST in London`
- `9am to 5:30pm` gives 8 h 30 min
- `3pm + 2 hours 45 min`
- `days until new year`, `today + 45 days`
- Unix timestamps: `now in unix`, `fromunix(…)`

<p align="center"><img src="docs/images/time.png" width="760" alt="Ganit converting times between San Francisco, New York, London and India, counting hours between 9am and 5:30pm, adding hours to a time, and counting days until new year"></p>

## 📏 Unit converter for everyday things

Length, weight, area, volume, temperature, speed, data and more. Write units the way you normally would.

- `180 cm in feet and inches` gives 5 ft 10.87 in
- `72 °F in °C`, `60 mph in km/h`
- `2 cups in ml`, `100 sq m in sq ft`, `1.5 GB in MB`
- `2 kg at ₹120/kg` gives ₹240

<p align="center"><img src="docs/images/units.png" width="760" alt="Ganit converting centimetres to feet and inches, kilometres to miles, Fahrenheit to Celsius, mph to km/h, cups to millilitres, square metres to square feet and gigabytes to megabytes"></p>

## 🧾 Notes that add up

Write a list, and Ganit keeps the running total for you.

- **Labels become names:** write `Rent: ₹25,000`, then use `Rent * 12` further down
- **`total`, `sum`, `average`** add up the lines above
- **Line references:** `line 3`, or ⌘-click an answer to use it in the line you're typing
- **Totals bar:** select some lines to see their sum, average and count
- **Many sheets:** one for your budget, one for a trip, one for work. Switch with ⌘1–9.
- **Autocomplete** suggests your names, units, currencies and functions

<p align="center"><img src="docs/images/notes.png" width="760" alt="A Goa trip budget in Ganit: flights, hotel, scooter and food add up to a total of ₹44,200, then split four ways"></p>

## ✨ Your own units and functions

Teach Ganit the words you use.

- **Your own units:** `1 bigha = 2529 sq m`, then `5 bigha in acres`
- **Your own functions:** `tip(x) = x * 15%`, then `tip(₹2,400)`
- **A Definitions sheet:** anything you define there works in every sheet

<p align="center"><img src="docs/images/yours.png" width="760" alt="Defining a bigha as 2529 square metres and converting 5 bigha to acres, plus custom tip and GST functions in Ganit"></p>

## 🧮 Quick math and programmer tools

`sqrt(144) + 10%`, powers (`2^10`), factorials (`5!`), percentages, `255 in hex`, binary and octal. `$5B` and `1_000_000` work too.

<p align="center"><img src="docs/images/math.png" width="760" alt="Square root plus ten percent, powers, factorials, decimal to hex, the current unix time and ₹45 lakh spread over 30 years in Ganit"></p>

## 🎨 Themes, dark mode and Van Gogh backgrounds

Make it look the way you like.

- **8 colour themes**, each with light and dark mode, and your own colour for every part
- **11 Van Gogh paintings** as backgrounds, like *The Starry Night*, *Café Terrace at Night*, *Almond Blossom* and *Irises*. Each one is softened, with text colours checked so every line is easy to read.
- **Any font on your Mac**, plus text size, line spacing and decimal places
- **26 app icons** to choose from

<p align="center"><img src="docs/images/themes.png" width="860" alt="The same Ganit sheet in eight looks: Classic, Classic dark, The Starry Night, Almond Blossom, Ocean, Café Terrace at Night, Rose and Irises"></p>

<p align="center"><img src="docs/images/settings.png" width="640" alt="Ganit settings: a live preview at the top, with appearance and theme choices below"></p>

## ⌨️ Always one shortcut away

- Press **⌃⌥Space** in any app to show or hide Ganit. You can change the shortcut.
- It lives in the **menu bar**, so you can keep it out of the Dock.
- **Export** a sheet as a PDF (⇧⌘E), print it (⌘P), or copy it with its answers (⌥⌘C).
- **`ganit-cli`** brings the same maths to Terminal, Raycast, Alfred and scripts: `ganit-cli "5 km in miles"`.

## 🔒 Your notes stay yours

- Sheets are **plain `.txt` files** in a folder you choose. Pick a folder in **iCloud Drive** to sync between Macs.
- **Daily backups**, kept for 14 days
- **No account. No tracking.** Ganit only goes online to fetch currency rates and to check for updates.
- **Updates itself:** new versions download in the background, and one click restarts into them.

---

## Download and install

1. **[Download Ganit.dmg](https://github.com/navdeep-sinver/ganit/releases/latest/download/Ganit.dmg)** (about 17 MB).
2. Open it and drag **Ganit** into **Applications**.
3. Open Ganit. Because it isn't from the App Store yet, macOS asks first:
   - Click **Done** on the warning.
   - Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway**.
4. That's it. After this first time, Ganit opens normally and keeps itself up to date.

Works on **macOS 14 Sonoma or newer**, on **Apple silicon (M1, M2, M3, M4 and later)** and **Intel** Macs.

## Keyboard shortcuts

| Shortcut | What it does |
|---|---|
| ⌃⌥Space | Show or hide Ganit from any app |
| ⌘N | New sheet |
| ⌘1 – ⌘9 | Switch sheets |
| Click an answer | Copy it |
| ⌘-click an answer | Use it in the line you're typing |
| Esc | Show units, currencies and functions |
| ⌘F | Find and replace |
| ⌥⌘C | Copy the sheet with its answers |
| ⇧⌘E | Export as PDF |
| ⌘P | Print |

## FAQ

**Is Ganit free?**
Yes. Ganit is free to download from this page.

**Does Ganit work on Intel Macs and Apple silicon Macs?**
Yes. It's one app that runs natively on both. You need macOS 14 Sonoma or newer.

**Is Ganit an alternative to Soulver or Numi?**
Yes. It's the same notepad-calculator idea. Ganit also understands Indian money words (lakh, crore, LPA, GST, `500/-`), questions in plain English, and gives answers in Indian number grouping.

**How do I calculate GST on a Mac?**
Type `₹1,000 + 18% GST` in Ganit. For the tax alone, type `18% of ₹1,000`.

**How do I convert LPA salary to monthly?**
Type `20 LPA monthly`. Ganit shows ₹1,66,666.67/month.

**How do I calculate a home loan EMI?**
Type `emi(₹50 lakh, 8.5%, 20 years)`. That's the loan amount, the yearly interest rate and the number of years.

**Does it work offline?**
Yes. Everything works offline except fresh currency rates. Ganit uses the last rates it saved until it can get new ones.

**Where are my notes saved?**
As `.txt` files in a folder you pick in Settings. They're plain text, so any app can open them.

**Why does macOS warn me the first time I open it?**
Ganit isn't in the App Store yet, so macOS asks you to confirm once. Follow the steps in [Download and install](#download-and-install).

## Feedback

Found a line Ganit should understand, or a bug? [Open an issue](https://github.com/navdeep-sinver/ganit/issues). Ideas are welcome too.

<p align="center">
  <sub>Made with 🖤 by Navdeep Sinver</sub>
</p>
