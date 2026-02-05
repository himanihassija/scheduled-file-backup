# Daily Screenshot Backup

A Python automation script that automatically backs up screenshots into date-based folders at a scheduled time each day.

## Features
- Automatically copies screenshots from a source directory
- Creates backups organized by date
- Runs on a daily schedule
- Prevents overwriting existing backups
- Simple and lightweight automation script

## Technologies Used
- Python
- os
- shutil
- datetime
- schedule

## How It Works
The script copies the entire screenshots folder into a backup directory named with the current date. If a backup for the day already exists, it is skipped to prevent duplication.

## Setup Instructions
1. Clone the repository
2. Update the source and destination paths in the script
3. Install required dependency:
   pip install schedule
4. Run the script and keep it running in the background

## Use Case
This project is useful for automating daily file backups and demonstrates real-world Python automation and task scheduling.

## Future Improvements
- Incremental backups
- Timestamp-based backups
- Integration with cloud storage
- Running via system task scheduler

