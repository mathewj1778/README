<div align="center">

# 📘 FBLA Member App

**A mobile application for FBLA members to stay connected, informed, and organized.**

Built with [Expo](https://expo.dev) · React Native · File-based Routing

[![Expo](https://img.shields.io/badge/Expo-SDK-blue?logo=expo)](https://expo.dev)
[![React Native](https://img.shields.io/badge/React%20Native-mobile-61DAFB?logo=react)](https://reactnative.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Prerequisites](#-prerequisites)
- [Getting Started](#-getting-started)
- [Running the App](#-running-the-app)
- [Project Structure](#-project-structure)
- [Learn More](#-learn-more)
- [Contributing](#-contributing)

---

## 🏫 About

The **FBLA Member App** is a cross-platform mobile application designed to help Future Business Leaders of America (FBLA) members manage their chapter activities, stay up to date with events and news, and access important resources — all in one place.

This project was bootstrapped with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app) and targets both **iOS** and **Android**.

---

## ✨ Features

| Feature | Description |
|---|---|
| 👤 **Member Profiles** | View and manage personal information and chapter details |
| 📅 **Event Calendar** | Browse upcoming events and receive competition reminders |
| 📚 **Resources** | Quick access to key FBLA documents and study materials |
| 📰 **News Feed** | Stay informed with chapter announcements and updates |
| 📱 **Social Media** | Links to chapter social media channels for easy engagement |

---

## 📸 Screenshots

> _Screenshots coming soon._

---

## ✅ Prerequisites

Before you begin, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/) — `npm install -g expo-cli`
- [Expo Go](https://expo.dev/go) app on your iOS or Android device _(for physical device testing)_

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/mathewj1778/README.git
cd README
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npx expo start
```

Once the server is running, you can open the app in:

| Platform | How to open |
|---|---|
| 📱 Physical device | Scan the QR code with the **Expo Go** app |
| 🤖 Android emulator | Press `a` in the terminal (requires Android Studio) |
| 🍎 iOS simulator | Press `i` in the terminal (macOS + Xcode required) |
| 🌐 Web browser | Press `w` in the terminal |

> See the Expo docs for setting up an [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/) or [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/).

---

## 🏃 Running the App

### Development build

```bash
npx expo start
```

### Reset to a blank project

If you want to start fresh and move the starter code to **app-example**:

```bash
npm run reset-project
```

This creates a clean **app** directory for you to build from scratch.

---

## 🗂️ Project Structure

```
README/
├── app/                  # Main application screens (file-based routing)
│   ├── (tabs)/           # Tab-based navigation screens
│   └── _layout.tsx       # Root layout component
├── assets/               # Images, fonts, and other static assets
├── components/           # Reusable UI components
├── constants/            # App-wide constants (colors, config, etc.)
├── hooks/                # Custom React hooks
└── package.json
```

> This project uses [Expo Router's file-based routing](https://docs.expo.dev/router/introduction/). Each file in the `app/` directory automatically becomes a route.

---

## 📖 Learn More

- [Expo Documentation](https://docs.expo.dev/) — Fundamentals and advanced guides
- [Expo Router](https://docs.expo.dev/router/introduction/) — File-based navigation
- [React Native Docs](https://reactnative.dev/docs/getting-started) — Core components and APIs
- [FBLA Official Site](https://www.fbla.org/) — National organization resources
- [Learn Expo Tutorial](https://docs.expo.dev/tutorial/introduction/) — Step-by-step project tutorial

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
Made with ❤️ for FBLA members
</div>