🏓 PickleStackPro — Open Play Dashboard
The #1 open play paddle stack management system built for pickleball facilitators.
No installation. No login. No internet required. Just open and play.
By: Norman Brigz | Built in Cebu, Philippines 🇵🇭

📌 What is PickleStackPro?
PickleStackPro is a free, browser-based open play management dashboard designed specifically for pickleball facilitators, club organizers, 
and court managers. It replaces the traditional physical paddle stack with a smart digital system that handles player queuing, court assignments, 
score tracking, and fair rotation — all in one place.
No app store. No subscription. No setup. Download the file, open it in any browser, and you're ready to run your open play session in seconds.

✨ Key Features

🎮 Smart Dual Queue System
- Separate queues for 🌱 Beginner (A/B) and ⚡ Intermediate/Advanced (C/D) players
- Fair rotation priority: Never-played players are always first in line
- W/L tagging: Winners and Losers are automatically sorted after each game
- Finish-order priority: The court that finishes first gets queue priority
- Special pairing rule: If only 1–2 unplayed players remain, they are matched with top winners

🏟 Court Management
- Add unlimited courts with custom names (Court 6, 7, 8 — whatever your venue uses)
- Assign Beginner or Intermediate/Advanced category per court
- Inline drag-and-drop player assignment directly from the queue
- Per-slot dropdowns for precise player placement
- Live court timer with 15-minute progress bar
- Rename courts inline with one click

🔄 Match Rotation
- Game Over → enter score → Next Match auto-fills and starts immediately
- Winners stay prioritized, losers rotate to queue — all automatic
- Next Match Preview before confirming — see who plays next
- Swap players between teams or replace with queue players before match starts
- All players returned to queue after each game — full rotation enforced

👥 Player Management
- All-time player roster saved in browser (localStorage) — never re-enter names
- Autocomplete search — type 2 letters, arrow key to navigate, Enter to add
- Players retained between sessions (up to 12 hours auto-save)
- Rapid-entry mode: add multiple players in seconds without clicking
- Player history: games played, wins, win percentage, last seen date

📊 Statistics & Reports
- Live leaderboard with win rate per player
- Match history log with scores, teams, court, and duration
- Court utilization breakdown
- Session analytics: avg game duration, avg games per player
- Export full CSV report — match log + leaderboard in one click

🎨 Professional Dashboard
- Dark mode premium UI
- 5-page navigation: Dashboard, Courts, Players, Match History, Statistics, Player Roster
- Editable facilitator profile (name, role, venue)
- Session timer, live court status indicators
- Mobile-responsive layout

📖 How to Use
Option A — Use the Live Link
Click the live demo link above. No download needed.

Option B — Download & Run Locally
1. Download `pickleball_openplay_dashboard_22.html`
2. Open it in Google Chrome, Edge, or Firefox
3. That's it — fully functional offline

Running Your First Open Play Session
1. Add players to the Beginner or Adv/Int queue using the quick-add bar (type name + Enter)
2. Add courts and set each court's category (Beginner or Advanced)
3. Click Auto-Fill to pull the top 4 players from queue into a court
4. Click 🏓 Start Match to begin the first game
5. When done, click 🏁 Game Over → enter score → review Next Match Preview → click Next Match
6. The system handles all rotation, prioritization, and queue management automatically

🔄 Queue Priority Rules (International Standard)
| Priority | Group | Description |
|----------|-------|-------------|
| 1 | 🆕 Never Played | First registered, first to play (FIFO) |
| 2 | 🏆 Winners | Sorted by which court finished earliest |
| 3 | 💔 Losers | Sorted by which court finished earliest |
| 4 | 💤 Resting | Has played, waiting for next rotation |

Special Rule: If only 1–2 unplayed players remain, they are paired with top winners so no one waits unnecessarily long.

🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML, CSS, JavaScript |
| Storage | Browser localStorage (no server needed) |
| Fonts | Space Grotesk, Inter (Google Fonts) |
| Hosting | GitHub Pages / Netlify |
| Backend | None — fully client-side |

📱 Browser Compatibility

| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Fully supported (recommended) |
| Microsoft Edge | ✅ Fully supported |
| Mozilla Firefox | ✅ Fully supported |
| Safari | ✅ Supported |
| Mobile Chrome (Android) | ✅ Supported |
| Mobile Safari (iOS) | ✅ Supported |

🗺 Roadmap
- [ ] Cloud sync — share session across multiple devices
- [ ] Multi-facilitator support
- [ ] Tournament bracket mode
- [ ] Player skill rating system (ELO-based)
- [ ] QR code check-in for players
- [ ] WhatsApp / Facebook Messenger integration
- [ ] Native Android & iOS app (Flutter)
- [ ] Venue dashboard for court owners

🤝 Contributing

PickleStackPro is currently maintained by Norman Brigz. If you have feature requests, bug reports, or suggestions:

1. Open an Issue in this repository
2. Or message directly via Facebook: Norman Brigz

📄 License

This project is free to use for personal and community open play facilitation.
For commercial licensing, white-label, or venue integration inquiries, contact Norman Brigz.

👤 About the Creator

Norman Brigz is a Cebu-based entrepreneur, digital marketing strategist, and pickleball enthusiast. 
PickleStackPro was built out of a real need — managing open play sessions manually was chaotic. This tool was designed by a 
facilitator, for facilitators.

🌐 Business: BRIGZ Scrap Trading
📍 Based in: Cebu City, Philippines
🏓 Built for: The Philippine pickleball community

Made with ❤️ for the pickleball community of Cebu and the Philippines.
