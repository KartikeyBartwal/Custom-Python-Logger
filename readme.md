# Custom Python Logger

A lightweight and easy-to-use Python logging module that automatically manages log files, formats messages with timestamps, and logs to both a file and console.

## Features
- **Automatic Log File Creation**: Creates a new log file for each day.
- **Structured Logging**: Logs are formatted with timestamps.
- **Dual Logging**: Logs are written to both a file (all levels) and the console (INFO and above).
- **Customizable**: Supports log directory and logger name customization.
- **Prevents Duplicate Handlers**: Ensures multiple handlers are not added.

## Installation
No external dependencies required. Just copy and use `logger.py` in your project.

## Usage
```python
from logger import setup_logger

logger = setup_logger()
logger.debug("This is a debug message.")
logger.info("This is an info message.")
logger.warning("This is a warning message.")
logger.error("This is an error message.")
logger.critical("This is a critical message.")
```

## File Structure
```
Custom-Python-Logger/
│── logger.py
│── README.md
└── logs/  # Log files are automatically stored here
```

