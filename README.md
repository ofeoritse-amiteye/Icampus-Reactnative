# 📱 iCampus – Student Companion App

> A mobile application built to enhance the daily experience of university students by providing essential campus tools in one place.

---

## 📖 Overview

iCampus is designed with usability and convenience in mind. The app helps students stay organized, navigate campus easily, and manage their academic lifestyle — all from a single app.

---

## 🚀 Features

| Feature | Description |
|---|---|
| 🗺️ Campus Map | Navigate around campus with an interactive map |
| 📅 Reading Timetable | Organize and track your personal study schedule |
| 🍽️ Meal Planner | Plan meals and manage daily nutrition on campus |
| 🔔 Reminders & Scheduling | Stay on top of tasks, classes, and deadlines |
| 👤 Student-Centered Design | Built specifically for the university student experience |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React Native (Expo) |
| Backend / Services | Firebase |
| Database | Firestore / Realtime Database |
| Authentication | Firebase Auth |
| State Management | Context API / Redux *(update as applicable)* |

---

## 📦 Installation

### Prerequisites
- Node.js ≥ 18
- npm or yarn
- Expo CLI (`npm install -g expo-cli`)

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/ofeoritse-amiteye/icampus.git
```

**2. Navigate into the project**
```bash
cd icampus
```

**3. Install dependencies**
```bash
npm install
```

**4. Start the development server**

With Expo:
```bash
npx expo start
```

Without Expo:
```bash
# Android
npm run android

# iOS
npm run ios
```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory and add your Firebase configuration:

```env
FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_auth_domain
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_STORAGE_BUCKET=your_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_sender_id
FIREBASE_APP_ID=your_app_id
```

> ⚠️ Never commit your `.env` file to version control. Make sure it's listed in `.gitignore`.

---

## 📸 Screenshots

> *Add screenshots of your app here — home screen, map view, timetable, meal planner, etc.*

---

## 🎯 Purpose

The goal of iCampus is to centralize key student utilities into a single mobile app, reducing the need for multiple disconnected tools and improving overall productivity on campus.

---

## 📈 Future Improvements

- [ ] Push notifications for reminders
- [ ] Integration with school portals
- [ ] Social features (student communities, messaging)
- [ ] Offline access for key features

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Amiteye Ofeoritse Favour** — Software Developer

- GitHub: [@ofeoritse-amiteye](https://github.com/ofeoritse-amiteye)
- Portfolio: *(https://ofeoritse-amiteye.vercel.app/)*
