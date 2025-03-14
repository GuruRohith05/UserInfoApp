# 📱 UserInfoApp

UserInfoApp is a **React Native application** that fetches and displays user information from the **Random Data API**. It supports navigation between multiple users and provides a seamless user experience.

## 🌟 Features
- 📡 **Fetches Random User Data** – Retrieves user details from the Random Data API.
- 🖼️ **Displays User Profiles** – Shows user name, email, avatar, and other details.
- 🔄 **Smooth Navigation** – Uses **React Navigation** for navigating between screens.
- 📱 **Compatible with Android & iOS** – Works on both platforms.
- ⚡ **Fast & Responsive UI** – Optimized performance with React Native.

---

## 🚀 Getting Started

Follow these steps to **set up and run the project locally**.

### **1️⃣ Prerequisites**
Before setting up the project, make sure you have the following installed:

✅ **Node.js** (Latest LTS version) → [Download Here](https://nodejs.org/)  
✅ **React Native CLI** (or **Expo CLI** if using Expo)  
✅ **Android Studio** (for emulator) OR a physical Android device  
✅ **Java JDK** (Required for Android development)  

To check if everything is installed correctly, run:
```sh
node -v   # Check Node.js version
npm -v    # Check npm version
java -version  # Check Java version
adb devices   # Check if the Android device/emulator is connected
```

---

### **2️⃣ Clone the Repository**
First, clone the repository and navigate into the project folder:

```sh
git clone https://github.com/yourusername/UserInfoApp.git
cd UserInfoApp
```

---

### **3️⃣ Install Dependencies**
Run the following command to install all required dependencies:

```sh
npm install
```

---

### **4️⃣ Start Metro Bundler**
Metro Bundler is a JavaScript bundler for React Native. Start it using:

```sh
npx react-native start
```

If you face issues, try resetting the cache:
```sh
npx react-native start --reset-cache
```

---

### **5️⃣ Run the Application**
#### ✅ **On Android Emulator or Physical Device**
Make sure an **Android emulator** is running or a **physical device** is connected via USB.

Then, run:
```sh
npx react-native run-android
```

If your emulator/device is not detected, check with:
```sh
adb devices
```

#### 🍎 **On iOS Simulator (Mac Only)**
For iOS, use the following command:
```sh
npx react-native run-ios
```
> Note: You need **Xcode** installed on Mac to run the iOS version.

---

## 🛠️ Troubleshooting

### **1️⃣ "adb: device not found" error**
If you get an error like:
```
adb.exe: device 'emulator-5554' not found
```
Try restarting ADB:
```sh
adb kill-server
adb start-server
adb devices
```

### **2️⃣ Emulator crashes or doesn’t launch**
- Make sure your **Android Virtual Device (AVD)** is running.
- Open **Android Studio** → Go to **Device Manager** → Start the emulator manually.
- Try running the app again.

### **3️⃣ Stuck on "Metro Bundler"**
If Metro is stuck or slow:
```sh
npx react-native start --reset-cache
```

---

## 📂 Project Structure

```
UserInfoApp/
│-- android/                # Android-specific code
│-- ios/                    # iOS-specific code
│-- src/                    # Main app source code
│   ├── components/         # Reusable UI components
│   ├── screens/            # Screen components
│   ├── navigation/         # React Navigation setup
│   ├── api/                # API calls and services
│   ├── styles/             # Stylesheets
│   ├── App.js              # Main app entry file
│-- assets/                 # Images, icons, etc.
│-- package.json            # Project dependencies
│-- README.md               # Project documentation (this file)
```

---

## 📜 License
This project is open-source and available under the **MIT License**.

