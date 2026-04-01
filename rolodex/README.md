# rolodex

A Flutter project which uses the Cupertino assets library (to look like iOS).

Teaches adaptive layouts, comprehensive theming, navigation patterns, advanced scrolling.

* Building responsive layouts with `LayoutBuilder`.
* Using advanced scrolling with slivers and search.
* Implementing stack-based navigation patterns.
* Creating comprehensive themes using `CupertinoThemeData`.
* Supporting both light and dark themes.
* Creating an iOS-style UI using Cupertino widgets.

## Instructions

1. Create a project without counter app

```bash
cd /c/proj/flutter_tutorial
flutter create rolodex --empty
```

2. Add Cupertino icons

```bash
cd /c/proj/flutter_tutorial/rolodex
flutter pub add cupertino_icons
```

3. Create project structure

```bash
cd /c/proj/flutter_tutorial/rolodex
mkdir lib/data lib/screens lib/theme
```

4. Modify main.dart to use CupertinoApp instead of MaterialApp. This provides iOS-style widgets and styling.


