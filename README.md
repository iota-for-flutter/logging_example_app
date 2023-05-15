# Logging Example App

---

Logging: Stream Rust log messages (trace, debug, warn, info, error) to Flutter.

---

## What is the goal?

The aim is to use logger macros on the Rust side, such as trace!, debug!, warn!, info!, and error!, and integrate them into the Rust code in the application. Flutter is supposed to process the incoming log entries.

Here, in a slightly modified form, I present the logging example of the Flutter-Rust-Bridge:

<a href="https://cjycode.com/flutter_rust_bridge/feature/logging.html" target="_blank">👉 &nbsp; Flutter Rust Bridge - Logging</a>

The app uses the Flutter Chat UI plugin, which displays a list of incoming messages and allows users to send their own messages. For demonstration purposes, this message is converted into multiple log messages on the Rust side. Flutter receives the entries and can decide using a switch whether the new entry should be streamed to the chat list or to the console.

## Usage of the repository

I recommend setting up the project from scratch. I don't have experience in downloading the repository and magically getting it up and running with a single install command. That's why I refer you to the tutorial and the corresponding video:

<a href="https://iota-for-flutter.github.io/tutorial/building-without-iota/flutter-and-rust/logging-example-app/" target="_blank">👉 &nbsp; Logging Example App</a>
