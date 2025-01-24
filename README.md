# husky-flutter-scripts

This repository contains shell scripts for validating Git commit messages and restricting branch operations for flutter projects.

## Scripts

1. `commit-msg`: Validates commit messages against a standard convention.
2. `pre-commit`: Prevents direct commits to prohibited branches.
3. `pre-push`: Runs Dart formatter and fixers on the project.

## Usage
To use these scripts with your Flutter project, you need to install the `husky` package and configure it to run the scripts at the appropriate Git hooks.

### Installation

1. Add `husky` to your `dev_dependencies` in `pubspec.yaml`:

    `dart pub add --dev husky`

2. Enable Git hooks in your project:

    `dart run husky install`

### Adding Scripts to Your Project

Copy the `commit-msg`, `pre-commit`, and `pre-push` files from this repository to the `.husky` directory in your project:

```sh
cp /path/to/husky-flutter-scripts/commit-msg .husky/
cp /path/to/husky-flutter-scripts/pre-commit .husky/
cp /path/to/husky-flutter-scripts/pre-push .husky/
```

### More Information

For more details on how to use `husky` with Flutter, visit the [husky package page on pub.dev](https://pub.dev/packages/husky).