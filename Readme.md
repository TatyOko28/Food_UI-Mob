# Deliveroo Food Ordering Application 🍔📲

**Platform**: iOS & Android (Cross-platform Mobile Application)  
**Technologies**: React Native, Expo Router, Zustand, Reanimated, Google API

This Deliveroo-inspired application allows users to browse restaurants, view menus, and place orders seamlessly. Featuring an elegant design, smooth animations, and integrated maps for delivery tracking, this app demonstrates the latest in mobile development with React Native.

---

## Features

- **Expo Router**: Streamlined navigation experience.
- **State Management with Zustand**: Simplified and efficient global state handling.
- **Reanimated**: Micro animations that enhance the user experience.
- **Google Maps API Integration**: Real-time maps for tracking orders.

---

## Project Structure

1. **Expo Router**: File-based routing for organized navigation.
2. **Zustand for State Management**: Efficient global state with Zustand.
3. **Smooth Micro Animations**: Enhances the app with fluid animations.
4. **Google API for Maps**: Interactive map integration for real-time tracking.

---
## Screenshots

<div style="display: flex; flex-direction: 'row';">
<img src="/photos/1.png" width=20%>
<img src="/photos/2.png" width=20%>
<img src="/photos/3.png" width=20%>
<img src="/photos/4.png" width=20%>
<img src="/photos/5.png" width=20%>
<img src="/photos/6.png" width=20%>
<img src="/photos/7.png" width=20%>
<img src="/photos/8.png" width=20%>
<img src="/photos/9.png" width=20%>
<img src="/photos/10.png" width=20%>
</div>

## Prerequisites

Before starting, make sure to have the following tools installed:
- [Node.js](https://nodejs.org/) version 14.x or above
- [Expo CLI](https://docs.expo.dev/get-started/installation/) installed globally
- A [GitHub](https://github.com/) account

## Installation

Clone the repository and install dependencies:
```bash
git clone https://github.com/username/AppleWalletClone.git
cd AppleWalletClone
npm install
```
Run the app with Expo:
```
expo start
```
Scan the QR code to test the app on your device.

## Deployment

### 1. Deploying to GitHub
Initialize your local repository:
bash
Copier le code
```
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/username/FoodOrderingApp.git  //modify this link
git push -u origin main
```

### 2. Install the latest EAS CLI
EAS CLI is the command-line app that you will use to interact with EAS services from your terminal. To install it, run the command:
```
npm install -g eas-cli
```

### 3. Log in to your Expo account
If you are already signed in to an Expo account using Expo CLI, you can skip the steps described in this section. If you are not, run the following command to log in:
```
eas login
```
You can read the official information of this process by clicking on this link https://docs.expo.dev/tutorial/eas/ios-production-build/ or continue reading the information below

### 4. Run a build
After you have confirmed that you have a Google Play Store or Apple App Store account and decided whether or not EAS CLI should handle app signing credentials, you can proceed with the following set of commands to build for the platform's store:
```
eas build --platform android
```
Alternatively, you can use --platform all option to build for Android and iOS at the same time:
```
eas build --platform all
```

### 5. Deploy the build
If you have made it to this step, congratulations! Depending on which path you chose, you now either have a build that is ready to upload to an app store, or you have a build that you can install directly on an Android device/iOS Simulator.




