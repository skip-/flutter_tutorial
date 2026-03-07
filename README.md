# README

This is code built while following the Flutter learning pathway.
(https://docs.flutter.dev/learn/pathway/tutorial/create-an-app)

## Steps

1. Create a Flutter project

In GitHub, create a new project called flutter_tutorial

```bash
cd /c/proj
git clone https://github.com/skip-/flutter_tutorial.git
cd /c/proj/flutter_tutorial
flutter create birdle --empty
```

Output

```text

┌─────────────────────────────────────────────────────────┐
│ A new version of Flutter is available!                  │
│                                                         │
│ To update to the latest version, run "flutter upgrade". │
└─────────────────────────────────────────────────────────┘
Creating project birdle...
Resolving dependencies in `birdle`...
Downloading packages...
Got dependencies in `birdle`.
Wrote 130 files.

All done!
You can find general documentation for Flutter at: https://docs.flutter.dev/
Detailed API documentation is available at: https://api.flutter.dev/
If you prefer video documentation, consider: https://www.youtube.com/c/flutterdev

In order to run your empty application, type:

  $ cd birdle
  $ flutter run

Your empty application code is in birdle\lib\main.dart.
```

Main file is birdle/lib/main.dart
Class MainApp builds MaterialApp, which contains Scaffold(Center(Text('Hello world!')))

2. Run empty template app

```bash
cd /c/proj/flutter_tutorial/birdle
flutter run -d chrome
```

This will launch a Dart virtual machine with a web server. It remains active in the terminal and allows for changes to the code and "hot reloading" of the changes for testing.

