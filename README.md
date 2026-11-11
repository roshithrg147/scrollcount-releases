# ScrollCount Releases (Android)

Official download hub and installation guides for **ScrollCount** for Android.

[![Latest Release](https://img.shields.io/github/v/release/roshithrg147/scrollcount-releases?label=Latest%20Beta&color=blue)](https://github.com/roshithrg147/scrollcount-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android%208.0+-green.svg)](https://github.com/roshithrg147/scrollcount-releases)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20On--Device-success.svg)](https://github.com/roshithrg147/scrollcount-releases)

---

## 📥 Direct APK Download

👉 **[Download Latest Beta APK (v1.2.0-beta)](https://github.com/roshithrg147/scrollcount-releases/releases/download/v1.2.0-beta/app-release.apk)**

---

## 🌟 What is ScrollCount?

ScrollCount is a lightweight, distraction-free, privacy-first Android app designed to help you break short-form video doomscrolling loops. It runs a subtle, interactive floating badge that keeps real-time tally of your reels and shorts across:
- **YouTube Shorts** (`com.google.android.youtube`)
- **Instagram Reels** (`com.instagram.android`)
- **Facebook Reels** (`com.facebook.katana`)
- **TikTok** (`com.zhiliaoapp.musically`)
- **Snapchat Spotlight** (`com.snapchat.android`)
- **Reddit Watch / Video Player** (`com.reddit.frontpage`)

### ✨ Key Features
- **Mindful Floating Counter:** A minimalist, glowing pill badge resting at the edge of your screen that expands on tap to show detailed statistics and duration metrics.
- **⏳ 24-Hour Midnight Auto-Reset:** Automatically zeroes out the daily tally at `00:00:00` local midnight with live countdown timers.
- **⏱️ Lifetime Watch-Time Calculator:** Tracks cumulative time lost to short-form video algorithms.
- **🛡️ 100% Local Privacy & Zero Telemetry:** Runs strictly in local memory—no internet access permissions, no trackers, no ads, and no screen recordings.

---

## 📲 Step-by-Step Installation Guide

Because this is a beta release distributed outside the Google Play Store, Android requires a few one-time permission approvals:

### 1. Download & Install
1. Tap the direct APK link above to download `app-release.apk`.
2. When prompted *"For your security, your phone is not allowed to install unknown apps from this source"*, tap **Settings** and toggle **"Allow from this source"**.
3. Tap **Install**.

### 2. Google Play Protect Warning
If Android displays a prompt saying *"App blocked to protect your device"* or *"Unrecognised app"*:
- Tap **More details** ➔ **Install anyway**.
*(Note: Because this test APK utilizes Android's `AccessibilityService` API to detect swipe gestures and hasn't yet gone through Google Play's store review, Play Protect shows an automated warning).*

### 3. Unlock Restricted Settings (Android 13, 14 & 15)
Google restricts Accessibility permissions on sideloaded apps by default:
1. Open phone **Settings** ➔ **Apps** ➔ **ScrollCount**.
2. Tap the **three vertical dots (⋮)** in the top right corner.
3. Tap **"Allow restricted settings"** and authenticate with your fingerprint or PIN.

### 4. Enable Required Permissions
Open the **ScrollCount** app and grant:
- **Accessibility Service:** Toggle **ON** so ScrollCount can detect short-form video swipes.
- **Display Over Other Apps:** Toggle **ON** to enable the floating mindful badge.
- **Notifications:** Allow to receive daily limit milestone reminders.

### 5. Disable Battery Optimization (Important)
To ensure Android's background cleaner doesn't kill the counter:
- Go to phone **Settings** ➔ **Apps** ➔ **ScrollCount** ➔ **Battery**.
- Select **"Unrestricted"**.

---

## 💬 Beta Feedback
Found a bug or have an idea? Please reach out to the developer or submit feedback via our beta testing form.
