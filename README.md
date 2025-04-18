# Task Force - Android Task Manager App

## Overview

**Task Force** is a user-friendly Android app that lets users manage tasks with deadlines, tags, priorities, and reminders. 
Designed for productivity, it supports advanced sorting, filtering, and smart UI feedback for overdue and completed tasks.

---

## Features
- Add tasks with:
  - Name (required, 64 characters max)
  - Description (optional, up to 4000 characters)
  - Tags (create or reuse a single-word tag)
  - Due date (optional)
  - Completion status (required true/false)
  - Priority (required integer)
- Data is persistent across sessions
- Visual styling for:
  - Completed tasks (e.g., strikethrough or faded)
  - Overdue tasks (e.g., red border or highlight)
- Reminders: configurable relative to due date (e.g., 3 hours before)
- Sort tasks by: priority (default), name, tag, due date
- Filter tasks by: name, tag, due date
- Search by task description
- Drag-and-drop to reorder and change task priority


## Getting Started

### Prerequisites

- Android Studio (Hedgehog or later)
- Android Emulator or physical device (API level 26+)

### How to Run the App

1. Clone the repository:
In terminal: 
git clone https://github.com/ar26/task-force.git

2. Open Android Studio
Choose "Open" from the welcome screen or File > Open
Select the cloned project folder (ex: task-force)

3. Let Gradle sync and build the project automatically
If prompted, click “Trust Project” and allow indexing

4. Connect an emulator or Android device
You can create a virtual device using AVD Manager (Tools > Device Manager)

5. Run the app
Click the green Run button at the top
Select your device/emulator if needed


