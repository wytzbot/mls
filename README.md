# ToluNote - Multi-Platform Native Notepad App

A production-quality, offline-first notepad application with support for Web, iOS, Android, and Desktop platforms. Built with modern native technologies and synchronized across all devices.

## ✨ Features

- **📱 Offline-First Architecture**: All data stored locally, full functionality without internet
- **🌐 Cross-Platform**: Web (React), iOS (SwiftUI), Android (Kotlin), Desktop (Electron)
- **📝 Rich Text Editing**: Full markdown support, code blocks, formatting
- **📂 Categories & Folders**: Hierarchical note organization
- **🔍 Full-Text Search**: Fast, instant search across all notes
- **🏷️ Tags**: Flexible tagging and filtering system
- **🌙 Dark/Light Mode**: System-aware theme support
- **🔒 Data Encryption**: AES-256 encryption at rest
- **⚡ Performance**: Optimized for speed, minimal memory footprint
- **☁️ Optional Cloud Sync**: Built-in sync architecture (Firebase-ready)
- **📊 Analytics Ready**: Built-in telemetry framework
- **🎨 Native UI/UX**: Platform-specific design patterns

## Project Structure

```
tolunote01/
├── shared/                    # Shared models and utilities
│   ├── models/               # Data models (TypeScript)
│   └── constants/            # App constants
├── web/                       # React web application
│   ├── src/
│   ├── public/
│   └── package.json
├── mobile/
│   ├── ios/                  # SwiftUI iOS app
│   └── android/              # Kotlin Android app
├── desktop/                  # Electron desktop app
└── docs/                     # Documentation
```

## Quick Start

### Web Application
```bash
cd web
npm install
npm start
```

### iOS
```bash
cd mobile/ios
pod install
open ToluNote.xcworkspace
```

### Android
```bash
cd mobile/android
./gradlew build
```

### Desktop
```bash
cd desktop
npm install
npm start
```

## Technology Stack

### Web
- React 18+, Redux Toolkit, TypeScript, SQLite, TailwindCSS

### iOS
- SwiftUI, CoreData, Combine, MVVM

### Android
- Kotlin, Jetpack Compose, Room Database, Kotlin Flow

### Desktop
- Electron, React, SQLite, Node.js

## Architecture

- **Offline-First**: All data stored locally
- **Encrypted Storage**: AES-256 encryption
- **Optional Cloud Sync**: Firebase-ready backend
- **Cross-Platform**: Shared data models

## License

MIT License

---

**Built with ❤️ for note-taking across all platforms**
