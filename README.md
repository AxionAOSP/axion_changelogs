# AxionOS Changelog

## Latest Version — 2.6 QUASIS

**Security Patch:** April 2026

---

### What's New in 2.6

- **Fixed and improved dynamic bar issues**
  - new lockscreen media layout
  - remove redundant notification events override
  - connected pipeline to default status bar chip 
     - call chip should now show aosp calls ui
     - recording now uses default ui
- **Introduce AxBurstEngine v2**
  - improved performance engine with new framework and features 
     - advanced thermal mitigation
     - ui first manager
     - BSP level boostings
       - performance improvements observed on mid range devices with modern kernel (5.X uclamp)
          - tests shows smoother scrolling on automated playstore | instagram app fling tests
          - smoother activity open transitions on settings app fragment tests
          - tolerable ui performance even when blur/wallpaper zoom enabled on mid range devices with 6 small : 2 big cluster type
- **Gamespace Improvements**
  - improved ui/ux
- **Edgelauncher improvements**
  - fixed reported issues
  - added default launch mode setting *(ct: Saikrishna1504)*
  - ui cleanup
- **Spoofing improvements**
  - fixed /data/adb exposure & regressions
- **AxPcMode Improvements**
  - layout fixes and ui improvements
- **AxionFx Improvements**
  - fixed effects not working on devices that use newer audio aidl like pixel 8/9/10 above *(ct: Localhorst04)*
  - added device profiles
- **Pulse Launcher improvements**
  - fixed private/work profile issues
  - added guide for private space access on all apps drawer
  - added long press to organize folders for smart drawer layout
- **Routines improvements**
  - fixed not working routines
  - added http/internet routines
- **Partial AxAnimationEngine introduction**
  - new activity slide material expressive animation
  - new lockscreen screen on wallpaper animation
  - new workspace unlock animation
- **New QS Tiles**
  - routines tiles
  - dns tiles
- **Qs Customizer Improvements**
  - improved qs customize button visuals *(ct: Saikrishna1504)*
- **New Theme Store Themes**
  - added udfps icons
  - added udfps themes
  - added waveform themes *(ct: Saikrishna1504)*
- **New Sandbox FileVault**
  - added file vault feature *(ct: Saikrishna1504)*
- **Weather Omnijaws improvements**
  - new weather icon types *(ct: Localhorst04)*
- **Pc Mode improvements**
  - added custom wallpaper support
- **Misc fixes**
  - fixed most issues reported in issue tracker
  - fixed performance issues on mid range soc like mtk dimensity 7200 pro
  - fixed lags when scrolling/flinging on unity games
  - fixed doze issues *(ct: bijoyv9)*
  - fixed app lock issues
  - fixed keybox issues caused by keybox comments 
