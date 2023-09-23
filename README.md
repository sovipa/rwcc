# RWCC App creation
Participants: Soham, Akshith, Aditya

## App creation using Flutter and Dart: Step-by-step *(pretty much)*

### Step 1 - Flutter
 - [Download Flutter ZIP file](https://docs.flutter.dev/get-started/install/windows)
 - **Note:** Extract to C drive (NOT Program files)
 - Open System Environment Variables (Comman Prompt) --> (and follow steps as given on the site)

### Step 0 - Git Bash
 - [Download GitBash](https://gitforwindows.org/)

## # Resources
 - Youtube: [Flutter Basics by a REAL Project - 2023](https://youtu.be/VFDbZk2xhO4)
 - Google Codelabs: [Your 1st flutter app](https://codelabs.developers.google.com/codelabs/flutter-codelab-first#2)
 - Flutter Codelabs: [Get started notes](https://docs.flutter.dev/get-started/codelab)

## Topic
"Possibilities for a safer world" **(confirm with ma'am)**

## VS code
*# (Downlaod if not on PC already)*

 - After done with Step 1 (and 0), open VS code.
 - Use shortcut key - Ctrl+Shift+P.
 - Type 'flutter' and select - 'Flutter: New Project'.
 - Then select 'Application' (**for learning**).
 - Select the Folder in which u wanna create the project.

### Install the VS Code Flutter extension

   - Start VS Code.
   - Open a browser and go to the [Flutter extension page](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter) on the Visual Studio Marketplace.
   - Click Install. Installing the Flutter extension also installs the Dart extension.

### Doctor
Run 'flutter doctor'

You should see something like this in the VS code output section:

Output Preview 1:
```
[myflutter] flutter create --template app --overwrite .
(some info)
Waiting for another flutter command to release the startup lock...
```

 - Now run 'flutter run'

Terminal preview 1:
```
PS C:\source-code\flutter-first-project\myflutter> flutter run
Multiple devices found:
Chrome (web) • chrome • web-javascript • Google Chrome 113.0.5672.93
Edge (web)   • edge   • web-javascript • Microsoft Edge 117.0.2045.36
[1]: Chrome (chrome)
[2]: Edge (edge)
Please choose one (To quit, press "q/Q"): 2
Launching lib\main.dart on Edge in debug mode...
Waiting for connection from debug service on Edge...               29.9s
This app is linked to the debug service: ws://127.0.0.1:60765/YOTlJTnlDxU=/ws
Debug service listening on ws://127.0.0.1:60765/YOTlJTnlDxU=/ws

 Running with sound null safety

  To hot restart changes while running, press "r" or "R".
For a more detailed help message, press "h". To quit, press "q".

An Observatory debugger and profiler on Edge is available at: http://127.0.0.1:60765/YOTlJTnlDxU=
The Flutter DevTools debugger and profiler on Edge is available at: http://127.0.0.1:9101?uri=http://127.0.0.1:60765/YOTlJTnlDxU=
Application finished.
```

Output preview 2:
```

  ╔════════════════════════════════════════════════════════════════════════════╗
  ║                 Welcome to Flutter! - https://flutter.dev                  ║
  ║                                                                            ║
  ║ The Flutter tool uses Google Analytics to anonymously report feature usage ║
  ║ statistics and basic crash reports. This data is used to help improve      ║
  ║ Flutter tools over time.                                                   ║
  ║                                                                            ║
  ║ Flutter tool analytics are not sent on the very first run. To disable      ║
  ║ reporting, type 'flutter config --no-analytics'. To display the current    ║
  ║ setting, type 'flutter config'. If you opt out of analytics, an opt-out    ║
  ║ event will be sent, and then no further information will be sent by the    ║
  ║ Flutter tool.                                                              ║
  ║                                                                            ║
  ║ By downloading the Flutter SDK, you agree to the Google Terms of Service.  ║
  ║ Note: The Google Privacy Policy describes how data is handled in this      ║
  ║ service.                                                                   ║
  ║                                                                            ║
  ║ Moreover, Flutter includes the Dart SDK, which may send usage metrics and  ║
  ║ crash reports to Google.                                                   ║
  ║                                                                            ║
  ║ Read about data we send with crash reports:                                ║
  ║ https://flutter.dev/docs/reference/crash-reporting                         ║
  ║                                                                            ║
  ║ See Google's privacy policy:                                               ║
  ║ https://policies.google.com/privacy                                        ║
  ╚════════════════════════════════════════════════════════════════════════════╝

Creating project ....
  lib\main.dart (created)
  pubspec.yaml (created)
  README.md (created)
  test\widget_test.dart (created)
  .gitignore (created)
  .idea\libraries\Dart_SDK.xml (created)
  .idea\libraries\KotlinJavaRuntime.xml (created)
  .idea\modules.xml (created)
  .idea\runConfigurations\main_dart.xml (created)
  .idea\workspace.xml (created)
  .metadata (created)
  analysis_options.yaml (created)
  android\app\build.gradle (created)
  android\app\src\main\kotlin\com\example\myflutter\MainActivity.kt (created)
  android\build.gradle (created)
  android\myflutter_android.iml (created)
  android\.gitignore (created)
  android\app\src\debug\AndroidManifest.xml (created)
  android\app\src\main\AndroidManifest.xml (created)
  android\app\src\main\res\drawable\launch_background.xml (created)
  android\app\src\main\res\drawable-v21\launch_background.xml (created)
  android\app\src\main\res\mipmap-hdpi\ic_launcher.png (created)
  android\app\src\main\res\mipmap-mdpi\ic_launcher.png (created)
  android\app\src\main\res\mipmap-xhdpi\ic_launcher.png (created)
  android\app\src\main\res\mipmap-xxhdpi\ic_launcher.png (created)
  android\app\src\main\res\mipmap-xxxhdpi\ic_launcher.png (created)
  android\app\src\main\res\values\styles.xml (created)
  android\app\src\main\res\values-night\styles.xml (created)
  android\app\src\profile\AndroidManifest.xml (created)
  android\gradle\wrapper\gradle-wrapper.properties (created)
  android\gradle.properties (created)
  android\settings.gradle (created)
  ios\Runner\AppDelegate.swift (created)
  ios\Runner\Runner-Bridging-Header.h (created)
  ios\Runner.xcodeproj\project.pbxproj (created)
  ios\Runner.xcodeproj\xcshareddata\xcschemes\Runner.xcscheme (created)
  ios\.gitignore (created)
  ios\Flutter\AppFrameworkInfo.plist (created)
  ios\Flutter\Debug.xcconfig (created)
  ios\Flutter\Release.xcconfig (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Contents.json (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-1024x1024@1x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@1x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@2x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@3x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@1x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@2x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@3x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@1x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@2x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@3x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-60x60@2x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-60x60@3x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-76x76@1x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-76x76@2x.png (created)
  ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-83.5x83.5@2x.png (created)
  ios\Runner\Assets.xcassets\LaunchImage.imageset\Contents.json (created)
  ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage.png (created)
  ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage@2x.png (created)
  ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage@3x.png (created)
  ios\Runner\Assets.xcassets\LaunchImage.imageset\README.md (created)
  ios\Runner\Base.lproj\LaunchScreen.storyboard (created)
  ios\Runner\Base.lproj\Main.storyboard (created)
  ios\Runner\Info.plist (created)
  ios\Runner.xcodeproj\project.xcworkspace\contents.xcworkspacedata (created)
  ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
  ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings (created)
  ios\Runner.xcodeproj\xcshareddata\xcschemes\Runner.xcscheme (overwritten)
  ios\Runner.xcworkspace\contents.xcworkspacedata (created)
  ios\Runner.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
  ios\Runner.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings (created)
  myflutter.iml (created)
  web\favicon.png (created)
  web\icons\Icon-192.png (created)
  web\icons\Icon-512.png (created)
  web\icons\Icon-maskable-192.png (created)
  web\icons\Icon-maskable-512.png (created)
  web\index.html (created)
  web\manifest.json (created)
Running "flutter pub get" in myflutter...                           4.1s
Wrote 82 files.

All done!
In order to run your application, type:

  $ cd .
  $ flutter run

Your application code is in .\lib\main.dart.
```

That's how we start.
