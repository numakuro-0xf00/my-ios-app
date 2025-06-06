# Simple iOS To-Do App

This repository contains a very basic sample To-Do application built with **SwiftUI**. The project consists of two Swift source files located under `ToDoApp/`.

```
ToDoApp/
├── ContentView.swift
└── ToDoApp.swift
```

## Requirements
- Xcode on macOS is required to build and run this SwiftUI app.
- Compiling with `swiftc` on Linux will fail due to the missing `SwiftUI` module.

To use this code, create a new *iOS App* project in Xcode and replace the default `App` and `ContentView` files with the contents provided here. The app allows you to add, mark, and delete tasks in a list.

## Features
- Add tasks using the text field at the top.
- Toggle completion by tapping the circle next to a task.
- Delete tasks using the standard swipe-to-delete gesture.

This is a minimal example intended for educational purposes. You can further expand it with persistence, custom views, and other features as needed.
