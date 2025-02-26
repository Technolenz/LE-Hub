# 📌 LE Hub

**A Flutter-powered platform for discovering and organizing local events effortlessly.**

## 🚀 Features
- 🔍 **Event Discovery** – Find local events based on location, category, and preferences
- 📅 **Event Management** – Create, edit, and manage events seamlessly
- 🔔 **Reminders & Notifications** – Stay updated with event reminders
- 🗺️ **Interactive Map View** – View events on a map for easy navigation
- 🌙 **Dark Mode Support** – A clean, modern UI with light & dark themes

## 🛠️ Tech Stack
- **Flutter** – Frontend framework
- **Firebase** – Backend (Firestore, Auth, Storage, Cloud Functions)
- **Google Maps API** – Location-based services
- **Provider / Riverpod / Bloc** – State management

## 📂 Folder Structure
```
📂 lehub/
 ├── 📂 lib/  
 │   ├── 📂 core/            # Global utilities (theme, constants, services)  
 │   ├── 📂 models/          # Data models  
 │   ├── 📂 services/        # API & database logic  
 │   ├── 📂 views/           # Screens & widgets  
 │   ├── 📂 controllers/     # State management  
 │   ├── main.dart           # Entry point  
 ├── 📂 assets/              # Images, fonts, etc.  
 ├── 📂 test/                # Unit & widget tests  
 ├── pubspec.yaml            # Dependencies  
```

## 🏗️ Installation & Setup
1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/LE-Hub.git
   cd LE-Hub
   ```

2. **Install Dependencies**
   ```sh
   flutter pub get
   ```

3. **Set Up Firebase** (Optional)
   - Create a Firebase project
   - Add `google-services.json` (Android) & `GoogleService-Info.plist` (iOS)

4. **Run the App**
   ```sh
   flutter run
   ```

## 💡 Contributing
Pull requests are welcome! Feel free to open an issue for discussion.

## 📜 License
This project is licensed under the MIT License.

---

🔗 **Follow the project on Twitter/X: [@miclenzy](https://twitter.com/miclenzy)**


