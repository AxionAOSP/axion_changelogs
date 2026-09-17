# AxionOS Changelog

## Latest Version — 2.8 ONEIRA FINAL

**Security Patch:** September 2026

**Notice** 
- some features were dropped for stability and will be re-added till we figure out how to do the feature correctly

**Dropped features**
- Folder styles
---

### What's New in 2.8
- **Introducing AxAnimationEngine**
  - new system animations
  - new activity/page transitions
  - new launcher animations
  - fixed and improved on/unlock animations
- **Reworked Performance Framework**
  - introducing AxDragonite: a more stable framework compared to previous performance framework
  - new app optimization feature
  - upgraded jemalloc to 5.3.1
  - enforced vulkan and added optional fix for devices with media tinting issues
    - devices affected with vulkan tint can now run vulkan without issues as long as maintainer enables to workaround prop
  - jpeg-turbo performance enhancements
  - performance optimized high quality blur (can be rendered at max of 175f blur radius on snapdragon 695 with minimal hiccups)
- **QuickSettings Reworked**
  - new quicksettings user interface made more customizable
  - new media player look
- **Introducing AxDiagnostics**
  - Overall diagnostics in one place ( Battery , gpu , cpu , thermals ,storage ).
  - Real-time cpu/gpu stats overlay.
  - Real-time battery stats via notification service.
- **Reworked Launcher**
  - fixed app drawer issues
  - improved universal search
  - added granular grid/home/drawer customizations
  - new recents ui
  - added shake to auto arrange and multi-select edit mode (credits: Saikrishna1504)
  - added options to disable adaptive icons when using 3rd party icons (removes the white icon wrapper)
  - flexible folder resize feature (credits: Localhorst04 & Saikrishna1504)
  - search bar history toggle (credits: Kill3rEz)
  - misc fixed issues (credits: Saikrishna1504 & Zarathos30)
- **Screen Record**
  - added granular fps control
  - fixed dropdown item alignment
- **Ram plus**
  - added swap extension feature
- **New AxKernelManager**
  - a more granular builtin kernel manager - devs can now add more tunables
  - works with libperfmgr (boosters)
- **Dual apps support**
  - support for app cloning - improved app cloning feature that doesnt create duplicate system apps (aosp bug)
- **Extended D2TS feature**
  - now has various options: disabled, status bar/lockscreen only, both
- **AxionFX**
  - various fixes and optimizations (credits: joshuah345 & Saikrishna1504)
- **AxQuicklook**
  - fix smartspacer issues (credits: Saikrishna1504)
- **GameSpace**
  - Introduce Music Player Controller
  - Introduce Custom Crosshair Overlay
  - Improved in-call overlay
  - Improved Memory boost tile
- **Added new lockscreen clock**
  - new Gooey clock
- **Fixed issues**
  - fixed smart pixels showing in screenshot issue
  - fixed hide gesture pill extra space issue
  - fixed essential notifications footer issue
  - fixed video flicker when expanding shade over
  - fixed stacked power menu issue
  - fixed media player issues
  - fixed pulse visualizer doze issue
