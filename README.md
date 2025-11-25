# AxionOS Changelog

## Latest Version — **2.2.1 Stable**
**Security Patch:** November 2025

---

### What's New in 2.2.1 Stable

#### Features & Additions
- Suppress notifications sound/vibration if screen on by ezio84
- Added ability to ship IMS overrides (Enable VoXX features) by vvb2060
- Added support to directly fetch latest beta PIF from google
- Translations updates (automated from google translate)
- New Updater material expressive redesign (credits to nivlafx for fixing)
- New gamespace call overlay feature - answer calls without leaving the game
- Added touch boost support to gamespace (device-specific)

---

#### Fixes & Improvements
- Prevented app memory leaks (e.g facebook mem leaks) that makes the system unstable 
- Fixed QQS flicker when expanding qs after collapsing the panel from non-first tile page
- Fixed brightness slider animation for always show mode
- Fixed flashlight tile inconsistencies 
- Fixed mistouch prevention not working on doze
- Fixed media art feature issues
- Fixed clock and doze icon shelf ui alignments
- Fixed disabled QS on keyguard vulnerability when dozing/pulsing
- Fixed gamespace inconsistencies and bypass charging issue where device bypass persist even after leaving the game
- Fixed flashbang when unlocking via bouncer/fingerprint
- Fixed launcher issues
    - fixed jank when going to all apps section
    - fixed all apps icon size on higher grid sizes and tablets
    - fixed sorting issues when cloned profile is active
    - fixed folder alignment when labels are hidden
    - fixed black screen when performing back gesture to homescreen 
