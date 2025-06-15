# Olisthelper

<p align="center">
  <img src="https://raw.githubusercontent.com/OpenListTeam/Logo/main/OpenList.svg" width="100" height="100">
</p>

English | [简体中文](./README_zh-Hans.md) |  [CODE_OF_CONDUCT](./CODE_OF_CONDUCT.md)

![](https://img.shields.io/badge/language-dart-blue.svg?style=for-the-badge&color=00ACC1)
![Downloads](https://img.shields.io/badge/flutter-00B0FF?style=for-the-badge&logo=flutter)
[![](https://img.shields.io/github/downloads/yeqiu600/Olisthelper/total?style=for-the-badge&color=FF2196)](https://github.com/yeqiu600/Olisthelper/releases)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/yeqiu600/Olisthelper?include_prereleases&style=for-the-badge)](https://github.com/yeqiu600/Olisthelper/releases/latest)
[![](https://img.shields.io/github/license/yeqiu600/Olisthelper?style=for-the-badge)](./LICENSE)
![](https://img.shields.io/github/stars/yeqiu600/Olisthelper?style=for-the-badge)
![](https://img.shields.io/github/issues/yeqiu600/Olisthelper?style=for-the-badge&color=9C27B0)

Olist Helper is an application developed using Flutter, designed to simplify the use of the desktop version of Olist. It can manage Olist, allowing you to easily start and stop the Olist program.

*Maintainer needed for the macOS part of the code. No new macOS-related changes or updates will be accepted until volunteers.*

### Screenshots
| ![image](https://github.com/yeqiu600/Olisthelper/assets/16839488/5b77df3a-8b07-40e4-adc5-9f0907f6a3f9) | ![image](https://github.com/yeqiu600/Olisthelper/assets/16839488/5a85db81-de92-4362-8c01-73e89482dcb7) |
| --------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| ![image](https://github.com/yeqiu600/Olisthelper/assets/16839488/0f28c3a0-aac5-40ac-87e1-e53ae597a738) | ![image](https://github.com/yeqiu600/Olisthelper/assets/16839488/e1b23c3c-cc62-4df8-8406-da41f798416e) |

Olist Helper includes several useful features:

- Automatic launching of Olist
- Minimizing to the system tray
- Automatic startup on boot, with the option for silent startup
- Quick access to Olist version and administrator information
- Adjustable Olist startup parameters. You can customize the startup parameters to meet your specific needs and preferences.

Free. No tracking. No ads.

Currently, this app is available on Windows and macOS. Adaptation plans for more platforms are in progress.

Please note that this program does not include the binary files for Olist. You will need to download them manually.

|                     | Olist                        | Olisthelper | Olist desktop   |
| ------------------- | ---------------------------- | ----------- | --------------- |
| Price               | 🆓 Free                       | 🆓 Free      | 💰8$/50￥         |
| Startup at boot     | 🛠️ Needs manual configuration | ✅ Supported | ✅ Supported     |
| Silent startup      | ❌ Not supported              | ✅ Supported | ✅ Supported     |
| Accompanied startup | ❌ Not supported              | ✅ Supported | ✅ Supported     |
| GUI                 | ❌ Not supported              | ✅ Supported | ✅ Supported     |
| System tray         | ❌ Not supported              | ✅ Supported | ✅ Supported     |
| Startup parameters  | 🛠️ Needs manual configuration | ✅ Supported | ❌ Not supported |
| Http proxy          | 🛠️ Needs manual configuration | ✅ Supported | ❌ Not supported |

### Getting Started
[Wiki (Simplified Chinese language)](https://github.com/yeqiu600/Olisthelper/wiki)

## Contributing to OlistHelper

OlistHelper is an open-source project, and we welcome contributions from anyone who is interested in helping improve the app. Whether you're a developer, a translator, or a documentation writer, there are many ways to get involved.

### Getting Started

If you're interested in contributing code to OlistHelper, you'll need to follow these steps:

### Run

Fork the repository and install [Flutter](https://flutter.dev).

After you have installed [Flutter](https://flutter.dev), then you can start this app by typing the following commands:

```shell
flutter pub get
dart run build_runner build
flutter run
```

### Translation

You can help translating this app to other languages!

1. Fork this repository
2. Choose one
   - Add missing translations in existing languages: Only update `_missing_translations_<locale>.json` in [lib/i18n](https://github.com/yeqiu600/Olisthelper/tree/master/lib/i18n)
   - Fix existing translations: Update `strings_<locale>.i18n.json` in [lib/i18n](https://github.com/yeqiu600/Olisthelper/tree/master/lib/i18n)
   - Add new languages: Create a new file, see also: [locale codes](https://saimana.com/list-of-country-locale-code/).
3. Optional: Re-run this app
   1. Make sure you have [run](#run) this app once.
   2. Update translations via `dart run build_runner build`
   3. Run app via `flutter run`
4. Open a pull request

#### _Take note:_ Fields decorated with `@` are not meant to be translated, they are not used in the app in any way, being merely informative text about the file or to give context to the translator.

### Contributing Guidelines

Before you submit a pull request to OlistHelper, please ensure that you have followed these guidelines:

- Code should be well-documented and formatted according to the [Dart Style Guide](https://dart.dev/guides/language/effective-dart/style).
- All changes should be covered by tests.
- Commits should be well-written and descriptive, with a clear summary of the changes made and any relevant context.
- Pull requests should target the `master` branch and include a clear summary of the changes made.

### Bug Reports and Feature Requests

If you encounter a bug in OlistHelper or have a feature request, please submit an issue to the [issue tracker](https://github.com/yeqiu600/Olisthelper/issues). Please be sure to provide a clear description of the problem or feature request, along with any relevant context or steps to reproduce the issue.
