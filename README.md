# All-in-One 🧰✨

An everyday utility app built with Swift and SwiftUI for macOS. Bring notes, tasks, calculations, drawing, personal trackers, weather, and quick tools together in one place. With a colourful gradient sidebar, distinct tool icons, and a dedicated workspace, All-in-One provides a central home for a variety of everyday activities. 🖥️🎨

## Features

- ✅ To-Do List
- 📝 Notes Pad
- 🧮 Calculator
- 🎨 Drawing Pad
- 📅 Calendar
- 😊 Mood Tracker
- 💬 Daily Quotes
- 🪙 Coin Flip
- 🎲 Dice Roller
- 🌤️ Weather Forecast
- ⏱️ Timer & Stopwatch
- ⭐ Habit Tracker
- 💰 Budget Planner
- 🚶 Fitness Tracker
- 💬 AI Chatbot entry with an availability notice in the inspected build
- 🌙 Appearance toggle
- 🌈 Colourful gradient sidebar
- 🧭 Tools organised into Released Apps, More Apps, and Coming Soon

## Requirements

- macOS 15.1 or later, as declared by the app bundle
- An Intel or Apple silicon Mac
- An internet connection for weather requests

The supplied application includes both Intel and Apple silicon executables. Python and Tkinter are not required.

## Installation

1. Obtain the `All in one.zip` application archive.
2. Double-click the ZIP to extract it.
3. Move `All in one.app` into your Applications folder.
4. Open the app from Applications.

The current package contains a compiled macOS application. Swift source files and source-build instructions are not included.

## Usage

Launch **All in one** from Applications.

Alternatively, after installing it in Applications, launch it from Terminal:

```bash
open "/Applications/All in one.app"
```

## How to Use

1. Launch the application. 🧰
2. Browse the tools in the left sidebar.
3. Select a tool to open its workspace.
4. Scroll down to explore the additional tools.
5. Use the appearance toggle at the top of the sidebar.
6. Browse the Coming Soon section to see planned additions.

## Productivity Tools

- ✅ **To-Do List** — The app’s task tool; the compiled task model includes a title, due date, and completion status.
- 📝 **Notes Pad** — A dedicated notes tool.
- 🧮 **Calculator** — A dedicated calculation tool.
- 📅 **Calendar** — A mini calendar with date-selection and event-entry components.
- ⏱️ **Timer & Stopwatch** — A dedicated timing tool.

## Creative & Quick Tools

- 🎨 **Drawing Pad** — Drawing components include strokes, colours, and line widths.
- 💬 **Daily Quotes** — Includes a built-in collection of motivational quotes.
- 🪙 **Coin Flip** — A quick coin-flip tool.
- 🎲 **Dice Roller** — A quick dice tool.

## Personal Trackers

- 😊 **Mood Tracker** — Includes fields for the latest mood and its date.
- ⭐ **Habit Tracker** — Includes habits such as Drink Water, Read, Plan Tomorrow, and Move for 30 Minutes.
- 💰 **Budget Planner** — Includes budget, expense-name, and expense-amount components.
- 🚶 **Fitness Tracker** — Includes step-count and goal components.

## Weather

The tool labelled **Weather Forecast** includes a request to Open-Meteo for current weather at Singapore coordinates.

The requested information includes:

- 🌡️ Temperature
- 🌡️ Feels-like temperature
- 💨 Wind speed

The inspected build also includes loading and weather-unavailable messages.

## AI Chatbot

An **AI Chatbot** entry appears under Released Apps.

The inspected build contains an **AI Chat Unavailable** screen with a country-or-region availability message. Working AI responses and a connected AI service have not been verified.

## Technical Details

- Built with Swift and SwiftUI
- Packaged as a native macOS `.app`
- Version 1.0, build 1
- Includes Intel `x86_64` and Apple silicon `arm64` executables
- Uses separate SwiftUI view types for the individual tools
- Includes Combine observable-object components for task management
- Includes an Open-Meteo current-weather request
- Bundles an application icon and compiled visual assets

This README describes the supplied application bundle and its visible interface. The source project was not included, and individual tool workflows, data persistence, and external integrations have not been fully verified.

## Future Enhancements

The following tools are listed in the app’s **Coming Soon** section:

- 🎙️ Voice Recorder
- 📖 Recipe Book
- 🌐 Language Translator
- 📊 Stock Market Tracker
- 🗓️ Event Planner

These entries represent planned additions rather than confirmed working features.

## License

Open source - Feel free to take inspiration!
