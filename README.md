# Todoey

![Author - Rehan Khan](https://img.shields.io/badge/Author-Rehan%20Khan-blue)

A cross-platform to-do list app built with Flutter. Add, complete, and delete tasks with a clean Material Design interface.

## Features

- Add new tasks via floating action button
- Mark tasks as done with checkboxes
- Delete tasks by long-pressing
- Live task count display
- Provider-based state management
- Runs on both iOS and Android

## Tech Stack

- **Framework:** Flutter
- **Language:** Dart
- **State Management:** Provider

## Project Structure

```
Todoey/
├── lib/
│   ├── main.dart                  # Entry point with Provider setup
│   ├── models/
│   │   ├── task.dart              # Task model
│   │   └── task_data.dart         # TaskData provider (state management)
│   ├── screens/
│   │   ├── tasks_screen.dart      # Main task list screen
│   │   └── add_task_screen.dart   # Add task bottom sheet
│   └── widgets/
│       ├── tasks_list.dart        # Task list widget
│       └── taks_tile.dart         # Individual task tile
├── ios/                           # iOS platform files
├── android/                       # Android platform files
└── pubspec.yaml                   # Dependencies
```

## Getting Started

**Prerequisites:** [Flutter SDK](https://flutter.dev/docs/get-started/install)

```sh
git clone https://github.com/khan-rehan/Todoey.git
cd Todoey
flutter run
```

### iOS

```sh
open -a Simulator
flutter run
```

Or open `ios/Runner.xcodeproj` in Xcode and hit play.

### Android

Ensure an Android emulator is running, then:

```sh
flutter run
```

## Screenshots

**Main Screen**

<img width="423" alt="Main Screen" src="https://user-images.githubusercontent.com/42263217/63638256-841d6a80-c6a3-11e9-9edb-54faa80d6138.png">

**Adding a Task**

<img width="934" alt="Add Task" src="https://user-images.githubusercontent.com/42263217/63638299-145baf80-c6a4-11e9-854d-49533306bf98.png">

**Completing & Deleting Tasks**

<img width="425" alt="Tasks Done" src="https://user-images.githubusercontent.com/42263217/63638264-913a5980-c6a3-11e9-9358-66005584400a.png">
