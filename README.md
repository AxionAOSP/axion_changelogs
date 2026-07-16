# AxionOS Changelog

## Latest Version — 2.8 ONEIRA FINAL

**Security Patch:** July 2026

**Notice** 
- some features were dropped for stability and will be re-added till we figure out how to do the feature correctly

**Dropped features**
- Folder styles
- Folder Enlarge/Shrink
---

### What's New in 2.8
- **Introducing AxAnimationEngine**
  - new system animations
  - new activity/page transitions
  - new launcher animations
  - fixed and improved on/unlock animations
- **Reworked Performance Framework**
  - a more stable framework compared to previous performance framework
   - improved performance over baseline stock AOSP 
     - improved entry-level device performance for devices like OnePlus Nord N30 5G
     - better ui performance even with blur enabled and heavy rendering
  - upgraded jemalloc to 5.3.1
  - enforced vulkan and added optional fix for devices with media tinting issues
  - jpeg-turbo performance enhancements
  - cheaper blur with better quality (can be rendered at max of 175f blur radius on snapdragon 695 with minimal hiccups)
- **QuickSettings Reworked**
  - new quicksettings user interface made more customizable
- **Reworked Launcher**
  - fixed app drawer issues
  - improved universal search
  - added granular grid/home/drawer customizations
  - new recents ui
- **Screen Record**
  - added granular fps control
  - fixed dropdown item alignment
- **Ram plus**
  - added swap extension feature
- **New AxKernelManager**
  - a more granular builtin kernel manager - devs can now add more tunables
- **Fixed issues**
  - fixed smart pixels showing in screenshot issue
  - fixed hide gesture pill extra space issue
  - fixed essential notifications footer issue
  - fixed video flicker when expanding shade over
  - fixed stacked power menu issue
