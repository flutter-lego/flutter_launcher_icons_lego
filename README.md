[![lego project](https://img.shields.io/badge/powered%20by-lego-blue?logo=github)](https://github.com/melodysdreamj/lego)
[![pub package](https://img.shields.io/pub/v/flutter_launcher_icons_lego.svg)](https://pub.dartlang.org/packages/flutter_launcher_icons_lego)

# flutter_launcher_icons_lego
app icon, web favicon generator lego.

##  Installation
1. open terminal in the lego project root directory, enter the following command for install cli.
   and create a new lego project if you don't have one.
```bash
flutter pub global activate lego_cli
lego create
```
2. in terminal, enter the following command for add lego to project.
```bash
lego add flutter_launcher_icons_lego
```

3. change app icon png in `assets/lego/flutter_launcher_icons_lego` directory.

4. modify in `pubspec.yaml` file below code block.
```yaml
flutter_icons:
  image_path_android: "assets/lego/flutter_launcher_icons_lego/android.png"
  image_path_ios: "assets/lego/flutter_launcher_icons_lego/ios.png"
  android: true # can specify file name here e.g. "ic_launcher"
  ios: true # can specify file name here e.g. "My-Launcher-Icon"
  remove_alpha_ios: true
  adaptive_icon_background: "#ffffff" # only available for Android 8.0 devices and above
  adaptive_icon_foreground: "assets/lego/flutter_launcher_icons_lego/android.png" # only available for Android 8.0 devices and above
  web:
    generate: true
    image_path: "assets/lego/flutter_launcher_icons_lego/web.png"
    background_color: "#ffffff"
    theme_color: "#ffffff"
```
4. enter the following command to install the module.
 ```bash
flutter pub run flutter_launcher_icons
 ```

## Usage
Usage here
