# Project structure

The repository contains the unpacked **CinMax 2.0.1** Flutter/Android project.

```text
.
├── android/       Android host project and Gradle configuration
├── assets/        Fonts, icons, images, and animations
├── archives/      Original ZIP and TAR.GZ distribution packages
├── docs/          Repository documentation
├── w/             Web entry-point assets
├── app-ads.txt    App-ads configuration
├── app_control.json
├── pubspec.yaml   Flutter package metadata and dependencies
├── sources_config.json
└── update.json
```

Generated build output, Kotlin compiler caches, crash logs, replay logs, and IDE metadata were removed from version control and are covered by `.gitignore`.

> Note: the supplied package does not contain a `lib/` directory. The README describes a Dart source layout, but those source files were not present in the uploaded archives.
