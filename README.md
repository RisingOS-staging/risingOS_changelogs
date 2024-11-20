# 🌌 RisingOS Version 6.0 STABLE (Ascension)

## 🌅 Introduction
A new beginning and a fresh opportunity to rise! This update brings **Android 15** with a touch of **RisingOS enhancements**. With *Ascension*, we've focused on thoughtfully adding customizations while prioritizing stability and performance.

---

## 🔒 Security Updates
- **Android Security Patches:** Up-to-date as of **November 2024**, ensuring robust protection.

---

## 💬 Highlights (RisingOS Exclusive Features)

### 🔧 **Bug Fixes**
#### AOSP Issues:
- Fixed laggy Quick Settings when playing media or handling multiple notifications (persisting issues since Android 12).

#### Beta Fixes (from the previous beta release):
- Launcher issues resolved.
- Corrected Quick Settings header picker layout.
- Updated default GMS spoofing values.
- Fixed:
  - Forced monochrome icons.
  - Boot animation styles.
  - Memory leaks from UDFPS animation (thanks to **neobuddy89**).
  - Stuck notifications when AOD image is enabled.
  - Various customization issues.
  - Vibrate icon display on the status bar.
  - Do Not Disturb delays.
  - Japanese dialog titles for notification/alarm sounds.
  - Auto-brightness icon UI bugs.
  - Vertical scrolling and A11-style side-scrolling issues.
  - Pulse media color filter glitches.

---

### 🌟 **Features**
#### **RisingUI 6.0**
- Redesigned **About Phone UI** (by **Sir Ayan**).
- New **Personalizations UI**.
- New **Settings Icons**
- Added **Settings Icon Styles**.

#### **Risa – Your AI Assistant**
- A brand-new assistant for tasks, visual impairments, and enhanced multitasking.

#### **Enhanced Multi-Window Support**
- Better Freeform and multi-window handling than AOSP.

#### **Revamped Pocket Mode**
- Prevents accidental inputs when the device is in your pocket.

#### **Pulse Gestures**
- Trigger Doze mode with gestures without waking the device.

#### **Compact Heads-Up Notifications**
- Displays notifications in a compact mode inspired by "island" notifications (more stable).

#### **Animated Volume Media Icon**
- A new animated wavelength icon in the volume panel when media is playing.

#### **Introducing Notification Peek Display**
- Inspired from motorola's bubble notification lockscreen style and android 15/16 minimalism beta feature

---

### 🎨 **UI Enhancements**
- **Display Engine Improvements:** Better selection UI for display engine modes.
- **Quick Settings Customizations:**
  - Added QS panel styles, UI styles, and tile layouts.
- **Lockscreen Widgets:**
  - Added lockscreen shortcuts toggle.
- **Clocks & Fonts:**
  - Added **Ntype82**, **Subway**, and **MotoMilkyStacked** clock fonts.
  - Introduced a minimalistic clock face inspired by **NothingOS 3.0**.
  - Added **Motorola**-styled clock face.
- **Wallpaper Blur & Dim Features:** New aesthetic customizations.

---

### 🎵 **Audio & Media**
- Added **media controls** to the media output dialog.
- Introduced **ambient music support** (Pixels only).
- **Music QS Tile:** Added for quick playback access.
- **Volume QS Tile:** Added for quick **buttonless** volume adjustment.

---

### 📊 **Performance Enhancements**
- Optimized feature integration to reduce resource usage.
- Reduced CPU usage during heavy workloads:
  - Prevented some observers from blocking main CPU threads.
  - Memory and CPU optimizations by limiting bitmap resources.
- Performance enhancements implemented from **ProtonAOSP** by **kdrag0n**.
- Improved memory management by improving memory killer performance

---

### 🔧 **Developer Options Exposure**
- Features moved to system settings without enabling developer mode:
  - **Android WebView Picker**
  - **Default USB Function Preference**
  - **Show Touches Option**

---

### 🛠️ **Additional Features**
- **Pin Auto-Confirmation:** Enabled for 4+ digit PINs.
- **Triluminous Pro Display Engine Mode:** New display mode inspired from Sony's Triluminous Pro Display.
- **New Wallpapers:** Featuring the **Rising x Wukong Edition** by Sir Ayan and the new **Nothing Phone 2A Plus Community Edition** wallpapers.
- **Added pixel features:** Exclusive pixel features such reverse charging, now playing, Quick tap

---

## 👴 Deprecated Features (Removed Features)

- **QS Widgets:**
  - Incompatible with Android 15 changes (Results to broken QS Customizer etc.)

---

## 🙌 All Features currently shipped with respective Authors and Contributors
Below is a detailed compilation of all features incorporated into the current release, accompanied by the acknowledgments of the original authors and contributors of the listed features.

**Disclaimer:** The risingOS team may have made partial modifications to these features. However, it is essential to note that we do not assert or will NEVER assert ownership to any of these features, nor do we claim any part of them as our own. All copyrights and credits belong to their respective authors and contributors.

Your understanding and appreciation for the creativity and efforts of the original contributors are highly valued. We extend our outmost gratitude and appreciation to all the people listed below for their contributions and efforts to the development of these features 🙏

---
## Cherry-picked features
- **LineageOS features and customizations:** LineageOS
- **Adaptive Playback:** Jyotiraditya, Stylogey
- **Ai Assistant Shortcut:** Credits to Mishaal Rahman
- **Always on Display schedule:** idoybh
- **App Lock:** jhonboy121, Pranav Vashi (Forward Port and fixes)
- **Brightness Slider Customizations:** Alberto97, Michael Bestas, Luca Stefani, Alexander Westphal, qjohn, maxwen, Pranav Vashi, idoybh, timjosten
- **Battery Bar:** cphelps76, Pranav Vashi (Fixes)
- **Battery Customizations:** althafvly, Pranav Vashi, Myself5, TheStrix, ezio84, 703joko, R15Hi, spezi77, StarkDroid, Dr Disagree
- **Colored Status Bar Icons:** Dil3mm4, spkal101, Pranav Vashi (Fixes and Improvements)
- **Depth Wallpaper:** siavash79
- **Disable Data Indicator:** varund7726
- **Edge Light:** jhonboy121, Stallix (Forward Port), Pranav Vashi (Fixes and Improvements)
- **Flashlight Strength Tile:** Anay Wadhera, Jake Weinstein, ralph950412, Dhina17
- **GameSpace:** Nauval Rizky
- **Hide ADB and developer:** someone5678
- **Hide Screen capture status from apps:** someone5678
- **Hide Power Menu on QS:** jhonboy121
- **Less Boring Headsup:** ezio84, Rushab Shah, Pranav Vashi
- **Music Ticker:** ezio84, Pranav Vashi (Forward Port)
- **Noisy Notifications:** ezio84
- **LMOFreeform Sidebar:** LibreMobileOS
- **Lockscreen Charging Info:** beanstown106
- **LockScreen Clocks:** Afterlife Project (703joko)
- **Monet Customizations:** idoybh, Pranav Vashi
- **Notification Count:** Steve Kondik, jhonboy121, Pranav Vashi (Fixes)
- **Omnijaws Weather Client:** Maxwen, Pranav Vashi
- **QuickSettings Header Image:** Idc/ancientOS
- **QuickSettings Styles and Customizations:** IacobIonut01, SamarV-121, Tim Zimmermann, cjh1249131356, timjosten, StarkDroid, Dr Disagree, elluzion, rdx420
- **Screen Off Animations:** Kshitij Gupta, Pranav Vashi (Forward Port),
- **Shape and Icon Pack Themes:** SagarMakhar, Pranav Vashi (Improvements), Dr Disagree (Iconify Icon Packs)
- **Status Bar Clock Customizations:** Luca Stefani, Hendrik Hagendorn, LuK1337, Michael W, Volodymyr Zhdanov, kxxt, bellegarde-c, Pranav Vashi
- **Status Bar Clock Chip:** StarkDroid
- **Status Bar Logo:** Pranav Vashi, Shevt, LorDClockaN, varund7726
- **Strict Standby Policy:** LibXZR, Adithya R
- **System Haptics:** Blaster4385, Pranav Vashi, someone5678
- **Smart 5G:** Adithya R
- **Smart Pixels:** Sergii Pylypenko, Anay Wadhera, Pranav Vashi, frap129
- **Screenshot Sound:** Ashwin R C
- **Sleep Mode:** SKULSHADY
- **Storage Access Framework bypass:** rdxzv
- **Swipe to Screenshot Gestures:** ghbhaha, jhenrique09
- **Per-app Volume:** cjybyjk
- **Pixel Framework:** jhenrique09, nivlafx, someone5678
- **Pulse Visualizer:** bigrushdog (Randall), Pranav Vashi (Forward Port)
- **QS Transparency Customization:** DotOS, spkal101, nift4, Pranav Vashi
- **UDFPS Animations:** SagarMakhar, Dhina17, AnnierinBliss, Pranav Vashi
- **UDFPS Icons:** Pranav Vashi
- **UI Styles:** eldainosor
- **Volume Styles:** Dr Disagree (iconify volume style packs).
---


