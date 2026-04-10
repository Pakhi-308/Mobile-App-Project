# Advanced Android Implementation: UI & Logic Integration

## 📌 Project Overview
This repository contains a mobile application developed for the **Mobile Application Development (B21+E14)** course. The primary objective of this project is to demonstrate a mastery of the Android Activity Lifecycle, XML-based UI design, and Java backend integration.

The application serves as a [Functional Calculator], providing a seamless user experience through intuitive design and robust error handling.

---

## 👨‍💻 Developer Information
* **Name:** Pakhi Shukla
* **Registration Number:** 23BCE10847
* **Course:** B.Tech Computer Science and Engineering (CSE)
* **Institution:** VIT Bhopal University

---

## 🚀 Technical Features & Implementation
This project explores several core concepts of Android development:

### 1. User Interface (XML)
* **Layout Management:** Utilized `ConstraintLayout` and `LinearLayout` to ensure the UI is responsive across different screen sizes.
* **Material Design:** Integrated Material Components for a modern look and feel, including custom button styles and input fields.
* **Resource Separation:** All strings, colors, and dimensions are stored in `res/values` to follow best practices for scalability and localization.

### 2. Functional Logic (Java)
* **View Binding:** Established a bridge between XML layouts and Java code using efficient view referencing.
* **Event Handling:** Implemented `View.OnClickListener` interfaces to handle user interactions in real-time.
* **State Management:** Managed data flow within the application to ensure accurate results during runtime.

### 3. Error Handling
* Built-in validation to prevent application crashes (ANR) caused by empty inputs or invalid data types.

---

## 🛠️ Technology Stack
* **IDE:** Android Studio (Bumblebee or higher)
* **Language:** Java
* **UI Framework:** Android XML
* **Build Tool:** Gradle (Groovy/KTS)
* **Min SDK:** API 21+

---

## ⚙️ How to Setup and Run
1. **Clone/Download:** Clone this repository or download the source code as a ZIP file.
2. **Import:** Open Android Studio, select `File > Open`, and navigate to the project directory.
3. **Gradle Sync:** Allow Android Studio to download necessary dependencies and sync the Gradle files.
4. **Deployment:** Build the APK via `Build > Build APK(s)` or run directly on an emulator/physical device.

---

## 📁 Project Architecture
```text
app/
 ├── manifests/
 │    └── AndroidManifest.xml  # App configuration and permissions
 ├── java/
 │    └── com.pakhi.app/       # Main Logic & Activity classes
 └── res/
      ├── layout/              # XML UI Definitions
      ├── values/              # Strings, Colors, and Themes
      └── drawable/            # App Icons and Graphics
