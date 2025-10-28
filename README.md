# 🌊 LiquidUI - Flutter Onboarding Demo

[![Made with Flutter](https://img.shields.io/badge/Made%20with-Flutter-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![Powered by Dart](https://img.shields.io/badge/Powered%20by-Dart-0175C2?logo=dart&logoColor=white)](https://dart.dev)
[![UI/UX Design](https://img.shields.io/badge/Design-Liquid%20Swipe-ff69b4)]()
[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://opensource.org/)

---

## 🧠 Overview

**LiquidUI** is a **stunning Flutter onboarding experience** that showcases the power of **liquid swipe animations** — featuring smooth, fluid page transitions with vibrant gradients and modern design principles.

This project serves as a **comprehensive learning resource** for developers exploring advanced Flutter animations, gesture handling, and creating engaging user onboarding flows.

---

## 🎬 Preview

<div align="center">
  
  ![LiquidUI Banner](screenshots/banner.png)
    
</div>

---

## ✨ Features

* 🌊 **Liquid Swipe Animation** — Smooth, fluid page transitions with gesture control
* 🎨 **5 Beautiful Screens** — Welcome, Features, Analytics, Security, and Get Started
* ✨ **Advanced Animations** — Fade, slide, and pulse effects for engaging UX
* 🎭 **Vibrant Gradients** — Eye-catching color schemes for each onboarding page
* 📍 **Page Indicators** — Clear navigation feedback with animated dots
* 📱 **Responsive Design** — Adapts seamlessly to different screen sizes
* 🔄 **Loop Support** — Continuous swiping for smooth navigation

---

## 📸 Screenshots

<div align="left">
  <table>
    <tr>
      <td><img src="screenshots/welcome.png" alt="Welcome Screen" width="200"/></td>
      <td><img src="screenshots/features.png" alt="Features Screen" width="200"/></td>
      <td><img src="screenshots/analytics.png" alt="Analytics Screen" width="200"/></td>
      <td><img src="screenshots/security.png" alt="Security Screen" width="200"/></td>
      <td><img src="screenshots/getstarted.png" alt="Get Started Screen" width="200"/></td>
    </tr>
  </table>
</div>

---

## 🎥 Demo Video

Watch the **LiquidUI Onboarding Experience** in action:
👉 [Watch the Demo Here](https://x.com/KishanP07684084/status/1946946799526195448)

---

## 🏗️ Tech Stack

| Technology | Description |
|------------|-------------|
| **Flutter** | Cross-platform framework for building beautiful apps |
| **Dart** | Core programming language powering Flutter apps |
| **liquid_swipe** | Package for fluid swipe animations |
| **AnimationController** | Handles custom fade and slide transitions |
| **Material Design** | Modern design principles with gradient aesthetics |

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/liquid-ui-flutter.git
cd liquid-ui-flutter
```

### 2️⃣ Install Dependencies

```bash
flutter pub get
```

### 3️⃣ Run the App

```bash
flutter run
```

---

## 📦 Dependencies

Add these to your `pubspec.yaml`:

```yaml
dependencies:
  flutter:
    sdk: flutter
  liquid_swipe: ^3.1.0
```

---


### 🎨 Change Gradient Colors

Update colors in each page's `LinearGradient`:

```dart
gradient: LinearGradient(
  colors: [
    Color(0xFF667eea),  // Start color
    Color(0xFF764ba2),  // End color
  ],
)
```

### ⚡ Adjust Animation Speed

Modify animation duration in `initState()`:

```dart
_animationController = AnimationController(
  duration: Duration(milliseconds: 1000),  // Change timing here
  vsync: this,
);
```

### 🔧 Configure Swipe Behavior

Customize `LiquidSwipe` properties:

```dart
LiquidSwipe(
  enableLoop: true,              // Enable continuous swiping
  fullTransitionValue: 700,       // Swipe sensitivity (lower = more sensitive)
  enableSideReveal: true,         // Show next page preview
  waveType: WaveType.liquidReveal, // Animation style
)
```

---


## 💡 Learning Outcomes

By working with this project, you'll gain insights into:

* Building **engaging onboarding experiences** with Flutter
* Implementing **gesture-based navigation** with liquid swipe
* Creating **custom animations** with AnimationController
* Applying **modern gradient designs** and glassmorphism effects
* Structuring **multi-page UI flows** effectively
* Managing **animation states** across page transitions

---

## 🤝 Contributing

Contributions are encouraged! If you'd like to enhance the design or functionality:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add a new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 🧠 Flutter Development Environment

This project is built using Flutter. Below are the essential details and configuration requirements:

| Component | Details |
|-----------|---------|
| **Flutter Version** | 3.27.1+ (Stable Channel) |
| **Dart Version** | 3.6.0+ |
| **liquid_swipe** | ^3.1.0 |
| **Platforms Supported** | Android, iOS, Web, Windows, macOS, Linux |
| **Minimum SDK** | Android 21+ / iOS 12+ |

### 💻 Recommended IDE

* **Android Studio** 2023.3+ or **VS Code** with Flutter extensions
* **Flutter SDK** properly configured in PATH
* **Dart DevTools** for debugging

---

## 💬 Connect

For questions, suggestions, or collaborations:

📧 **[Email](pathakhom17@gmail.com)**  
🐦 **[Follow me on X (Twitter)](https://x.com/KishanP07684084)**  
💼 **[LinkedIn](https://www.linkedin.com/in/hom-bdr-pathak-01a3bb210)**  

---

## 🌟 Show Your Support

If this project inspired you or helped your Flutter learning journey:

* ⭐ **Star this repository**
* 🍴 **Fork it for your own projects**
* 📢 **Share it with the Flutter community**
* 🐛 **Report issues or suggest features**

---

<div align="center">

**Made with ❤️ and Flutter**

*Creating beautiful experiences, one swipe at a time* 🌊

</div>
