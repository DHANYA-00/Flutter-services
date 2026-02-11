# Flutter & Dart Fundamentals – Concept 1

## Overview

This project explores the basics of Flutter architecture, widget-based UI, and Dart language fundamentals. It demonstrates how Flutter builds reactive user interfaces using a single codebase for cross-platform development.

## StatelessWidget vs StatefulWidget

- `StatelessWidget`: Used for static UI that does not change once built (e.g., Text, Icon).

- `StatefulWidget`: Used for dynamic UI that updates based on user interaction or data changes (e.g., Counter app).

## Widget Tree & Reactive UI

Flutter builds the UI using a widget tree, where every element is a widget.
When the app state changes, setState() triggers Flutter to rebuild only the affected widgets, making UI updates fast and efficient.

## Why Dart for Flutter

- Strongly typed and object-oriented

- Supports async/await for smooth asynchronous operations

- Null safety reduces runtime errors

- Optimized for fast UI rendering and Hot Reload

## Demo App

A simple `The Laggy To-Do List` is used to demonstrate:

- Stateful widgets

- Reactive UI updates using setState()

- Instant UI changes with Hot Reload

## Conclusion

Flutter’s reactive model and Dart’s simplicity make cross-platform app development faster, cleaner, and more efficient compared to traditional native approaches. And I have understood the use of Flutter.