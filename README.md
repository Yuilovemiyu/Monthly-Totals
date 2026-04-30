# 📊 HC/PG SA Monthly Report

A fast, simple web app for tracking daily and monthly reports of HC/PG Sales Associates.

---

## 🚀 Features

- ✅ No login required (instant access)
- ✅ Enter name, store, and rest day once
- ✅ Daily report table acts as live editor
- ✅ Add, edit, and delete entries before saving
- ✅ Firestore database sync
- ✅ Monthly totals auto-computed
- ✅ Bonus calculator (built-in modal)
- ✅ Installable as a mobile app (PWA)
- ✅ Works offline (cached)

---

## 🧠 How It Works

1. Enter:
   - Name
   - Store
   - Rest day

2. Add entries:
   - Fill form
   - Click **Add Entry**

3. Daily Table:
   - Shows saved + unsaved entries
   - Unsaved entries highlighted
   - Editable before saving

4. Save:
   - Click **Save All**
   - Data goes to Firestore
   - Monthly totals auto-update

---

## 📅 Daily Report = Working Area

- Acts as:
  - Preview
  - Editor
  - Data viewer

- Actions:
  - ✏️ Edit saved entries
  - 🧹 Delete unsaved entries
  - 🟢 Green rows = not yet saved

---

## 📊 Monthly Totals

- Auto-calculated per:
  - Month
  - Store

- Updates instantly after saving

---

## 💰 Bonus Calculator

Accessible via:
> "💰 Open Bonus Calculator"

- Opens inside modal
- No page reload

---

## 📦 Tech Stack

- HTML / CSS / JavaScript
- Firebase Firestore
- Progressive Web App (PWA)
- Service Worker (Offline Support)

---

## ⚠️ Notes

- No authentication system
- Designed for internal/team use
- Anyone can edit data

---

## 🔧 Future Improvements (Optional)

- 🔒 Admin PIN protection
- 📅 Prevent duplicate entries per store/day
- 📱 Auto-save locally (offline-first)
- 🏆 Store ranking system
- 🚫 Rest day entry blocking

---

## 📲 Installation (Mobile)

1. Open in browser
2. Tap **Add to Home Screen**
3. Use like a native app

---

## 👨‍💻 Developer Notes

- Cache version: `hcpg-report-v3`
- Update cache name when pushing new changes
- Firestore collections:
  - `reports`
  - `monthly_totals`

---

## ✅ Status

✔ Stable  
✔ Optimized for speed  
✔ Ready for team use  
