# 🚀 MyACS – Indian Oil Corporation Ltd.

**MyACS** is a cross-platform Flutter application developed for **Indian Oil Corporation Ltd.** to streamline regularizations, attendance tracking, and internal communications. Built with modern design principles, it supports Android and Web platforms using Flutter and Android Studio.

---

## 📦 Prerequisites

Make sure the following tools are installed before proceeding:

- ✅ [Flutter SDK](https://flutter.dev/docs/get-started/install)
- ✅ [Android Studio](https://developer.android.com/studio)
- ✅ Git (optional, for version control)
- ✅ Chrome browser (for web support)

---

## 🧰 Setup Instructions

### 1. 💻 Install Android Studio

1. Download from [https://developer.android.com/studio](https://developer.android.com/studio)
2. Install with default options.
3. Add **Flutter** and **Dart** plugins:
   - Open Android Studio
   - Go to `Preferences → Plugins`
   - Search and install `Flutter` (Dart is installed automatically)

---

### 2. 🧩 Install Flutter SDK

1. Download Flutter from [Flutter Install Page](https://flutter.dev/docs/get-started/install)
2. Extract and place it somewhere (e.g. `C:\src\flutter` or `/usr/local/flutter`)
3. Add Flutter to your PATH:
   - Windows: Add `flutter/bin` to Environment Variables
   - macOS/Linux:
     ```bash
     export PATH="$PATH:/path-to-flutter/bin"
     ```

4. Run this to verify installation:
   ```bash
   flutter doctor
3. 📂 Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-org/myacs.git
cd myacs
▶️ Run the App
📱 Android
Open the project in Android Studio (Open → myacs folder).

Let it sync all dependencies.

Run a physical device or emulator.

Press Run or use the terminal:

bash
Copy
Edit
flutter run
🌐 Web (Chrome)
Enable web support if not done:

bash
Copy
Edit
flutter config --enable-web
Launch in Chrome:

bash
Copy
Edit
flutter run -d chrome
📁 Project Structure
bash
Copy
Edit
lib/
├── generated/                    # Auto-generated files
├── pages/
│   └── auth/                     # Screens for user, team, and history management
│       ├── approve_regularizations_page.dart
│       ├── global_member_profile_page.dart
│       ├── history_page.dart
│       ├── home_page.dart
│       ├── main_page.dart
│       ├── my_regularizations_page.dart
│       ├── profile_page.dart
│       └── team_member_profile_page.dart
├── providers/                    # App state (e.g. attendance, locale)
│   ├── attendance_provider.dart
│   └── locale_provider.dart
├── widgets/                      # Reusable components
│   ├── chatbot_page.dart
│   ├── nav_bar.dart
│   ├── profile_header.dart
│   ├── recent_activity_list.dart
│   └── stats_grid.dart
├── main.dart                     # App entry point
└── theme_provider.dart           # Theme logic and settings


⚠️ Some unused/legacy files (like .oldchatbot_page.dart) might need cleanup.

🛠 Common Commands
bash
Copy
Edit
flutter pub get         # Install dependencies
flutter clean           # Clean build files
flutter doctor          # Check setup status
flutter build apk       # Build Android release APK
flutter build web       # Build Web version
👨‍💻 Contributing
We welcome internal contributions. Follow the steps below:

Fork the repo

Create a new branch:

bash
Copy
Edit
git checkout -b feature-name
Commit and push:

bash
Copy
Edit
git commit -m "Added feature"
git push origin feature-name
Create a pull request on GitHub

📝 License
This project is proprietary and developed for internal use by Indian Oil Corporation Ltd. All rights reserved.
