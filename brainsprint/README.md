# BrainSprint 🚀

A modern, cross-platform mobile application for interactive learning and quiz-based education. Built with Flutter, BrainSprint provides an engaging platform for users to test their knowledge, track progress, and enhance their learning experience.

![BrainSprint Banner](https://via.placeholder.com/1200x400/6C63FF/FFFFFF?text=BrainSprint+App)  
*Screenshot: BrainSprint in action*

## ✨ Features

- 🎯 **Smart Learning** - Adaptive quizzes that adjust to your learning pace
- 🔐 **Secure Authentication** - Firebase-powered signup and login with email verification
- 📊 **Performance Analytics** - Track progress with detailed statistics and insights
- 🎨 **Customizable UI** - Light/dark theme support with Material Design 3
- 🔄 **Offline Mode** - Continue learning without internet connectivity
- 📱 **Cross-Platform** - Works seamlessly on iOS and Android
- 📝 **Interactive Quizzes** - Various question types with instant feedback
- 🏆 **Achievements** - Earn badges and rewards for learning milestones

## 🛠 Tech Stack

| Category            | Technologies                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Framework**       | Flutter 3.x                                                                 |
| **Language**        | Dart 3.x                                                                    |
| **State Management**| Provider & Riverpod                                                         |
| **Navigation**      | Go Router                                                                   |
| **UI**              | Material Design 3, Responsive Layouts                                       |
| **Backend**         | Firebase (Authentication, Firestore, Cloud Functions)                       |
| **Local Storage**   | Shared Preferences, Hive                                                    |
| **Networking**      | Dio, Firebase APIs                                                          |
| **Testing**         | Mockito, Mocktail, Flutter Test                                            |
| **CI/CD**           | GitHub Actions                                                              |

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (3.0.0 or later)
- Dart SDK (3.0.0 or later)
- Android Studio / Xcode (for emulator/simulator)
- VS Code or Android Studio (recommended for development)
- Firebase account (for backend services)

### 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/brainsprint.git
   cd brainsprint
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   - Create a new Firebase project
   - Add Android and iOS apps to your Firebase project
   - Download the configuration files:
     - `google-services.json` for Android
     - `GoogleService-Info.plist` for iOS
   - Place them in the respective directories

4. **Run the app**
   ```bash
   flutter run
   ```

## 🧪 Testing

Run all tests:
```bash
flutter test
```

Run specific test file:
```bash
flutter test test/widget_test.dart
```

Generate test coverage report:
```bash
flutter test --coverage
```

## 📂 Project Structure

```
lib/
├── core/
│   ├── constants/
│   ├── errors/
│   └── utils/
├── data/
│   ├── models/
│   ├── repositories/
│   └── services/
├── presentation/
│   ├── screens/
│   ├── widgets/
│   └── providers/
└── main.dart
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

For any questions or feedback, please reach out to [your-email@example.com](mailto:your-email@example.com)

---

<div align="center">
  Made with ❤️ using Flutter
</div>

## Project Structure

```
lib/
├── core/               # Core utilities, constants, themes
├── models/             # Data models
├── providers/          # State management
├── routes/             # App navigation
├── screens/            # UI screens
│   ├── auth/           # Authentication screens
│   ├── dashboard/      # Main app screens
│   ├── quiz/           # Quiz-related screens
│   └── profile/        # User profile screens
├── services/           # Business logic and API calls
└── widgets/            # Reusable UI components
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Flutter Team for the amazing framework
- All contributors who helped shape this project

## Support

For support, email support@brainsprint.com or open an issue on GitHub.
