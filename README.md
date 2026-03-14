# F1 107 Percent Performance Tracker (2026 Edition)

A lightweight, mobile-first utility for Formula 1 fans to calculate the 107 percent qualifying cut-off time in real-time during Q1 sessions.

### [Open the Web App](https://kanrog.github.io/F1-107-calc)

## What is the 107 Percent Rule?
The 107 Percent Rule is a sporting regulation (Article 35.1) designed to ensure that all cars on the grid are fast enough to compete safely. It acts as a performance gatekeeper to prevent significantly slower cars from interfering with the leaders during a race.

**The Logic:**
* During Q1 (the first phase of qualifying), any driver who fails to set a lap time within 107 percent of the fastest lap of that session is technically disqualified from the race.
* Calculation: The fastest time is multiplied by 1.07 to determine the cut-off.
* Exceptions: If the track is declared Wet by the Race Director, the rule is waived. Stewards may also grant permission to race if a driver demonstrated competitive pace in Free Practice sessions (FP1-FP3) but was prevented from setting a representative time in Q1 due to mechanical failure or force majeure.

## Why is this relevant in 2026?
With the 2026 Technical Regulation Overhaul, the 107 percent rule has returned to prominence. The shift to a 50/50 power split between internal combustion and electrical energy, combined with the introduction of active aerodynamics, has created a wider performance delta between the front-runners and those still optimizing the new power units.

* New Manufacturers: With the entry of Audi and the expanded presence of Cadillac, the focus on the pace of the back of the grid is higher than in previous seasons.
* Energy Management: The complexities of the 2026 "Override" and "Recharge" modes mean that a single mistake in energy deployment can lead to a lap time that falls dangerously close to the 107 percent threshold.

## Features
* Real-time Calculation: Input the current fastest Q1 time to see the cut-off time immediately.
* Offset View: Displays the exact time delta a driver can be off the pace before facing disqualification.
* Session History: Automatically saves the last five calculations to the device via LocalStorage for session tracking.
* Mobile-First Design: Optimized for use on mobile devices at the track or while watching a live broadcast.

## Installation as a Web App
This tool is a Progressive Web App (PWA) and can be saved directly to a smartphone home screen:
1. Open the site in a mobile browser.
2. Select the Share menu (iOS) or the Options menu (Android).
3. Select Add to Home Screen.