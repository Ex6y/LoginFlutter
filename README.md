# myink

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)


///// CyberInk Login App (Flutter)

This is an example Flutter application that demonstrates a modern login screen with a customizable background, text styling, and navigation to a HomeScreen. The app is designed to showcase best practices in UI, Stack, Column, SingleChildScrollView, and image/color handling in Flutter.

Key features:

Login screen with Email and Password fields.
Login button navigates to HomeScreen.
Customizable background (image or solid color with opacity).
Responsive design using SingleChildScrollView for different screen sizes.
Uses Stack to overlay content on background.
Modern styling with rounded borders, colors, and typography.

Project Structure:


myink_flutter_app/
│
├─ assets/
│   └─ images/
│       ├─ background.jpg
│       └─ logo.png
│
├─ lib/
│   ├─ main.dart
│   ├─ home.dart
│   └─ constants/
│       └─ colors.dart
│
├─ pubspec.yaml
└─ README.md


Dependencies Setup

In your pubspec.yaml file, make sure to include:

flutter:
  uses-material-design: true

  assets:
    - assets/images/



Important Notes

Background: You can switch between an image or a solid color. For a solid color, replace Image.asset in the Stack with a colored Container.

Image opacity: To darken an image without it turning white, you can use:

color: Color(0xFF000000).withOpacity(0.5),
colorBlendMode: BlendMode.darken,



// © 2025 Eury Nunez. All rights reserved.
