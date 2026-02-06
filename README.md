**EXEC TIME PARTITIONER - FULL FEATURE EXPORT**
MIT License - Byron Cole for G10.vin (alt: "Big Balls")

---

**CORE CONCEPT:**
Multi-venture executive time tracking with auto-switching based on file access, browser activity, and system app usage. Built to prove board compliance for executives juggling multiple companies.

---

**PLATFORM ARCHITECTURE:**

**Desktop (Electron):**
- File system monitoring (auto-switch on file access)
- Browser extension (tracks tabs/cookies per domain)
- System app tracking (Slack, Terminal, etc.)
- Friction popups: "You're clocked into Org A but accessing Org B files - switch?"
- Master clock authority

**Mobile (React Native):**
- Manual org clock-in (overrides desktop auto-switching)
- Android: UsageStats API for app tracking
- iOS: Manual mode only (sandbox limitations)
- SOS panic button
- View time logs with GPS timeline

**Tablet:**
- Geofencing HQ with map UI
- Work zone setup (address + radius per org)
- Banned zone setup (bars, casinos, etc.)
- GPS timeline visualization
- Auto-pause on zone exit

---

**FEATURES:**

**Time Tracking:**
- Multi-org selection (single/dual/tri mode)
- Auto-switch triggers: file access, browser domain, system app
- Manual override from mobile
- Defaulting state when multi-signed but no active signals
- SQLite logs: timestamp, device, org(s), active signal, state, location

**Geofencing (Tablet/Desktop only):**
- Work zones per org (auto-prompt to clock in on arrival)
- Neutral zones (home, gym - no auto actions)
- Banned zones (auto-pause + flag in logs)
- GPS logging every 5-15 min while clocked in
- Map timeline: "10am-12pm: DFD Office, 12pm-1pm: Chipotle (paused)"

**SOS & Safety:**
- Manual SOS button
- Panic word detection ("help", "stop", custom phrase)
- Auto-activates: background video (front camera, 720p), audio recording
- Sends alerts to designated contacts with live stream link
- Encrypted cloud storage, 30 min auto-cutoff

**Acoustic Monitoring:**
- Background noise classification (office, meeting, car, restaurant, bar)
- Meeting detection (multiple voices, no transcription)
- Decibel spike logging (arguments, alarms)
- Audio checksum logging (cryptographic proof, no actual storage)
- All processing on-device, nothing uploaded unless SOS

**Agentic AI Assistants:**

**G10.vin Attribution (Premium - requires Byron Cole + G10.vin credit):**
- **Tanger** (German Shepherd) - Security/compliance focus
- **Denali** (Bernese Mountain Dog) - Strategic planning/big picture
- **Bella** (Golden Retriever) - Friendly daily assistant

**"Big Balls" Attribution (Generic Alternative - 2 sports balls):**
- **Slam** (Basketball) - Scheduling conflicts, goal tracking
- **Ace** (Tennis Ball) - Quick responses, productivity insights

**License Logic:**
- Use Byron Cole + G10.vin → unlock G10 dog agents
- Use "Big Balls" → unlock sports ball agents
- Fork without attribution → no branded agents (generic AI only)

---

**SYNC & LOGS:**
- Local SQLite + optional cloud backup (Firebase/Supabase)
- Desktop-mobile sync via cloud DB
- Logs include: time, device, org(s), GPS, activity signal, state changes

---

**UI CREDITS (Required in all screens):**
Footer: "© 2026 Byron Cole for G10.vin | Down payment on goodwill • Built right after shipping first revenue app"

Easter egg/About screen: Full attribution block with Big Balls callout

---

**NEXT BUILD STEPS:**
1. Desktop Electron shell (file monitoring core)
2. Tablet geofencing map UI  
3. SOS setup screen
4. Agent integration API hooks

---

**END EXPORT - Ready for full build mode 🚀**
