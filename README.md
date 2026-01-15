# Android To-Do List

https://github.com/user-attachments/assets/54335e77-67f9-43a4-ac15-41a53d3202e3

A lightweight, efficient, and modern To-Do List application built for Android. This app allows users to create, manage, and track daily tasks with a focus on simplicity and persistence.

## ✨ Features
- **Persistent Storage:** Uses **Room Persistence Library** to ensure your tasks are saved even after closing the app or restarting your device.
- **Dynamic List:** Implemented with **RecyclerView** for smooth scrolling and efficient memory management.
- **Modern UI:** Built with **Material Design components** and full support for **Android 15 (API 35)** "Edge-to-Edge" display.
- **Interactive UX:** 
    - Real-time task status updates.
    - Floating Action Button (FAB) for quick task entry.
    - Delete functionality to keep your list clean.

## 🛠️ Tech Stack & Requirements
- **Language:** Java
- **IDE:** Android Studio (Ladybug or newer recommended)
- **Minimum SDK:** 24 (Android 7.0 Nougat)
- **Target/Compile SDK:** 35 (Android 15)
- **Database:** Room Persistence Library
- **Architecture:** Local Database (DAO, Entity, Database Implementation)

## 🚀 Getting Started

1.  **Clone the repository**
    ```bash
    git clone https://github.com/siddhic0311/OIBSIP-to-do-list.git
    ```
2.  **Open in Android Studio**
    - Select `File > Open` and navigate to the project folder.
3.  **Sync Gradle**
    - Android Studio will automatically prompt you to sync the Gradle files. Ensure you are connected to the internet to download the Room dependencies.
4.  **Run the App**
    - Connect an Android device or start an emulator (API 24+) and click the **Run** button.

## 📂 Project Structure
```text
app/src/main/java/com/example/to_do_list_1/
├── AppDatabase.java    # Room Database configuration
├── Task.java           # Data Entity (Task model)
├── TaskDao.java        # Data Access Object (SQL Queries)
├── TaskAdapter.java    # RecyclerView Adapter for list rendering
└── MainActivity.java   # Main UI logic and lifecycle management
```

