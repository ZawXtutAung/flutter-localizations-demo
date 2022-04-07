# flutter_localization

A new Flutter project.

## Getting Started

## l10.yaml create

```yaml
arb-dir: lib/l10n
template-arb-file: app_en.arb
output-localization-file: app_localizations.dart
```

## run flutter project

```dart
     localizationsDelegates: const [
         GlobalMaterialLocalizations.delegate,
         GlobalWidgetsLocalizations.delegate,
         GlobalCupertinoLocalizations.delegate,
       ],
       supportedLocales: const [
         Locale('en', ''),
         Locale('my', ''),
       ],

```

## after

```dart
  localizationsDelegates: AppLocalizations.localizationsDelegates,
      supportedLocales: AppLocalizations.supportedLocales,
```

need Extract Widget

```dart
  home: MyHome(),
```

- [Useful Flutter samples](https://docs.flutter.dev/development/accessibility-and-localization/internationalization)
# flutter-localizations-demo
