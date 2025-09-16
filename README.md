# Flutter Experiments

This repository contains five Flutter experiments, each demonstrating a different concept or feature of Flutter and Dart. These experiments are designed for beginners and intermediate learners to explore core Flutter widgets, layouts, state management, and navigation.

## Table of Contents

- [Experiment 1: Dart Basics](#experiment-1-dart-basics)
- [Experiment 2: Basic Widgets & Layouts](#experiment-2-basic-widgets--layouts)
- [Experiment 3: Responsive Layout](#experiment-3-responsive-layout)
- [Experiment 4: Navigation](#experiment-4-navigation)
- [Experiment 5: State Management](#experiment-5-state-management)
- [How to Run](#how-to-run)
- [Requirements](#requirements)

---

## Experiment 1: Dart Basics

**File:** `experiment1.dart`

This experiment demonstrates basic Dart programming concepts within a Flutter app:

- String interpolation and function calls
- Variables (`const`, `dynamic`)
- Lists and Maps
- Loops and conditionals
- Building widgets using loops and conditionals

**Highlights:**
- Shows how to use Dart functions to generate content.
- Demonstrates list and map usage in Flutter widgets.
- Uses conditional rendering and for-loops in widget trees.
![WhatsApp Image 2025-09-03 at 15 06 04_94a67401](https://github.com/user-attachments/assets/eee7310b-d8c7-49e6-8d22-88d57eb6f56a)

---

## Experiment 2: Basic Widgets & Layouts

**File:** `experiment2.dart`

This experiment introduces core Flutter widgets and layout techniques:

- Text styling
- Container decoration and styling
- Row and Column layouts
- Stack widget for overlapping elements
- Image placeholder (can be replaced with actual images)

**Highlights:**
- Demonstrates how to arrange widgets using `Row`, `Column`, and `Stack`.
- Shows how to style widgets with colors, borders, and shadows.
- Includes custom helper methods for reusable widget building.
![WhatsApp Image 2025-09-03 at 15 05 51_b596a98a](https://github.com/user-attachments/assets/359178ff-55b7-48f9-9825-797a91bc2f77)

---

## Experiment 3: Responsive Layout

**File:** `experiment3.dart`

This experiment focuses on building responsive UIs that adapt to different screen sizes:

- Uses `MediaQuery` to detect device type (mobile, tablet, desktop)
- Adjusts grid layout and font sizes based on screen width
- Demonstrates `GridView`, `LayoutBuilder`, and adaptive Row/Column layouts

**Highlights:**
- Responsive grid layout with dynamic column count and aspect ratio.
- Shows how to use `LayoutBuilder` for adaptive widget sizing.
- Includes device info card and responsive arrangement of widgets.
![3](https://github.com/user-attachments/assets/3dc0e93d-3ac4-40a1-a83c-e13325493ffa)
![31](https://github.com/user-attachments/assets/8c875c0d-bfdc-44e9-aa87-94cda5c403e3)

---

## Experiment 4: Navigation

**File:** `experiment4.dart`

This experiment covers navigation between screens in Flutter:

- Named routes and route definitions
- Passing arguments between screens
- Returning results from screens
- Navigating with replacement and popping multiple routes

**Highlights:**
- Home screen with buttons to navigate to other screens.
- Profile screen receives and displays arguments.
- Third screen returns a result to the previous screen.
- Demonstrates navigation patterns for multi-screen apps.
![navigation](https://github.com/user-attachments/assets/7f26fb55-ce4c-49a5-bdd4-75d242b89d61)

---

## Experiment 5: State Management

**File:** `experiment5.dart`

This experiment introduces state management using the Provider package:

- Stateless and Stateful widgets
- `ChangeNotifierProvider` for managing state
- `Consumer` widget for listening to state changes
- Demonstrates increment/reset actions and state sharing across widgets

**Highlights:**
- Counter example using both `setState` and Provider.
- Shows how to access and update shared state from multiple widgets.
- Explains the difference between local and global state management.
![state mang](https://github.com/user-attachments/assets/b7f4e6cd-73a3-4f48-ac3f-d6073061baf6)

---

## How to Run

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd flutter-main
   ```

2. **Install dependencies:**
   Make sure you have Flutter installed. Run:
   ```sh
   flutter pub get
   ```

3. **Run an experiment:**
   Replace the `main()` function in `lib/main.dart` (or your entry point) with the desired experiment's `main()` or widget.  
   Alternatively, you can run each experiment file directly if your IDE supports it.

   Example:
   ```dart
   import 'experiment1.dart'; // or experiment2.dart, etc.
   void main() => runApp(const Experiment1());
   ```

   For experiments with their own `main()` (like `experiment4.dart` and `experiment5.dart`), you can run them directly.

---

## Requirements

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- Dart 3.x
- For Experiment 5: Add `provider` to your `pubspec.yaml` dependencies:
  ```yaml
  dependencies:
    provider: ^6.0.0
  ```

---

## License

This project is for educational purposes.

---


**Explore each experiment to learn more about Flutter and Dart!**
