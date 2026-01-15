# Wellness & Medication Tracker

## Quick Access
**Live App:** https://kandyangel27.github.io/wellness-tracker/

**GitHub Repo:** https://github.com/KandyAngel27/wellness-tracker

---

## What This App Does

A personal health tracking app for monitoring:

### Medications Tracked
| Medication | Schedule | Time |
|------------|----------|------|
| TRT Shot | Weekly (Friday) | - |
| NAD+ Shot | Weekly (Monday) | - |
| Wellbutrin 300mg XL | Daily | Morning |
| One A Day Multivitamin | Daily | Morning |
| Iron | Daily | Afternoon |
| Vitamin C | Daily | Afternoon |

### Features
- **Calendar View** - See your daily check-ins at a glance
- **Daily Check-In** - Log medications taken, sleep, symptoms, side effects
- **TRT & NAD+ Dashboard** - Track shots with libido/energy graphs
- **Sleep Tracking** - Hours, quality, wake-ups, morning energy
- **Symptom Tracking** - Energy, mood, libido, mental clarity, anxiety, temperature
- **Wellbutrin Tapering** - Track dose reductions and withdrawal symptoms
- **Lab Results** - Store and graph your blood work (testosterone, estrogen, ferritin, etc.)
- **Recovery Timeline** - What to expect week-by-week after restarting Wellbutrin
- **Desktop Notifications** - Reminders for medications
- **Backup/Export** - Save your data to a JSON file

---

## How to Install as Desktop App

1. Open https://kandyangel27.github.io/wellness-tracker/ in Chrome
2. Click the install icon in the address bar (monitor with arrow)
3. Or: Click 3 dots menu → "Install Wellness Tracker"
4. App will open in its own window with no browser toolbar

---

## How to Backup Your Data

1. Go to the **Reminders** tab
2. Scroll to the green "Backup & Restore" section
3. Click **Export Backup** - saves a JSON file
4. Store the file in OneDrive/Google Drive for safekeeping
5. To restore: Click **Import Backup** and select your JSON file

**IMPORTANT:** Back up weekly, especially after entering lab results!

---

## Data Storage

- Data is stored in your browser's localStorage
- Data does NOT sync between devices (phone vs computer have separate data)
- If you clear browser data, your tracking history will be lost - USE BACKUPS!

---

## Files in This Project

| File | Purpose |
|------|---------|
| `index.html` | The main app (all HTML, CSS, JS in one file) |
| `manifest.json` | PWA configuration (app name, icon, colors) |
| `sw.js` | Service worker for offline support |
| `README.md` | This file |

---

## Current Tracking Goals

### Wellbutrin Restart (Started Jan 15, 2026)
- Restarted 300mg XL after stopping cold turkey
- Tracking withdrawal symptom recovery
- Monitoring sleep, libido, energy improvements

### TRT Journey (Started Nov 25, 2025)
- Weekly injections (Fridays)
- Tracking libido correlation with shots

### NAD+ Therapy (Started Dec 26, 2025)
- Weekly injections (Mondays)
- Tracking energy levels

---

## Making Changes

To update the app:
1. Edit files in `C:\Users\kandy\OneDrive\AngelMetrix SEM\wellness-tracker\`
2. Open terminal in that folder
3. Run:
   ```
   git add -A
   git commit -m "Description of changes"
   git push
   ```
4. Changes go live in 1-2 minutes

---

## Local Development

To test changes locally before pushing:
1. Open terminal in the wellness-tracker folder
2. Run: `npx serve` (requires Node.js)
3. Open http://localhost:3000

---

## Created With
- HTML5, CSS3, JavaScript
- Chart.js for graphs
- PWA (Progressive Web App) for installability
- GitHub Pages for hosting

---

## Support
This app was built with Claude Code (Anthropic's AI assistant).
