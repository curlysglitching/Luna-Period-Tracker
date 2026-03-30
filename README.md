# Luna ☽ — Period & Cycle Tracker

A beautiful, fully private period tracker that runs entirely in your browser. No accounts, no servers, no data collection — everything stays on your device.

Built as a single HTML file, Luna works on any device and can be hosted for free on GitHub Pages.

-----

## ✨ Features

### 📅 Visual Year Calendar

- Full year displayed January through December, one month per screen
- Scroll down to move through the year
- Navigate between years with the arrow buttons at the top
- Automatically opens to the current month

### 🩸 Period Logging

- Click any day to open the day menu
- Log flow intensity: **Light**, **Medium**, or **Heavy**
- Days fill with solid color so your cycle is obvious at a glance
- Choose from 7 period colors: Rose, Coral, Amber, Sage, Sky, Violet, or Fuchsia

### 🔮 Smart Predictions

- **Predicted period days** shown with a dashed orange border, calculated from your average cycle length
- **Fertile window** marked with a purple **!** on each day (5 days before ovulation)
- **Ovulation day** shown with a purple border — estimated 14 days before your next expected period
- Predictions update automatically as you log more cycles

### 📊 Cycle Stats

Live stats displayed at the top of the page:

- **Avg Cycle** — average days between period starts
- **Avg Period** — average length of your period
- **Next Period** — predicted start date
- **Next Ovulation** — predicted ovulation date

### 🏷️ Symptoms & Notes

- Quick-tap symptom tags: Cramps, Bloating, Fatigue, Mood swings, Headache, Spotting, Discharge, Nausea
- Free-text note field for anything extra (medications, observations, etc.)
- Days with notes or tags show a small dot so you can spot them easily
- Manually mark confirmed ovulation days

### 🔒 Completely Private

- Runs 100% in your browser — no login, no account, no internet required after loading
- All data saved to your browser’s local storage only
- Nothing is ever sent to any server

-----

## 🚀 Getting Started

### Option 1: Use the Live Version

If hosted on GitHub Pages, visit:

```
https://yourusername.github.io/luna-period-tracker
```

### Option 2: Run Locally

1. Download `period-tracker.html`
1. Open it in any browser
1. That’s it — no installation needed!

-----

## 🌐 Browser Compatibility

Luna is built for broad compatibility and has been tested across:

|Browser             |Support       |
|--------------------|--------------|
|Chrome / Brave      |✅ Full support|
|Safari (iOS & macOS)|✅ Full support|
|Firefox             |✅ Full support|
|Android Chrome      |✅ Full support|
|Samsung Internet    |✅ Full support|

Includes `-webkit-` prefixes, flex fallbacks, and no modern-only CSS functions — works on older browser versions too.

-----

## 📖 How to Use

1. **Log a period day** — click any date, choose a flow intensity, hit Save
1. **Track symptoms** — tap tags or write a note in the same menu
1. **Watch predictions appear** — after logging at least one full cycle, Luna calculates your next period, fertile window, and ovulation day automatically
1. **Change your color** — pick a new period color from the swatches in the top bar anytime
1. **Browse years** — use the `‹ ›` arrows to view past or future years; your data is saved across all years

Click the **ⓘ** button in the top right for a full in-app guide.

-----

## 🛠️ Technical Details

- **Single file** — everything (HTML, CSS, JavaScript) in one `.html` file
- **Zero dependencies** — no frameworks, no npm, no build step
- **Storage** — uses `localStorage` to persist data across sessions
- **No backend** — fully static, deployable anywhere
- **Fonts** — Google Fonts (Playfair Display + DM Sans), loaded from CDN

-----

## 📁 File Structure

```
luna-period-tracker/
└── period-tracker.html   # The entire app
└── README.md             # This file
```

-----

## 🙏 Credits

Designed and built with [Claude](https://claude.ai) by Anthropic.

-----

*Luna is a personal wellness tool and is not a substitute for medical advice. Cycle predictions are estimates based on your logged data.*
