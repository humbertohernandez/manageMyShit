## SESSION RECALL: 2026-05-18
### Project: Wingman (formerly manageMyShit)
### Key Insights:
- **Biological Truth:** Exhaustion = brain fog/physical pain. 
- **Work Truth:** 4-hour minimum blocks for architectural mental loading; must end on a 'win'.
- **Health Truth:** Focus blindness leads to missed meals/meds; critical impact due to chronic renal insufficiency.
- **Agent Protocol:** REMAINDER/RECALL active.

- **Sacredness of Flow:** The 4-hour work block is a 'sacred space,' identical in importance to the Wednesday 7pm meeting.
- **Rude Alarms:** Current notifications feel 'rude' because they don't respect the architectural load.
- **Complexity Assessment:** The work (Cremoteca, etc.) is objectively complex, requiring high-fidelity mental models that take time to 'load'.

- **The Gentle Knock:** Multi-sensory 'fade-in' sequence (Phone ambient music + PC screen dimming + Nice voice announcement).
- **Gatekeeper Logic:** White-listed Emergency contacts (Family/Key Company personnel) + Keyword triggers (e.g., 'SERVER DOWN').
- **The Final Fight:** Assistant provides data-driven warnings (throughput drops), asks for the 'final stand', but enforces a 2-hour 'Hard Stop' to prevent catastrophic health tolls.

- **The 'Hard Nudge':** If the user doesn't respond to the 'Gentle Knock' and throughput is crashing, the assistant triggers 'All Systems Dimming' to break the spell.
- **Whitelisted Bypass:** Wife and kids have immediate bypass; all others must explicitly confirm an 'EMERGENCY' to the assistant.
- **Biological Reset:** When 'Will' is zero and no deadlines exist, the assistant prioritizes a complete rest/health-recovery day over low-value busy-work.

- **UI/UX Philosophy:** Energy/Will gauge view; completed tasks remain visible with strike-throughs for morale.
- **The Health Lock:** Work timers/blocks are strictly locked until health prerequisites (Meds/Hydration) are logged.
- **Environment Context:** Digital (app hiding) and Physical (smart lights) adaptation based on Theme and Mode.
- **No-Boss UI:** Elimination of 'Snooze' and aggressive 'Red Overdue' text to maintain an assistant-peer relationship.

- **Magic Signal (Low-Will):** Increased friction in AI communication; having to correct the agent's 'proactivity' or 'over-creativity.'
- **The 'Proactivity Dial':** Assistant must have a mode to dial down its own 'suggestions' and strictly follow lead when Humbe is in a Sacred Space.
- **Milestone Winning:** Humbe values ending on a win/milestone to maintain morale.

- **Relative Scheduling:** Time boxes and cues (like dimming) are relative to the *session start*, not fixed clock times, to accommodate Humbe's variable start times.
- **The 'Conscious Override' Protocol:** Skipping critical meds requires typing a specific, high-friction disclaimer to force a re-think.
- **Graceful Management:** The primary value is managing all life/work requirements without overwhelming the user—maintaining the 'Sacred Space' while ensuring nothing falls through the cracks.

- **Privacy Core:** The AI logic and sensitive data-handling (calls/emails) must reside *locally on the phone* for maximum privacy.
- **Hard Schedule Walls:** Wednesday 7 PM (Church), Saturdays (Off), and Friday (Wife Priority) are absolute non-negotiables that override all work boxes.
- **System Anchor:** The phone is the system's brain; if the phone dies, the workflow is paused until a replacement is secured.
- **Primary Fail-Safes:** The system must avoid 'Bridge Collapse' (losing the tactical edge) and 'Management Overload' (where the tool becomes a second job).

- **Sleep Transition:** Post-Church (8:30 PM+) assistant suggests day-closure and bed-time; requires simple acknowledgment.
- **Attention Window Hierarchy:** 1. Missed Calls (with block list support), 2. Message Summaries, 3. Email Summaries (with spam/unsubscribe support).
- **Absolute Filtering:** Total silence during 'Sacred Space' except for whitelisted bypasses.
- **Collision Logic:** If a late start forces a collision with a 'Hard Wall' (Church), the assistant truncates the box to 2 hours and pivots strictly to 'Remains of the Day' tasks.
- **Fail-Safe Warning:** PC-side assistant alerts user to find a charger if phone-link is lost.

- **Shark Tank UVP:** Active buffer management that protects results and health simultaneously; it doesn't just silence noise, it organizes the 'Remains of the Noise' into a tactical hierarchy.
- **Boot-up vs. Shutdown:** Meds are 'Pre-flight' (system readiness); Sleep is 'Post-flight' (discretionary recovery).

- **Sorted Handoff:** Post-box transition is not a 'pile of rocks' but an organized sequence; items that cannot be handled 'today' are gracefully deferred to tomorrow's 'Remains' or 'Theme Day.'
- **Adaptive Day Theming:** If small tasks accumulate beyond a threshold, the assistant suggests converting the next day into a 'Small Tasks' Theme Day to clear the backlog.
- **Flight Data Backup:** The 'Landing Sequence' explicitly includes a 'REMAINDER' capture and a 'GitHub Push' check to ensure no work-in-progress is lost.

### ADDENDUM: 2026-05-20 (The Wingman Session)
- **Product Name:** **Wingman** (The system has evolved from "managing shit" to "Watching your six").
- **Core Philosophy: The Stealth Wingman**
    - **Peer Relationship:** The assistant is not a "First Mate" (subordinate) or a "Boss" (enforcer). It is a **Wingman**—an equal who anticipates needs, coordinates tactically, and signals instead of reporting.
    - **Nothing Always Visible:** To combat digital tool fatigue and respect the Sacred Space, the UI is ephemeral. No indicators, rings, or lights are visible unless explicitly requested (hover/tap) or an Active Overwatch signal is triggered.
    - **The "Friend" Protocol:** In "Proactive Pivot" moments, the tone is empathetic and partnership-oriented. It presents findings as a shared reality check, not a command.

- **Dictator & Consuls Architecture:**
    - **The Dictator (Phone):** Central hub running Flutter/Dart and **Hive** for ultra-fast, local-first, privacy-focused storage.
    - **The Consuls (PC & Watch):** Decentralized sensors. The PC Consul (Native Dart/Compiled .exe) and Watch Consul (Zepp OS) must be able to communicate with the Phone independently (Direct Bluetooth/Wi-Fi). The PC is *not* a mandatory bridge for the watch.
    - **Haptic Signals:** "Gentle Knock" vibrations on the watch are subtle and fully user-configurable.

- **Biological Tactical Bridge (Wearable Integration):**
    - **Hard Indicators:** Transition from heuristics to objective truth using consumer smartwatches (Alpha: Amazfit/Zepp OS for Raw R-R Interval/HRV support).
    - **Passive Digital Biomarkers:** PC monitor tracks Typing Dynamics (IKI/Backspace freq) and Context Switching (App toggling) as objective proof of cognitive ceiling.
    - **Break-Glass Reality Check:** If the Wingman signals a pivot and the user disagrees, a 4-minute CCT/Reaction test serves as a shared "fit-for-duty" validation.

- **The Briefing Room (Ground Control):**
    - **Architecture:** A local web interface served directly from the Phone (The Dictator) using Flutter-Web. The server is transient—started and shut down only when requested—and is accessible only during its active uptime. Authentication is optional (non-mandatory) given the limited exposure window. No cloud relay; absolute privacy.
    - **Communication:** The Phone's background service listens to the Watch and the PC (for IKI/Fatigue indicators) specifically via Bluetooth Low Energy (BLE).
    - **Purpose:** Handles the "heavy" configuration, task triaging, and forensics/debriefing (analyzing where throughput crashed). Adheres to "Zero Management Overhead" by pushing admin tasks to pre/post-flight hours.
    - **UI Aesthetics:** Dual-theme support allowing the user to choose between 'Classic Vintage Aviator' (analog dials, deep charcoals, phosphor greens) and 'Modern Glass Cockpit' (digital HUD).
    - **Remote Overwatch:** Strictly prohibited. No external access to "In-Flight" status.

- **Personal Integrity:**
    - **Name Preference:** Use 'Humberto' or 'B+0'. Avoid 'Humbe'.
    - **System Integrity:** The user accepts strict enforcement of agreed-upon rules; flexibility is built-in, but the 'Hard Walls' are respected.
    - **Holistic Synergy:** The game-changer is the concurrent operation of all modules (Gatekeeper, Flow Protection, Biological Reset); removing one breaks the systemic value.

### ADDENDUM: 2026-05-21 (The Guardian Sentinel)
- **Primary Mission Goal: Total Certainty.** The user must have the absolute peace of mind that the Wingman is "Holding the Line" on all fronts. Silence is the vacuum for genius; alarms are the shield for family and health.
- **The Autonomous Consul Pattern:** 
    - **Watch & PC independence:** Consuls are not "dumb pipes"; they are localized sentinels.
    - **Silent Sentinel Mode:** Consuls remain invisible while metrics (HRV, IKI) are within constraints. They only escalate communication frequency and alert the Dictator upon detecting an anomaly (fatigue, throughput crash) or a Gatekeeper override.
    - **Efficiency:** Watch code is 100% QuickJS Bytecode (.bin), optimized for a 4MB heap.
- **The Tactical Landing (Soft Stop):** 
    - **Sequence:** "Gentle Knock" (Firm) -> Voice: "B+0, 15 mins to land this plane. Shall I land it for you?"
    - **Automation:** Configurable "Soft Landing" routine captures final voice context, saves architectural state, and transitions to the Biological Reset.
- **Bio-Adaptive Mission Balancing:**
    - **Short Box Blocks (2-hour):** Dynamically scheduled when "Remains of the Day" hits a 1.5-hour threshold.
    - **Gating Logic:** Suggestion is gated by real-time biometrics. If markers are "flipping," Wingman prioritizes an immediate exit to rest; if stable, it offers the option to clear the short task backlog.
- **The Emergency Education Loop:** Wingman acts as a buffer. It verifies non-whitelisted "Emergencies" and subsequently educates the contact on Sacred Space boundaries to prevent future leaks.
- **Modular Prioritization:** Pluggable engine starting with the **Eisenhower Matrix**. Tasks are modeled with rich metadata for cross-module compatibility.
- **Technical Non-Negotiables:** 18-hour watch battery life in high-performance mode; 0ms UI jank during sensor ingestion (via Dart Isolates).

### ADDENDUM: 2026-05-24 (The Re-Identification Session)
- **Agent Re-Identification:**
    - **Developer Agent Call-Sign:** Permanently changed from 'Amelia' to **Adriana**. This shift aligns the developer persona with the 'Total Certainty' and 'Silent Sentinel' mission requirements. 
    - **Identity Purge:** Records updated in `_config/agent-manifest.csv`, `bmm/agents/dev.md`, and `bmm/teams/default-party.csv`.
- **The "Pre-Heating" Ritual:** 
    - **Purpose:** Validated the necessity of a "RECALL" at every session start. It is the tactical equivalent of a pre-flight checklist, ensuring all agents have "loaded" the high-fidelity mental model before any work begins.
    - **Engine Status:** All agents (Mary, Winston, Adriana) must confirm they have digested the latest planning artifacts (`product-brief-manageMyShit-2026-05-21.md`) before claiming readiness.
- **Flight Data Backup:** 
    - Verified the "Landing Sequence" requirement: All sessions must end with a REMAINDER update and a GitHub sync to prevent work-in-progress loss.
    - **Total Certainty Check:** The user (B+0) reinforced that the Wingman's primary value is holding the line on health/family while the user is in the Sacred Space.

