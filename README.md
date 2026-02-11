# Final Project – Android Development (Flutter)

A production-ready mobile application built with Flutter as the final project of the Android Development Workshop.
This project demonstrates applied knowledge of modern mobile engineering principles, UI implementation from design prototypes, and clean project structuring.

---

## Project Overview

This application was developed to translate a structured design prototype into a functional, scalable Flutter application. The goal was not only to build a working app, but to demonstrate:
- Clean architecture mindset
- Reusable component structuring
- Proper state handling
- Maintainable and readable codebase
- UI consistency with design reference
The project reflects practical mobile development workflow:
Design → Implementation → Testing → Refinement

---

## Objectives

- Implement a multi-screen Flutter application
- Apply modular project structure
- Follow Flutter best practices
- Integrate user interaction logic and navigation flow
- Deliver a portfolio-ready Android application

---

## Tech Stack
- Layer	Technology
- Framework	Flutter
- Language	Dart
- IDE	Android Studio
- UI Design	Figma
- Version Control	Git & GitHub

---

## Core Features

- Multi-screen navigation
- Responsive UI layout
- Structured widget hierarchy
- Modular folder organization
- Form input handling
- Clean visual implementation from design prototype

---

## Architecture & Project Structure

The project follows a modular separation of concerns:

```text
lib/
│
├── screens/        → UI screens (Page-level widgets)
├── widgets/        → Reusable UI components
├── models/         → Data models (if applicable)
├── services/       → Business logic / API calls (if applicable)
├── utils/          → Helpers / constants
│
└── main.dart       → Application entry point
```

### Design Principles Applied:
- Stateless vs Stateful separation
- Widget composition over monolithic UI
- Clear file naming conventions
- Logical directory grouping
- Readability-first code formatting

---

## UI Reference

The UI was implemented based on the following Figma prototype:

Figma Prototype:
https://www.figma.com/proto/HLqqYK7PZQk6ObItnV7oPr/Final-Project-Android-Workshop-Deisgn

### The implementation focuses on:
- Layout precision
- Spacing consistency
- Visual hierarchy
- Component reusability

---

## Getting Started

Prerequisites:
- Flutter SDK installed
- Android Studio
- Android Emulator or physical device
- Git

### Installation
```bash
git clone https://github.com/Shevanka/final-project-android-dev.git
cd final-project-android-dev
flutter pub get
flutter run
```

---

## Testing

To execute tests:

```bash
flutter test
```

If testing is not yet implemented, consider adding:
- Widget tests
- Integration tests
- Basic unit tests for business logic

---

## Engineering Considerations

### This project emphasizes:
- Maintainability over quick fixes
- Scalability in folder organization
- Reusable UI components
- Clean separation of concerns
- Clear commit history 

### Future improvements could include:
- State management implementation (Provider / Riverpod / Bloc)
- API integration
- Authentication system
- Persistent local storage
- CI/CD workflow
- Play Store deployment build

---

## What This Project Demonstrates

- Practical Flutter development capability
- Ability to convert design into working product
- Understanding of mobile UI structure
- Code organization suitable for real-world scaling
- Readiness for collaborative development
📄 License

This project is licensed under the MIT License.
