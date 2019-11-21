# Circular Text Widget

[![pub package](https://img.shields.io/pub/v/flutter_circular_text.svg)](https://pub.dartlang.org/packages/flutter_circular_text)

## Installation

Add dependency in `pubspec.yaml`:
```yaml
dependencies:
  flutter_circular_text: "^0.1.0"
```

Import in your project:
```dart
import 'package:flutter_circular_text/circular_text.dart';
```

## Basic usage

```dart
CircularText(
  text: "circular text widget",
  textStyle: TextStyle(
      fontSize: 25,
      color: Colors.blue,
      fontWeight: FontWeight.bold
  ),
  radius: 125,
  spacing: 10,
  startAngle: 0,
  backgroundPaint: Paint()..color = Colors.grey.shade200,
  backgroundShape: BackgroundShape.circle,
  position: CircularTextPosition.inside,
  direction: CircularTextDirection.clockwise
)
```

## Examples

[example](https://github.com/faob-dev/flutter_circular_text/tree/master/example) project contains demo

### Demo

##### v 0.1.0
![alt tag](https://raw.githubusercontent.com/faob-dev/flutter_circular_text/master/screenshots/circular_text.gif)

##### v 0.2.0
![alt tag](https://raw.githubusercontent.com/faob-dev/flutter_circular_text/master/screenshots/circular_text1.gif)

## Changelog
Check [Changelog](https://github.com/faob-dev/flutter_circular_text/blob/master/CHANGELOG.md) for updates

## Bugs/Requests
Reporting issues and requests for new features are always welcome.
