![CI](https://github.com/MgSuper/startup_launch/actions/workflows/flutter_ci.yml/badge.svg)

Use this repository as a GitHub Template to launch new Flutter startups fast.

# Startup Launch

A production-ready Flutter starter template built for speed, scalability, and rapid startup launches.

Create new app ideas in minutes — not days.

---

## Features

### Core Architecture

- Clean scalable structure
- Dependency Injection (`get_it`)
- State Management (`flutter_bloc`)
- Navigation (`go_router`)
- Feature-first ready architecture

### UI System

- Material 3
- Light / Dark / System theme
- Runtime theme switching
- Design token structure
- Responsive-ready foundation

### Localization

- Multi-language support
- English 🇺🇸
- Vietnamese 🇻🇳
- Japanese 🇯🇵
- Thai 🇹🇭
- Runtime language switching
- Persist selected language

### Networking

- `dio` API client
- Auth interceptor
- Connectivity guard
- Refresh token ready
- Error handling foundation

### Productivity

- Android flavors (`dev`, `staging`, `prod`)
- iOS schemes (`dev`, `staging`, `prod`)
- Environment banners
- Different app icons per flavor
- Rename app script ready

### Quality

- GitHub Actions CI
- Static analysis
- Unit test ready

---

## Tech Stack

- Flutter
- Dart
- flutter_bloc
- get_it
- go_router
- dio
- shared_preferences
- flutter_secure_storage
- intl

---

## Getting Started

### Clone Project

```bash
git clone https://github.com/YOUR_USERNAME/startup_launch.git
cd startup_launch
flutter pub get
```

---

## Run Flavors

### Development

```bash
flutter run --flavor dev -t lib/main_dev.dart
```

### Staging

```bash
flutter run --flavor staging -t lib/main_staging.dart
```

### Production

```bash
flutter run --flavor prod -t lib/main_prod.dart
```

---

## One-command startup generator

```bash
sh scripts/create_startup.sh "My App" com.company.myapp
flutter run --flavor dev -t lib/main_dev.dart
```

---

## Generate Flavor Icons

```bash
dart run flutter_launcher_icons -f flutter_launcher_icons-dev.yaml
dart run flutter_launcher_icons -f flutter_launcher_icons-staging.yaml
dart run flutter_launcher_icons -f flutter_launcher_icons-prod.yaml
```

---

## Run Tests

```bash
flutter test
```

---

## Project Structure

```text
lib/
├── app/
│   ├── localization/
│   ├── theme/
│   ├── router.dart
│   └── app.dart
│
├── core/
│   ├── config/
│   ├── di/
│   ├── network/
│   ├── extensions/
│   ├── error/
|   ├── state/
│   ├── storage/
|   ├── utils/
│   ├── widgets/
├── features/
│   └── sample_feature/
│
├── main_common.dart
├── main_dev.dart
├── main_staging.dart
└── main_prod.dart
```

---

## Why This Template Exists

Most Flutter projects waste time rebuilding:

- themes
- routing
- localization
- networking
- startup configs
- flavors
- CI

This template solves it once.

Ship ideas faster.

---

## Roadmap

- [ ] Firebase flavor setup
- [ ] Supabase starter option
- [ ] Fastlane deployment
- [ ] Crashlytics integration
- [ ] Analytics module

---

## License

MIT

---

## Support

If this project helps you, give it a star.
