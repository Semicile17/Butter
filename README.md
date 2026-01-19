
---

<h1 align="center">🧈 Butter – A Social Networking App</h1>

![Demo App](/mobile/assets/images/screenshot-for-readme.png)

**Butter** is a full-stack social networking mobile application built with **React Native**.
It focuses on smooth interactions, clean design, and modern mobile-first UX while running seamlessly on both Android and iOS.

---

## ✨ Project Overview

Butter is a personal project that replicates the core functionality of a modern social platform, including authentication, content creation, engagement, messaging, and user profiles — all backed by a scalable API and cloud infrastructure.

* 📱 Cross-platform (Android & iOS)
* ⚛️ Built entirely with JavaScript / TypeScript
* ☁️ Cloud-integrated backend
* 🔐 Secure authentication & API protection

---

## 🧈 Features

### 🔐 Authentication

* Google & Apple sign-in
* Secure session handling

### 🏠 Feed

* Create text and image posts
* Upload images from camera or gallery

### ❤️ Engagement

* Like and comment on posts
* Smooth modal interactions

### 🔔 Notifications

* Activity updates for likes and comments

### 💬 Messages

* One-to-one chat history
* Long-press message deletion

### 👤 Profile

* Editable user profile modal
* View personal posts and activity

### 🔎 Discover

* Search for trending content and users

### 🚪 Sign Out

* Secure logout with session cleanup

---

## 🧠 Tech Stack

### Frontend (Mobile)

* **React Native**
* **Expo**
* **Clerk** (authentication)

### Backend

* **Node.js**
* **Express.js**
* **MongoDB**
* **Cloudinary** (media storage)
* **Arcjet** (rate limiting & bot protection)

---

## 📁 Environment Variables

### ⚙️ Backend (`/backend`)

```bash
PORT=5001
NODE_ENV=development

CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
CLERK_SECRET_KEY=<your_clerk_secret_key>

MONGO_URI=<your_mongodb_connection_uri>

ARCJET_ENV=development
ARCJET_KEY=<your_arcjet_api_key>

CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
```

---

### ⚙️ Mobile (`/mobile`)

```bash
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
EXPO_PUBLIC_API_URL=<your_backend_api_url>
```

---

## ▶️ Running the Project Locally

### Backend

```bash
cd backend
npm install
npm run dev
```

### Mobile

```bash
cd mobile
npm install
npx expo start
```

---

## 🎨 Design Philosophy

Butter follows a **minimal, soft UI approach**:

* Rounded components
* Generous spacing
* Calm color palette
* Smooth transitions

The goal is to prioritize **readability and flow** over dense information layouts.

---

## 📌 Future Improvements

* Reposts / shares
* Bookmarks
* Polls
* Dark mode & theme customization
* Real-time typing indicators

---

## 🧈 About

Butter is a **personal project** built to explore modern mobile app architecture, scalable backend design, and real-world authentication and media handling patterns.

---


