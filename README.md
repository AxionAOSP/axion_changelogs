# 📱 AxionOS Changelog  

## 📅 Latest Version - **1.2**
- **March 2025 Security Update:**

### 🚀 What's New  

#### 🎨 UI/UX Enhancements  
- **Volume Panel Improvements:**
  - Enhanced volume slider swipe animation for a smoother experience
  - Optimized volume panel size and layout in portrait mode
  - Added an animated wave icon when media is playing
- **Quick Settings Enhancements:**
  - Improved landscape layout for better usability
- **Tablet UI Fixes:**
  - Resolved various layout issues for a more refined experience
- **Imporved Freeform:**
  - Reduced freeform window density

#### 🛠️ New Features  
- Added **Game Spoofing** option
- Added **Hide ADB and Developer Options**
- Added **Ignore Secure Window Flag** option
- Enabled **Application Downgrade Support**
- Added **Columbus Service** aka **Quick Tap**
- Added **Volume Steps**
- Added **Sound tile**
- Added **Data Switch tile**
- Added **ViperFx Support**
- Added **Increasing Ring feature**
- Added **Multi-sim phone ringtone**
- Added **Custom Vibration patterns**
- Added **Hide app list**
- Added **Lockscreen Weather**
- Added **Preferred Network QS tile**
- Added **Netflix Full HD spuff**

#### ⚡ System Enhancements  
- **Performance Mode:**
  - Introduced a new **Performance Mode** that optimizes the CPU scheduler (based on TKG/Liquorix/Zen kernel tunings) and governor for higher performance
  - Improved gaming performance by applying Unity CPU affinity tweaks to all games for better performance.
- **GameSpace Integration:**
  - When **GameSpace Performance Mode** is enabled, the system automatically enables the system performance mode while the game is active (if system performance mode is disabled)
- **CPU Sleep Optimizations:**
  - Limits CPU usage when the device is idle or the screen is off, without disrupting audio or media playback
- **Pixel Tensor Devices:**
  - Disabled early thermal throttling to allow faster charging at lower temperatures (still capped at **41°C+** for safety)
  - Implemented Smart charging mode with QS Tile
  - Boosted minimum GPU frequency when GameSpace performance mode is enabled
- **Minimize rendering overhead:**
  - Disabled thread renderer that increases rendering overhead on low-end devices
- **Fixed Triluminous Display contrast**
- **Improved hide adb/developer settings**
  - Now hides adb/developer options status to more apps e.g Gcash/banking apps
- **Improved hide app list feature**
  - Now works like zygisk-detach
- **Fixed Revanced MicroG Signature Spoofing**
- **Scheduling improvements**
- **Enabled Proactive kills for modern kernels**

## 🔄 Previous Releases  

### **1.1 - Hotfix** (February 19, 2025)  
#### 🎨 UI/UX Enhancements  
- Reverted Quick Settings to Material You color scheme.
- **Launcher**: Added Option to disable the search bar background for a cleaner look.
- Added **vibration haptic feedback** for:
    - Overscroll actions
    - Incoming and outgoing calls
    - Auto brightness button
- Reduced intensity of back gesture vibration for improved comfort.
- Added **Lockscreen Media Art Filter**.
- Added **Lockscreen Widgets** feature.
- Allow enabling/disabling of compact headsup notifications
- Improved the Network Traffic UI for separate upload and download modes.

#### ⚡ System Enhancements  
- Added support for **PlayIntegrity Bypass** and **Google Photos spoofing**.
- Optimized rendering performance.
- Significantly improved app launch speeds.
- Enhanced memory management.
- Optimized task scheduler performance.
- Reduced notifications images resource usage.
- Disabled Play Services OTA checks.

#### 🛠️ Bug Fixes  
- Fixed **power button delay**.
- Resolved **random reboots** caused by a fix for aggressive freezer kills.

### **1.1** (February 11, 2025)  
#### 🎨 UI/UX Enhancements  
- Fixed lockscreen lock icon color for better visibility.
- Removed media focus restrictions for an improved audio experience.
- Reduced UDFPS animation size and enhanced scanning animation for a better visual experience.

#### ⚡ Performance Boost  
- Introduced **SystemUIBoostFramework** for a more responsive Quick Settings expansion.
- System-wide performance optimizations for a faster and more efficient experience.

#### 🛠️ Bug Fixes  
- Fixed an issue where Hide NavBar feature leaves the navigation bar hidden when switching from gestural to 3 button navigation.
- Resolved a launcher crash when pressing the **Lens** button.
- Fixed a potential **SystemUI** crash when toggling between light and dark themes.
- Fixed delay when performing three finger screenshot action.
- Fixed notification shelf color after light/dark theme toggle.


### **1.0** (February 8, 2025)  
✅ **Initial Release** – Welcome to AxionOS!

---
