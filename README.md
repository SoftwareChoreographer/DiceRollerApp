
# 🎲 DiceApp

DiceApp is a simple Android application that simulates the rolling of a dice. It displays a random result each time the user clicks a button, showing the corresponding dice image. The app is designed using Jetpack Compose to create a modern and responsive UI.

## 📑 Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [UI Overview](#ui-overview)
- [Dependencies](#dependencies)
- [License](#license)
- [Contributors](#contributors)

## 🚀 Introduction
DiceApp is a fun, easy-to-use app that lets users simulate a dice roll. It uses Jetpack Compose for the UI and random number generation to display a result between 1 and 6, showing the corresponding dice face as an image. This app is perfect for users who need a dice roll for board games, decision-making, or just for fun.

## 🌟 Features
- **🎲 Random Dice Roll:** The app generates a random number between 1 and 6 when the button is clicked.
- **🖼️ Dynamic UI:** Displays the corresponding dice face as an image based on the result.
- **💡 Modern Design:** The app is built with Jetpack Compose and follows modern Android development practices.
- **📱 Edge-to-Edge Display:** The app uses edge-to-edge support for a fullscreen experience.

## 📦 Installation
To install and run the DiceApp on your Android device, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/softwarchoreographer/dicerollerapp.git
   ```

2. **Open the Project:**
   Open the project in Android Studio.

3. **Build and Run:**
   Click on the "Run" button in Android Studio to build and launch the app on an emulator or physical device.

## 🖱️ Usage
Once the app is installed and running, you’ll see a dice face displayed in the center of the screen. To roll the dice:

1. Press the **Roll Dice** button.
2. The app will generate a random number between 1 and 6 and display the corresponding dice face.
3. You can keep pressing the button to roll again and get a new random result.

## 🖥️ UI Overview
The main UI of the app consists of:
- **🎲 Dice Image:** Shows the current dice result (from 1 to 6).
- **🔘 Roll Button:** A button that triggers the dice roll, generating a new random result.
- The UI is centered on the screen using Jetpack Compose's layout modifiers for a clean, modern design.

### 📸 Example UI:
![DiceApp Example](images/diceapp_preview.png)

## 📚 Dependencies
This project uses the following libraries:
- **Jetpack Compose**: For building the UI.
- **Material3**: For the button and text styling.
- **AndroidX**: For general Android framework support.

Make sure you have the following dependencies in your `build.gradle` file:

```gradle
dependencies {
    implementation 'androidx.compose.ui:ui:1.0.0'
    implementation 'androidx.compose.material3:material3:1.0.0'
    implementation 'androidx.activity:activity-compose:1.3.1'
}
```

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Contributors
- **SoftwareChoreographer** - Creator and Developer
- **Contributors** - Feel free to contribute via pull requests!

---

🎉 Thank you for using DiceApp! Have fun rolling the dice! 🎲
