# AccelerateDevGHCopilot

Python console application for basic library operations, including patron management, book loans, and JSON-based data persistence.

## Requirements

- Python 3.10+
- pip (optional, only if you want to install test tooling)

## Project Structure

- `library/application_core/`: Domain entities, enums, interfaces, and services
- `library/console/`: Console UI and app entry point
- `library/infrastructure/`: JSON repositories and local data files
- `library/tests/`: Unit tests for service logic

## Run the App

From the repository root:

```bash
cd library
python -m console.main
```

## Run Tests

From the repository root:

```bash
cd library
python -m unittest discover -s tests -p "test_*.py"
```

## Notes

- Data is stored in `library/infrastructure/Json/`.
- This repository root README is intended as a quick start. Additional module details are in `library/readme.md`.
