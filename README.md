# 📱 Track My Pantry

**Track My Pantry** is an iOS application designed to help users easily manage and track the contents of their pantry.  
This project was developed using **Swift** and **Xcode**, and demonstrates the use of `UIViewController`, `Storyboard` interfaces, and asset management.

---

## 🚀 Features

✅ User registration and authentication interface  
✅ Home page to visualize pantry contents  
✅ Simple UI to add, edit, and delete items  
✅ App icons and assets included  
✅ Unit tests and UI tests provided

---

## 📂 Project Structure

- `Tracciare_dispensa/` – Main app source files
  - `AppDelegate.swift` – Application lifecycle management
  - `Info.plist` – App configuration
  - `Assets.xcassets` – App icons and resources
  - `Base.lproj/Main.storyboard` – Main user interface
  - `Base.lproj/LaunchScreen.storyboard` – Launch screen UI
  - `FileController/` – Custom view controllers:
    - `HomePageViewController.swift`
    - `RegistrazioneViewController.swift`
    - `ViewController.swift`
- `Tracciare_dispensa.xcodeproj` – Xcode project file
- `Tracciare_dispensaTests/` – Unit test targets
- `Tracciare_dispensaUITests/` – UI test targets

---

## ⚙️ Requirements

- macOS with Xcode installed
- Swift 5
- iOS 13.0 or later

---

## 💡 Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/track-my-pantry.git
   ```

2. Open the project in Xcode:

   ```bash
   open Tracciare_dispensa.xcodeproj
   ```

3. Select your preferred simulator or connected device.

4. Build and run the project (⌘ + R).

---

## 🧪 Testing

To run unit and UI tests:

1. In Xcode, select the **Track My Pantry** scheme.
2. Press (⌘ + U) or select **Product > Test**.

---

## ✨ Possible Improvements

- Implement persistent storage (Core Data or SQLite) to save pantry data between app launches.
- Add notifications to remind users about expiring products.
- Enhance the user interface with more advanced layouts.
- Support user authentication with a backend service.
- Localize the app into multiple languages.

---

## 📬 Contact & Support

For questions, suggestions, or contributions, feel free to contact me:

📧 **[Insert your email address here]**

---

## 📄 License

This project is released under the [MIT License](LICENSE).
