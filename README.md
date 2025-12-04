# ⛽ appGasAlc: Fuel Price Calculator

[![GitHub Repository](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?style=flat&logo=github)](https://github.com/Patrick-Gonzaga/-alcohol-or-gasoline/)

This repository contains the source code for a simple mobile application named **appGasAlc**. Based on the name and initial setup, the app is intended to help users determine whether **Gasoline (Gas)** or **Ethanol (Alc)** is the more cost-effective fuel option.

---

## ✨ Features

* **Initial Setup:** A basic React Native application scaffolded with Expo.
* **Purpose:** Designed to be a fuel cost-efficiency calculator (Gas vs. Alcohol/Ethanol).
* **Cross-Platform:** Supports Android, iOS, and Web deployment via Expo.

---

## 🛠️ Technology Stack

The project is built using **React Native** and managed with **Expo**. It uses **TypeScript** for type safety.

* **Framework:** React Native
* **Environment:** Expo
* **Language:** TypeScript
* **Dependencies:** `react`, `expo`, `react-native`, `expo-status-bar`

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

Ensure you have **Node.js** and **npm/yarn** installed. For running the app, you'll need the **Expo Go** app on your device or an emulator/simulator.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Patrick-Gonzaga/-alcohol-or-gasoline/](https://github.com/Patrick-Gonzaga/-alcohol-or-gasoline/)
    cd appGasAlc
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

### Running the Application

You can start the development server using one of the following commands:

| Command | Description |
| :--- | :--- |
| `npm start` / `yarn start` | Starts the Expo development server. |
| `npm run android` / `yarn android` | Opens the app on an Android Emulator/Device. |
| `npm run ios` / `yarn ios` | Opens the app on an iOS Simulator/Device. |
| `npm run web` / `yarn web` | Opens the app in a web browser. |

Once the server is running (`npm start`), you can scan the QR code with the **Expo Go** app on your mobile device to view the application.

---

## 📂 File Structure Overview

| File | Description |
| :--- | :--- |
| `App.tsx` | The main component of the application. Currently shows a basic "Hello World" style text. |
| `app.json` | The Expo configuration file, defining app name (`appGasAlc`), icons, splash screens, and platform settings. |
| `package.json` | Contains project metadata, dependencies, and available scripts (like `start`, `android`, `ios`, `web`). |
| `index.ts` | The entry point for the Expo app, registering the root component. |
| `tsconfig.json` | TypeScript compiler configuration. |

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for features or improvements, please feel free to open an issue or submit a pull request.

---

## 📝 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
