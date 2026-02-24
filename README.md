# 🛍️ Flutter Store App

A fully functional **e-commerce store application** built with Flutter. The app fetches real product data from an API, displays it with a polished UI, and handles loading states gracefully — mirroring real-world production app patterns.

---

## 📱 Features

- 🌐 Fetch **real product data** from a live API
- ⏳ **Loading spinner** displayed while data is being fetched for a smooth user experience
- 🛒 Browse products with clean, structured UI
- 🎨 Rich icons using **Font Awesome** for a professional look
- 📦 Handles **async API calls** with proper loading state management
- 🚀 Works on both **Android and iOS**

---

## 🛠️ Tech Stack

| Technology | Details |
|---|---|
| Framework | Flutter |
| Language | Dart (null-safe) |
| HTTP Requests | http (^0.13.4) |
| Loading UI | modal_progress_hud_nsn (^0.5.1) |
| Icons | font_awesome_flutter (^9.2.0) + Cupertino Icons |
| UI | Material Design |
| Platforms | Android & iOS |

---

## 📂 Project Structure

```
store/
├── lib/
│   └── main.dart              # App entry point
├── android/                   # Android platform files
├── ios/                       # iOS platform files
├── pubspec.yaml               # Project dependencies
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (>=3.18.0)
- Dart SDK (>=2.15.1)
- Android Studio or Xcode (for running on a device/emulator)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bhavyansh1407/store.git
   cd store
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

---

## 📸 Screenshots

> _Add your app screenshots here once the app is running_

---

## 🏗️ How It Works

- On launch, the app makes an **HTTP GET request** to fetch product listings from an external API.
- While the data loads, a **modal progress indicator** (loading spinner) is displayed over the screen, preventing user interaction until data is ready — a pattern commonly used in production apps.
- Once loaded, products are rendered with their details and **Font Awesome icons** for visual elements like ratings, categories, and cart actions.

---

## 🎯 Skills Demonstrated

- Real-time **REST API integration** using the `http` package
- Professional **loading state management** with `modal_progress_hud_nsn`
- Rich UI design using **Font Awesome icons**
- Handling **asynchronous programming** with async/await in Dart
- Cross-platform mobile development with **Flutter & Dart**
- Building **production-like UX patterns** (loading states, error handling)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with Flutter 💙 | [bhavyansh1407](https://github.com/bhavyansh1407)