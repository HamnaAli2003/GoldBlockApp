# GoldBlock 💳

GoldBlock is a modern **Android banking application** built with **React Native and TypeScript**, with **Firebase** powering the backend services.

The app provides users with a digital banking experience where they can manage their accounts, perform banking operations, and create/manage **virtual cards** directly from the application.

## 📱 Overview

GoldBlock was developed to provide a simple and modern mobile banking experience with a focus on:

* Digital banking
* Virtual card creation and management
* Secure user authentication
* Real-time backend services
* Clean and responsive mobile UI

## ✨ Features

* 🔐 **User Authentication**

  * Secure sign-up and login
  * Firebase Authentication integration

* 💳 **Virtual Cards**

  * Create virtual cards
  * View and manage virtual card information
  * Digital card management from within the app

* 🏦 **Banking Dashboard**

  * View account information
  * Access banking features from a centralized dashboard

* ⚡ **Real-Time Data**

  * Firebase-powered backend
  * Real-time data synchronization

* 📱 **Android Application**

  * Built specifically for the Android platform
  * Responsive React Native interface

## 🛠️ Tech Stack

| Technology                    | Purpose                           |
| ----------------------------- | --------------------------------- |
| React Native                  | Mobile application development    |
| TypeScript                    | Type-safe application development |
| Firebase                      | Backend and cloud services        |
| Firebase Authentication       | User authentication               |
| Firebase Database / Firestore | Data storage and synchronization  |
| Android                       | Target platform                   |

## 🏗️ Architecture

The application follows a component-based React Native architecture.

```text
GoldBlock
│
├── React Native
│   ├── Screens
│   ├── Components
│   ├── Navigation
│   └── Business Logic
│
├── TypeScript
│   └── Type-safe application code
│
└── Firebase
    ├── Authentication
    ├── Database / Firestore
    └── Backend Services
```

## 📸 Screenshots

> Add screenshots of the application here to showcase the UI.

### Login

![Login Screen](./screenshots/login.png)

### Dashboard

![Dashboard](./screenshots/dashboard.png)

### Virtual Cards

![Virtual Cards](./screenshots/virtual-cards.png)

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js
* React Native development environment
* Android Studio
* Android SDK
* Java / JDK
* Firebase project

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/goldblock.git
```

Navigate to the project:

```bash
cd goldblock
```

Install dependencies:

```bash
npm install
```

### Firebase Configuration

Create/configure your Firebase project and connect it to the Android application.

Make sure your Firebase configuration files and environment variables are set up correctly before running the application.

> **Important:** Never commit private API keys, service credentials, or other sensitive Firebase configuration to a public repository.

### Run the Android App

Start Metro:

```bash
npm start
```

Then run the Android application:

```bash
npx react-native run-android
```

## 🔒 Security

GoldBlock uses Firebase services for authentication and backend functionality.

For production deployments, sensitive credentials and configuration should be managed through secure environment/configuration mechanisms and appropriate Firebase security rules.

## 🎯 Project Purpose

GoldBlock was created as a **mobile banking application project** to demonstrate practical experience with:

* React Native mobile development
* TypeScript
* Firebase backend integration
* Authentication
* Financial application UI/UX
* Virtual card management
* Android application development

## 📌 Project Status

**Active Development**

Additional banking features and improvements may be added over time.

## 👨‍💻 Developer

Developed using **React Native, TypeScript, and Firebase**.

---

⭐ If you find this project interesting, feel free to explore the repository and the implementation.
