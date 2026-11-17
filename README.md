# Academic Pro – Student Learning Tracker

Academic Pro is a C++ desktop application designed to help students manage their academic activities, organize study materials, and track their learning progress.

## Features

- **Dashboard:** Displays academic information, calendar, tasks, and study progress.
- **GPA Calculator:** Allows students to add courses, enter grades and credit hours, and calculate their GPA.
- **Study Planner:** Create tasks with subjects, topics, and deadlines. Users can also mark tasks as completed and filter them.
- **Note Organizer:** Create subjects, write notes, edit existing notes, and save them.
- **Study Streak Tracker:** Log study sessions, track consecutive study days, view study activity on a calendar, and unlock achievements.

## Tech Stack

- **Language:** C++
- **Framework:** Qt 6
- **GUI:** Qt Widgets
- **Libraries:** Qt Core and Qt GUI
- **Data Storage:** QSettings and local file storage
- **Build System:** qmake
- **IDE:** Qt Creator
- **Compiler:** MinGW 64-bit

## Requirements

- Qt 6
- Qt Creator
- Qt Widgets module
- Compatible C++ compiler (MinGW 64-bit recommended)

## How to Run

1. Install Qt 6 and Qt Creator.
2. Extract the project folder.
3. Open `OOP_PROJECT.pro` in Qt Creator.
4. Select a compatible Qt 6 MinGW 64-bit kit.
5. Configure the project.
6. Click **Build** to compile the application.
7. Click **Run** to launch Academic Pro.

## Project Structure

```text
OOP_PROJECT/
│
├── main.cpp
├── mainwindow.cpp
├── mainwindow.h
├── dashboard.cpp
├── dashboard.h
├── gpacalculator.cpp
├── gpacalculator.h
├── studyplanner.cpp
├── studyplanner.h
├── noteorganizer.cpp
├── noteorganizer.h
├── streaksystem.cpp
├── streaksystem.h
│
├── OOP_PROJECT.pro
└── README.md
```

## Data Storage

The application uses local storage instead of an external database. It uses Qt settings and local files to store application data. Notes are stored as text files in the user's Documents directory.

---

Developed as a C++ Object-Oriented Programming project.