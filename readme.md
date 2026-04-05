![Native Wallet Banner](/screenshots/banner.png)

# Native Wallet 💰📱

A modern **Expense Tracking Mobile App** built using **Expo React Native**, featuring secure authentication, fast API performance, and a clean UI.

Track income, monitor expenses, and manage finances seamlessly with a minimal and intuitive experience.

---

## ✨ Features

- 🔐 Secure authentication with Clerk
- 📊 Track income & expenses
- ⚡ Fast backend with Neon Postgres
- 🛡️ Rate limiting using Redis middleware
- 🌐 Hosted API on Render
- 📱 Cross-platform mobile app (Android)
- 🎨 Clean & modern UI
- 🔄 Real-time data sync

---

## 📸 Screenshots

| Sign-in Screen                 | Sign-up Screen                 | Home Screen                 |
| ------------------------------ | ------------------------------ | --------------------------- |
| ![Sign-in](/screenshots/1.jpg) | ![Sign-up](/screenshots/2.jpg) | ![Home](/screenshots/3.jpg) |

| Add Transaction Screen     | Recent Transactions Screen    |
| -------------------------- | ----------------------------- |
| ![Add](/screenshots/4.jpg) | ![Recent](/screenshots/5.jpg) |

---

## 📦 APK Download

👉 **Download Latest APK**

[Download Android APK](https://expo.dev/accounts/mrudul_gauba/projects/Mobile/builds/be149ceb-b50a-4318-985d-6033c2af6ce5)

> Install on Android device and allow unknown sources if prompted.

---

## 🧰 Tech Stack

### Mobile App

- Expo React Native
- Expo Router
- Clerk Authentication
- TypeScript

### Backend API

- Node.js
- Express.js
- Neon PostgreSQL
- Redis (rate limiting middleware)
- Hosted on Render

---

## 📁 Project Structure

```
native-wallet/
│
├── backend/        # API server
│   ├── src/
│   ├── middleware/
│   ├── routes/
│   └── db/
│
├── mobile/         # Expo React Native app
│   ├── app/
│   ├── components/
│   └── assets/
│
└── README.md
```

---

## ⚙️ Environment Variables

### Backend (.env)

```
DATABASE_URL=
REDIS_URL=
CLERK_SECRET_KEY=
PORT=
```

---

### Mobile (.env)

```
EXPO_PUBLIC_API_URL=
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=
```

---

## 🚀 Running Locally

### 1. Clone Repository

```
https://github.com/mrudul-gauba/Native-Wallet.git
cd native-wallet
```

---

### 2. Backend Setup

```
cd backend
npm install
npm run dev
```

---

### 3. Mobile App Setup

```
cd mobile
npm install
npx expo start
```

Run on:

- Android emulator
- Expo Go
- Physical device

---

## 🌍 Deployment

| Service        | Platform        |
| -------------- | --------------- |
| Backend API    | Render          |
| Database       | Neon PostgreSQL |
| Authentication | Clerk           |
| Mobile App     | Expo            |

---

## 🔮 Future Improvements

- Budget tracking
- Charts & analytics improvements
- Recurring transactions
- Dark mode toggle
- Export transactions (PDF/CSV)

---

## 👨‍💻 Author

**Mrudul Gauba**

If you like this project, consider giving it a ⭐ on GitHub!

---

## 📜 License

This project is licensed under the MIT License.
