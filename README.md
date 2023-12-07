# PCAN Communication

This repository contains timerread and timerwrite scripts for PCAN IPEH-002022-336673 connectors. These scripts are designed to read and write timer settings for these connectors, allowing users to manage and control timing functionalities effectively.

## Getting Started

These scripts are written in [Python](https://www.python.org/) and are compatible with PCAN IPEH-002022-336673 connectors.

### Prerequisites

- **Python**: Ensure that Python is installed on your system. The scripts are written in Python 3.x.

- **PCAN Tools**: You need the PCAN tools or drivers installed on your system to interact with the PCAN connectors. Make sure the necessary drivers are correctly installed.

## Usage

### `timerwrite.py`

The `timerwrite.py` script allows you to write data and timer settings and send it through PCAN IPEH-002022-336673 connectors.


### `timerread.py`

The `timerread.py` script allows you to retrieve timer data from sender through PCAN IPEH-002022-336673 connectors.

Usage:
```bash
python timerwrite.py
```bash
python timerread.py
