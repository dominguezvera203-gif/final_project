# Gesture-Controlled Drawing Canvas

A whiteboard-style drawing application that supports gesture-based interactions such as drawing, pinch-to-zoom, panning, undo/redo, and layer management without using external drawing libraries.

## Features

* Multi-touch drawing
* Pinch-to-zoom and pan
* Undo and redo using Command Pattern
* Layer management
* Eraser tool
* Custom canvas coordinate calculations

## Technologies Used

* JavaScript
* React Native / Expo

## Installation

```bash id="k0t5hb"
npm install
npx expo start
```

## Core Concept

The project uses the **Command Pattern** to manage undo and redo actions.
Screen-to-canvas coordinate math is implemented to keep drawing accurate during zooming and panning.

## Eraser Tool

The eraser uses the same stroke data structure as the drawing tool, making it compatible with the undo/redo system.
