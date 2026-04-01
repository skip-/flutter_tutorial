# wikipedia_reader

A Flutter project to fetch wikipedia articles using HTTP and display summaries.

App uses the architectural pattern MVVM (Model-View-ViewModel)

Model (data operations) is responsible for data and low-level tasks, such as making HTTP requests, caching data, and managing system resources used by Flutter plugins. The model does not usually need to import Flutter libraries.

View (user interface) is responsible for displaying the app elements to the user.

ViewModel (state management) connects the View to the Model and provides interactivity. Use Flutter's ChangeNotifier class to notify the UI when data changes.


## Instructions

1. Create the project and add the http package
```bash
flutter create wikipedia_reader --empty
cd wikipedia_reader
flutter pub add http
```
The "--empty" parameter generates a project without the default 'counter app' code.
Adding a package dependency using `flutter pub add [package_name]` adds the package to the pubspec.yaml and downloads it.

2. Modify the code
Edit code: added lib/summary.dart and modified lib/main.dart according to the tutorial

3. Run the app
```bash
cd /c/proj/flutter_tutorial/wikipedia_reader
flutter run -d chrome
```

