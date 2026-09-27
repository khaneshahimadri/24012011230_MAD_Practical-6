# 📱 MAD Practical 6 — Android Application

<div align="center">

# 📲 Mobile Application Development — Practical 6

### Android Application Development using Kotlin

**Kotlin • XML • Android Studio • Material Design**

---

**Himadri Khanesha**  
**Enrollment No.: 24012011230**  
**Class: CE-I | Batch: I-2**

</div>

---

## 📌 About the Practical

This project is developed as part of the **Mobile Application Development (MAD)** practical coursework.

The practical focuses on implementing Android application development concepts using **Kotlin** and **XML** in Android Studio.

The application demonstrates how Android UI components, event handling, resources, activities, and application logic can be combined to create an interactive mobile application.

---

## 🎯 Aim

> To design and develop an interactive Android application using **Kotlin and XML** and understand the implementation of Android UI components, event handling, and application functionality.

---

# ✨ Key Features

| Feature | Description |
|---|---|
| 📱 **Android Application** | Native Android application developed in Kotlin |
| 🎨 **Modern UI** | User interface designed using XML |
| 👆 **User Interaction** | Interactive controls and event handling |
| 🧩 **Android Components** | Implementation of core Android components |
| ⚡ **Kotlin Logic** | Application functionality implemented using Kotlin |
| 🖼️ **Drawable Resources** | Custom icons and graphical resources |
| 📐 **Responsive Layout** | UI designed for Android screen sizes |
| 🔄 **Dynamic Behaviour** | UI responds to different user actions |

---

# 🛠️ Technology Stack

<div align="center">

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)

![XML](https://img.shields.io/badge/XML-UI-FF6600?style=for-the-badge)

![Gradle](https://img.shields.io/badge/Gradle-Build%20System-02303A?style=for-the-badge&logo=gradle&logoColor=white)

</div>

---

# 🧠 Concepts Implemented

This practical demonstrates several important Android development concepts:

### 🔹 Kotlin Programming

Kotlin is used to implement the application logic, event handling, and interaction between different Android components.

### 🔹 XML Layout Design

XML is used to design and organize the graphical user interface of the application.

### 🔹 Android Activities

Activities are responsible for displaying application screens and handling user interactions.

### 🔹 Event Handling

Click listeners and other event-handling mechanisms are used to respond to user actions.

Example:

```kotlin
button.setOnClickListener {
    // Perform required action
}
```

### 🔹 Android Resources

The application uses Android resource directories to manage:

- Layouts
- Drawables
- Icons
- Strings
- Colors
- Themes

---

# 📂 Project Structure

```text
24012011230_MAD_Practical-6/
│
├── 📁 app/
│   │
│   ├── 📁 src/
│   │   └── 📁 main/
│   │       │
│   │       ├── 📁 java/
│   │       │   └── com.example...
│   │       │       └── MainActivity.kt
│   │       │
│   │       ├── 📁 res/
│   │       │   │
│   │       │   ├── 📁 drawable/
│   │       │   ├── 📁 layout/
│   │       │   ├── 📁 mipmap/
│   │       │   └── 📁 values/
│   │       │
│   │       └── AndroidManifest.xml
│   │
│   └── build.gradle.kts
│
├── 📁 gradle/
├── .gitignore
├── build.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
├── settings.gradle.kts
└── README.md
```

---

# ⚙️ Application Workflow

```text
        ┌──────────────────────┐
        │    Launch the App    │
        └──────────┬───────────┘
                   │
                   ▼
        ┌──────────────────────┐
        │     MainActivity     │
        └──────────┬───────────┘
                   │
                   ▼
        ┌──────────────────────┐
        │      XML Layout      │
        │     Displayed        │
        └──────────┬───────────┘
                   │
                   ▼
        ┌──────────────────────┐
        │   User Interaction   │
        └──────────┬───────────┘
                   │
                   ▼
        ┌──────────────────────┐
        │    Kotlin Handles    │
        │       Events         │
        └──────────┬───────────┘
                   │
                   ▼
        ┌──────────────────────┐
        │ Application Responds │
        │   to User Actions    │
        └──────────────────────┘
```

---

# 🧩 Main Components

| Component | Purpose |
|---|---|
| `MainActivity.kt` | Contains the main application logic |
| `activity_main.xml` | Defines the main user interface |
| `AndroidManifest.xml` | Contains application configuration |
| `drawable/` | Stores icons, shapes and graphical resources |
| `layout/` | Stores application layouts |
| `values/` | Stores colors, strings and themes |
| `mipmap/` | Stores launcher icons |
| `build.gradle.kts` | Contains project dependencies and build configuration |

---

# 🎨 UI Design

The application's user interface is created using **Android XML layouts**.

The design focuses on:

- 📱 Clean interface
- 🎨 Proper UI components
- 📐 Organized layout
- 👆 Easy user interaction
- 🖼️ Appropriate icons and drawable resources
- ⚡ Smooth interaction between UI and Kotlin logic

---

# 📸 Application Screenshots

Create a folder named:

```text
screenshots
```

inside your GitHub repository and add your application screenshots.

Then use:

### 🏠 Main Screen

```markdown
![Main Screen](screenshots/main_screen.png)
```

### 📱 Application Screen

```markdown
![Application Screen](screenshots/app_screen.png)
```

### ⚙️ Functionality

```markdown
![Functionality](screenshots/functionality.png)
```

### ✅ Output

```markdown
![Output](screenshots/output.png)
```

> ⚠️ **Important:** Screenshot filenames in the README must exactly match the filenames uploaded to the `screenshots` folder, including uppercase/lowercase letters.

---

# 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/khaneshahimadri/24012011230_MAD_Practical-6.git
```

### 2️⃣ Open Android Studio

Open:

```text
Android Studio → Open → 24012011230_MAD_Practical-6
```

### 3️⃣ Sync Gradle

Wait for **Gradle Sync** to complete successfully.

### 4️⃣ Select Device

Run the application using:

- 📱 Physical Android Device

or

- 💻 Android Emulator

### 5️⃣ Run Application

Click:

```text
▶ Run 'app'
```

The application will be installed and launched on the selected Android device.

---

# 📚 Learning Outcomes

After completing this practical, I gained practical knowledge of:

- ✅ Android Studio project development
- ✅ Kotlin programming
- ✅ XML layout designing
- ✅ Android Activities
- ✅ Android UI components
- ✅ Event handling
- ✅ Drawable resources
- ✅ Application resources
- ✅ Android Manifest configuration
- ✅ Gradle build system
- ✅ Connecting XML UI with Kotlin
- ✅ Debugging Android applications
- ✅ Running applications on emulator/physical devices

---

# 🚧 Challenges Faced

During the development of this practical, I encountered and solved several challenges:

- Connecting XML components with Kotlin code.
- Managing drawable resources and icons.
- Handling click events correctly.
- Fixing missing resource errors.
- Maintaining proper Android project structure.
- Managing UI alignment and layout.
- Resolving Gradle and resource-related errors.
- Testing application functionality on Android devices.

Solving these challenges improved my understanding of **Android application development, resource management, UI design, and debugging**.

---

# 📋 Practical Information

| Information | Details |
|---|---|
| 👩‍💻 **Student Name** | Himadri Khanesha |
| 🆔 **Enrollment No.** | 24012011230 |
| 🎓 **Class** | CE-I |
| 👥 **Batch** | I-2 |
| 📚 **Subject** | Mobile Application Development |
| 🧪 **Practical No.** | Practical 6 |
| 💻 **Language** | Kotlin |
| 🎨 **UI Design** | XML |
| 🛠️ **IDE** | Android Studio |
| ⚙️ **Build System** | Gradle |
| 🏫 **Institute** | U.V. Patel College of Engineering |
| 🎓 **University** | Ganpat University |

---

# 🔗 Repository

### 📂 24012011230_MAD_Practical-6

This repository contains the complete Android Studio project developed for **Mobile Application Development Practical 6**.

---

# 👩‍💻 Developer

<div align="center">

### Himadri Khanesha

**B.Tech — Computer Engineering**

**Enrollment No.: 24012011230**

U.V. Patel College of Engineering  
Ganpat University

---

### 📱 Building Android Applications with Kotlin



</div>
