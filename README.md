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

3. Common widgets for composing your app

Scaffold
AppBar
Row
Column

Container
Center
Text
Padding
ColoredBox
SizedBox
DecoratedBox

Icon
Text
Image
Checkbox


## NOTES

### Layouts and Constraints

BoxDecoration allows for basic styling of the container
* Border, background, color: set with BoxDecoration

*Three Rules*
* Constraints go down
  * Parents communicate down to child(ren) widget(s) the minimum and maximum width and height
* Sizes go up
  * Children report back up to parents how much of the allowable space they will take up
* Parents set the position

Widgets have differing default behavior
* Center tries to occupy all available space
* Image takes only what is required for the image
* Opacity tries to match the size of its child(ren)

Rows and Columns
* Rows tell children they must conform to the height, but can be as wide as available space permits
* Rows are unbounded in width
* Unbounded width/height errors
    A widget in a row that requests to be as big as possible will cause an unbounded error as it could be infinitely large.


