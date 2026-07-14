# File Backup Automation

Python automation script for creating directory backups and logging backup processes with timestamps.

---

## Features

* Automated directory backups
* Creates timestamped backup folders
* Copies configured files and directories
* Logs backup events with timestamps
* Basic error handling
* Simple and lightweight automation workflow

---

## Project Status

✅ Completed

The backup automation script is fully functional.

Current functionality includes:

* Directory backup creation
* Backup folder organization
* Process logging
* Error handling for file operations

---

## Getting Started

### Requirements

* Python 3.x installed

---

## Usage

1. Configure the source and backup directories in `main.py`.

Example:

```python
source = r"C:\Source" # Change here
destination = r"D:\Backups" # Change here
```

2. Run the script:

```bash
python main.py
```

---

## Backup Process

The script performs the following steps:

1. Loads the configured source and backup paths
2. Creates a new timestamped backup folder
3. Copies configured directories to the backup location
4. Logs the backup process
5. Handles possible file operation errors