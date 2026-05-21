---
stepsCompleted: [1, 2, 3, 4]
inputDocuments: []
date: 2026-05-21
author: Humberto
---

# Product Brief: Wingman (formerly manageMyShit)

<!-- Content will be appended sequentially through collaborative workflow steps -->

## Executive Summary

Wingman is an uncompromising, privacy-first "Chief of Staff" designed to protect the user's health ("biological truths"), family obligations, and flow state ("sacred space") simultaneously. It acts as an aggressive, context-aware gatekeeper against digital noise while ensuring critical health prerequisites (medications, hydration) are met. By balancing deep work protection with an "Autonomous Consul" system—which monitors biometrics and digital biomarkers locally and silently—it provides the "Total Certainty" required for high-fidelity mental modeling. The system is built on a hierarchy of needs: family and health are the absolute "Hard Walls" that justify and enable the "Machine-like" performance required for professional excellence.

---

## Core Vision

### Problem Statement

Deep, complex architectural work requires extended (4-hour minimum) blocks of uninterrupted focus. However, this "focus blindness" leads to skipping critical health routines and invites exhaustion. Simultaneously, the mental tax of managing a backlog and filtering interruptions creates "Administrative Leaks" that deplete the user's "Will." Existing tools fail because they are "bossy" rather than "protective," treating all stimuli as equal and failing to distinguish between a trivial notification and a family emergency.

### Proposed Solution

A holistic, multi-device ecosystem (Watch, Phone, PC) that operates as a **Guardian Sentinel**. 
- **The Gatekeeper:** A rigid whitelist that enforces total silence for the world while maintaining a high-fidelity "Emergency Override" for immediate family.
- **The Autonomous Consul:** Localized sensors on the Watch and PC whom perform silent, real-time analysis of HRV and typing dynamics. They remain invisible while metrics are within constraints but escalate communication frequency instantly upon detecting an anomaly or a "Gatekeeper" emergency.
- **Tactical Time Management:** Tasks are organized into a strict hierarchy. "Sacred Space" blocks are protected, while all other administrative noise is auto-sorted into "Attention Windows" for decisive batch processing.

---

## Mission Architecture & Logic

### The Modular Prioritizator
To ensure the system remains flexible and future-proof, the prioritization engine is a **pluggable module**.
- **The Model:** Tasks are modeled with rich metadata (complexity, urgency, context) to be readable/writable by any prioritizator.
- **Initial Implementation:** An **Eisenhower Matrix** (Urgent/Important) logic will serve as the default module to categorize the backlog.

### Mission Balancing (Bio-Adaptive Logic)
The Wingman manages the mission workload dynamically based on the state of the "Airman" (User):
- **Hard Task Blocks (4-Hour):** The standard for deep architectural "Sacred Space."
- **Short Box Blocks (2-Hour):** Used to clear the "Remains of the Day" backlog.
    - **Scheduling Trigger:** If the backlog is < 1.5 hours, the Wingman suggests a Short Box after the 2nd or 3rd Time Box.
    - **Bio-Gating:** Suggestions are filtered by **Will-Power and Biometrics**. 
        - If markers are "flipping" (declining), the Wingman defaults to a "Remains of the Day" exit (administrative/rest).
        - If markers are stable, it presents the *option* to clear the short task backlog via a Short Box.
- **Adaptive Attention Windows:** During Short Boxes, "Attention Windows" are more frequent to process administrative overhead, though the Sacred Space vacuum remains active for the duration of individual tasks to prevent drift.

---

## Target Users

### Primary Users

#### The Strategic Architect (B+0)
- **Context:** An expert engaged in high-fidelity mental modeling. Requires extreme focus and deep "Sacred Space" blocks, but manages chronic health needs (renal health/medication) and high-value family commitments.
- **Motivations:** To perform "like a machine" during work hours to ensure the absolute freedom and well-being of his family.
- **Problem Experience:** "Focus Blindness" and "Administrative Leaks." skips meds/water during flow and feels "nibbled to death" by non-critical digital interruptions.
- **Success Vision: The "Total Certainty" State.** The peace of mind that comes from knowing the Sentinel is holding the line. Silence is the default, but an emergency will pierce through instantly across all devices (Watch, Phone, PC).

### Secondary Users
- **Care Takers (Future Iteration):** Individuals who may need access to the "Biological Truth" data if a "Final Fight" hard-stop is triggered or a health anomaly persists.

### User Journey: The "Guardian's Cycle"

1. **The Pre-Flight Check:** Wingman locks the "Sacred Space" timer until "Non-Negotiables" (meds, hydration, grooming) are verified.
2. **The Silent Sentinel (Sacred Space):** For 4 hours, the Watch and PC Consuls monitor "Throughput" and "Biometrics" locally. The world is silenced. B+0 works with "Total Certainty" that the vacuum is being held.
3. **The Tactical Pivot:** If the Consul detects a "Throughput Crash" or an "Emergency Override," it initiates the **"Gentle Knock"**—a multi-sensory fade-in (music -> dimming -> voice) that respects the mental load while demanding an exit to health/family protocols.
4. **The Soft Landing:** Instead of an abrupt cut, Wingman executes a configurable "Landing Routine"—capturing final voice notes, saving architectural context, and transitioning the user safely to the "Biological Reset."
5. **The Attention Window:** Post-flow, B+0 enters a designated window where Wingman presents the "Remains of the Day" (filtered messages/tasks) for rapid, batch execution.
6. **The Biological Reset:** The system enforces a hard-stop to prevent total exhaustion, ensuring B+0 returns to his family as a human, not a depleted machine.

---

## Success Metrics

### User Success Metrics: The "Line in the Sand"
- **The "Non-Negotiable" Score:** 100% adherence to health routines (meds, hydration) and family "Sacred Time" (Friday/Saturday). This is the absolute success baseline.
- **Landing Efficiency:** 5-15 minute "Soft Landing" execution time. The system successfully transitions from hyper-focus to rest without loss of work context.
- **The "Sunday Re-engagement" Baseline:** A self-reported metric confirming that by Sunday, the user has successfully reset and is ready for the new cycle without residual exhaustion.

### Business & Technical Objectives (MVP Focus)
- **Gatekeeper Integrity:** 100% successful block of non-emergencies.
- **The "Emergency Education" Loop:** Number of non-family emergencies successfully verified by the AI and subsequently used to "train/educate" the contact about Sacred Space boundaries.
- **Battery Resilience:** The Watch Consul must maintain at least 18 hours of life while in "High-Performance Monitoring" mode during Sacred Space blocks.
- **UI Fluidity (The "No-Jank" Rule):** 0ms UI lag on the Phone/PC during high-frequency sensor data ingestion (enforced via Hive Isolates).
- **Local-First Privacy:** 0 bytes of biometric telemetry or digital biomarkers ever touch a remote server.
