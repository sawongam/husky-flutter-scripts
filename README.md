# husky-flutter-scripts

This repository contains shell scripts for validating Git commit messages and restricting branch operations.

## Scripts

1. `commit_msg_validator.sh`: Validates commit messages against a standard convention.
2. `branch_restrictions.sh`: Prevents direct commits to prohibited branches.
3. `format_and_fix.sh`: Runs Dart formatter and fixers on the project.

## Usage

To use these scripts, place them in your Git repository and run them as needed.

## Configuration

- `commit_msg_validator.sh`: No configuration required.
- `branch_restrictions.sh`:
  - Modify the `PROHIBITED_BRANCHES` array in the script to add/remove restricted branches.
- `format_and_fix.sh`: No additional configuration needed.

## License

This project is open-source and free to use under the MIT License.
