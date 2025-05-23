Budget Tracker App (Kotlin + SQLite database )
📱 Overview
The Budget Tracker App is a fully offline Android application built with Kotlin and SQLite to help users track their expenses efficiently. Users can log in, create categories, add expenses (with optional photos), and set monthly spending goals. The app provides detailed reports on expenses per category over user-selectable periods and uses the South African Rand (R) as the currency.

✅ Features
User Authentication

Log in using a secure username and password.
Category Management

Create and manage categories for budgeting and expense tracking.
Expense Entry

Add new expenses with:
Date
Start and End Time
Description
Category
Optional photo attachment
Goal Setting

Set minimum and maximum monthly spending goals.
Expense Report

View expense entries over a custom time range.
View photos attached to expense entries.
View total spending per category over a selected time period.
Data Persistence

All data is stored locally using RoomDB (SQLite).
Robust UI

User-friendly design based on Figma prototype.
Input validation to avoid crashes and invalid data.
🛠 Tech Stack
Language: Kotlin
IDE: Android Studio
Database: Room (SQLite)
UI Design: Jetpack Compose/XML (based on Figma screenshots)
Media Handling: Optional photo attachments using ImagePicker
Authentication: Local username-password validation
🔧 Installation & Running
Clone the Repository or extract the zipped folder.
Open in Android Studio.
Make sure Gradle sync completes.
Run the project on a device or emulator.
📸 Screenshots
Screenshots of the Figma design can be found in the /screenshots folder.

💡 Notes
All monetary values are displayed in South African Rand (R).
The app works completely offline using local RoomDB storage.
Photos are stored in internal storage and linked to individual expense records.
📂 Folder Structure
BudgetTrackerApp/
│
├── app/                   # Kotlin source code
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   └── res/
│   │   │       ├── layout/        # XML layouts
│   │   │       ├── drawable/      # Icons, image placeholders
│   │   │       └── values/        # Strings, themes
│
├── screenshots/           # Figma-based UI design references
├── README.md              # You're reading it!

🎥 Demo Video Youtube
Ensure your demonstration includes: https://youtu.be/Z6eU78hAav0

A clear walk-through of each feature.

A voice-over explaining what’s being shown.

Compressed video (e.g., via Handbrake) for easy upload to Arc.
#GITHUB LINK : https://github.com/st10174327/FinTrack.git
Figma: https://www.figma.com/design/jeO75R66yExelcO1XlgEqv/FinTrack-OPSC?node-id=0-1&t=tMRSTvH7dXcwesMk-1 
Canva edits: https://www.canva.com/design/DAGnOugsKEE/SHzyLr-Yh3gOSrh3XabMDw/edit?utm_content=DAGnOugsKEE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
