# 🏓 PickleStackPro — Open Play Dashboard

The #1 open play paddle stack management system built for pickleball facilitators. No installation. No login. No internet required. Just open and play.
**By:** Norman Brigz | Built in Cebu, Philippines 🇵🇭

---

## 📌 What is PickleStackPro?

PickleStackPro is a free, browser-based open play management dashboard designed specifically for pickleball facilitators, club organizers, and court managers. It replaces the traditional physical paddle stack with a smart digital system that handles player queuing, court assignments, score tracking, and fair rotation — all in one place. No app store. No subscription. No setup. Download the file, open it in any browser, and you're ready to run your open play session in seconds.

---

## ✨ Key Features

### 🎮 Simple Dual Queue System
- Two clear skill categories — 🌱 **Beginner** and ⚡ **Int/Adv** — no confusing letter grades
- Add a player in one motion: type their name, tap their category, done — they're instantly in the queue
- Queues display in strict registration order: first player added is always first in line
- Fair rotation priority: never-played players go first, then winners, then losers — all sorted automatically by which court finished first
- Special pairing rule: if only 1–2 unplayed players remain, they're matched with top winners so no one waits unnecessarily long

### 🏟 Court Management
- Add unlimited courts with custom names (Court 6, 7, 8 — whatever your venue uses)
- Assign Beginner or Int/Adv category per court
- Inline dropdowns for precise player placement on each court slot
- Live court timer with progress tracking
- One-click **Auto-Fill** pulls the next 4 players from the correct queue

### 🔄 Match Rotation
- Game Over → enter the final score → review the Next Match Preview → confirm and the next match starts immediately
- Score entry defaults to **11–11** — just adjust the losing team's number, since most games end at 11
- Built-in safety check warns you if both scores still match before you confirm, so a forgotten entry never accidentally hands a free win
- Winners stay prioritized, losers rotate to the back — all automatic
- Swap players between teams or pull in someone from the queue before the match starts
- All players return to their queue after each game — full rotation enforced

### 👥 Player Management
- All-time player roster saved in your browser (`localStorage`) — never re-enter a name twice
- Autocomplete search — type 2 letters, arrow key to navigate, Enter to add
- Players retained between sessions (auto-saved for up to 12 hours)
- Player history: games played, wins, win percentage, last seen date

### 📊 Statistics & Reports
- Live leaderboard with win rate per player
- Match history log with scores, teams, court, and duration
- Court utilization breakdown
- Session analytics: average game duration, average games per player
- Export a full CSV report — match log and leaderboard in one click

### 🎨 Professional Dashboard
- Dark mode premium UI throughout
- **6-page navigation:** Dashboard, Courts, All Players, Player Roster, Match History, Statistics
- **Quick Actions** panel: Rotate All Courts, Add Court, Shuffle Queue
- At-a-glance **Session Stats** in the sidebar: players in queue, games played, total players, most active player
- Editable facilitator profile (name, role, venue)
- Session timer with live court status indicators
- Fully mobile-responsive with bottom navigation for phones

---

## 📖 How to Use

**Option A — Use the Live Link**
Click the live demo link above. No download needed.

**Option B — Download & Run Locally**
1. Download `index.html`
2. Open it in Google Chrome, Edge, or Firefox
3. That's it — fully functional offline

### Running Your First Open Play Session
1. Click **Add Player** on the dashboard, type a name, and tap **Beginner** or **Int/Adv** — they're instantly in the right queue
2. Add courts and set each court's category (Beginner or Int/Adv)
3. Click **Auto-Fill** to pull the next 4 players from that court's queue
4. Click **Start Match** to begin the first game
5. When the game ends, click **Game Over**, confirm the score, review the **Next Match Preview**, then confirm — the system handles rotation, prioritization, and queue management automatically

---

## 🔄 Queue Priority Rules

| Priority | Group | Description |
|----------|-------|--------------|
| 1 | 🆕 Never Played | First registered, first to play (FIFO) |
| 2 | 🏆 Winners | Sorted by which court finished earliest |
| 3 | 💔 Losers | Sorted by which court finished earliest |
| 4 | 💤 Resting | Has played, waiting for next rotation |

**Special Rule:** If only 1–2 unplayed players remain, they're paired with top winners so no one waits unnecessarily long.

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Vanilla HTML, CSS, JavaScript |
| Storage | Browser `localStorage` (no server needed) |
| Fonts | Space Grotesk, Inter (Google Fonts) |
| Hosting | GitHub Pages |
| Backend | None — fully client-side |

---

## 📱 Browser Compatibility

| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Fully supported (recommended) |
| Microsoft Edge | ✅ Fully supported |
| Mozilla Firefox | ✅ Fully supported |
| Safari | ✅ Supported |
| Mobile Chrome (Android) | ✅ Supported |
| Mobile Safari (iOS) | ✅ Supported |

---

## 🗺 Roadmap

- [ ] Cloud sync — share session across multiple devices
- [ ] Multi-facilitator support
- [ ] Tournament bracket mode
- [ ] Player skill rating system (ELO-based)
- [ ] QR code check-in for players
- [ ] Native Android & iOS app
- [ ] Venue dashboard for court owners — evolving into **PICKLEBOOK PH**

---

## 🤝 Contributing

PickleStackPro is currently maintained by Norman Brigz. If you have feature requests, bug reports, or suggestions:

- Open an [Issue](../../issues) in this repository
- Or message directly via [Facebook](https://www.facebook.com/normz.kinsidosi/)

---

## 📄 License

This project is free to use for personal and community open play facilitation. For commercial licensing, white-label, or venue integration inquiries, contact Norman Brigz.

---

## 👤 About the Developer

Norman Brigz is the founder and creator of PickleStackPro, built right here in Cebu City, Philippines. An Electronics Engineer by background and a serial businessman — also the owner of Brigz Scrap Trading — Norman has always been driven to solve everyday problems with practical, no-nonsense solutions.

As an active open play facilitator himself, Norman experienced firsthand the chaos of managing paddle stacks, court rotations, and player queues with nothing but paper and guesswork. So he built the tool he wished existed — a clean, dark-mode dashboard that takes the guesswork out of running open play sessions, designed for how Filipino pickleball communities actually play.

Looking to bring something like this to your own court, club, or sport? Norman is open to building custom tools, white-label versions, or full venue management systems — just reach out via [Facebook](https://www.facebook.com/normz.kinsidosi/).

🌐 **Business:** Brigz Scrap Trading
📍 **Based in:** Cebu City, Philippines
🏓 **Built for:** The Philippine pickleball community

---

*Made with ❤️ for the pickleball community of Cebu and the Philippines.*
