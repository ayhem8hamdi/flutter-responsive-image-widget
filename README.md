# Flutter Responsive Image Widget

A clean, production-ready Flutter widget for responsive image rendering — ideal for modern UI layouts that need to scale cleanly across devices.

## ✨ Features

- Maintains original aspect ratio
- Scales based on design width
- Prevents layout overflow
- Works perfectly inside `ListView`, `Column`, `GridView`, etc.
- Configurable min/max width and `BoxFit`

## 🚀 Usage

```dart
ResponsiveImage(
  imageProvider: AssetImage('assets/image.png'),
  imageDesignWidth: 120,
  screenDesignWidth: 375,
  imageDesignAspectRatio: 1.2,
)
