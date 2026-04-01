# birdle

A new Flutter project.

## Run project

```bash
cd /c/proj/flutter_tutorials/birdle
flutter run -d chrome
```

## Run DevTools

```bash
cd /c/proj/flutter_tutorials/birdle
dart devtools
```

Look for the following messages in the terminal after starting the app.

```
Debug service listening on ws://127.0.0.1:57589/_FuA6Vjwmtg=/ws
A Dart VM Service on Chrome is available at: http://127.0.0.1:57589/_FuA6Vjwmtg=
The Flutter DevTools debugger and profiler on Chrome is available at:
http://127.0.0.1:57589/_FuA6Vjwmtg=/devtools/?uri=ws://127.0.0.1:57589/_FuA6Vjwm
tg=/ws
```

In the browser window opened by `dart devtools` enter the connection URL:
`http://127.0.0.1:57589/_FuA6Vjwmtg=`


### Game

Odd behavior - only accepts a limited set of words as legal guesses. Should probably be changed to allow any combination of five alphabet characters (no numbers or special characters).

