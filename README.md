---

# SmartSpender App (Kotlin + RoomDB)

## 📱 Overview

The **SmartSpender App** is a fully offline Android application built with Kotlin and RoomDB, helping users track expenses, manage categories, and set monthly financial goals. Users can log in, add expenses with optional photos, and monitor their spending over custom periods. All amounts are displayed in South African Rand (R).

---

## ✅ Features

* **User Authentication**

  * Log in with a username and password securely.

* **Category Management**

  * Create and manage spending categories.

* **Expense Tracking**

  * Add new expenses with:

    * Date
    * Start and End Time
    * Description
    * Category
    * Optional photo attachment

* **Goal Setting**

  * Set **minimum** and **maximum** monthly spending limits.

* **Expense Reports**

  * View all expense entries within a selected date range.
  * Access stored photos attached to expenses.
  * Analyze total spending per category during a selectable period.

* **Offline Data Storage**

  * Full local persistence using **RoomDB (SQLite)**.

* **User-Friendly Interface**

  * Clean design layout with input validation to prevent crashes and errors.

---

## 🛠 Tech Stack

* **Language**: Kotlin
* **IDE**: Android Studio
* **Database**: Room (SQLite)
* **UI Design**: XML layouts
* **Authentication**: Local username-password validation
* **Photo Handling**: Internal storage management for expense images

---

## 🔧 Installation & Running

1. **Download** or **clone** the project.
2. **Open** the project in **Android Studio**.
3. Allow **Gradle** to sync all dependencies.
4. **Build and run** the app on an emulator or Android device.
5. Log in or create a user and start tracking expenses!

---

## 📸 Screenshots

> UI design references and screenshots are available in the `/screenshots` folder.

---

## 💡 Additional Notes

* All monetary values are calculated and displayed in **South African Rand (R)**.
* The app is fully functional offline, ensuring fast and reliable access to your data.
* All attached photos are saved securely in the device’s internal storage.

---

## 📂 Folder Structure

```bash
SmartSpender/
│
├── app/                   # Source code
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   └── res/
│   │   │       ├── layout/        # XML layouts
│   │   │       ├── drawable/      # Icons and images
│   │   │       └── values/        # Themes, styles, and strings
│
├── screenshots/           # UI and design references
├── PGSL_Form.pdf          # Project form and learning outcomes
├── demo/                  # Demo video and voice-over
├── README.md              # This file
```

---

## 🎥 Demo Video Guidelines

* The demo video must clearly walk through each app feature.
* Include a **voice-over** explaining what is being demonstrated.
* **Compress** the video using tools like Handbrake for easier upload to Arc.

---
🌐 Links
📄 Canva Design:
https://www.canva.com/design/DAGnPg0fBAc/UbifJ4FxypdlHZ-OfvDntA/edit?utm_content=DAGnPg0fBAc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton 

🎥 YouTube Demo Video:
https://youtube.com/shorts/D0oT_n03Ess 
---
✅ **Smart Choices. Smart Savings.** — Thank you for using **SmartSpender**!

---
