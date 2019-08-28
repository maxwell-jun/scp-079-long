# SCP-079-LONG

This bot is used to auto delete super long messages.

## How to use

See [this article](https://scp-079.org/long/).

## To Do List

- [ ] Basic functions

## Requirements

- Python 3.6 or higher
- Ubuntu: `sudo apt update && sudo apt install opencc -y`
- pip: `pip install -r requirements.txt` or `pip install -U APScheduler OpenCC pyAesCrypt python-telegram-bot[socks]==12.0.0b1`

## Files

- plugins
    - functions
        - `channel.py` : Functions about channel
        - `etc.py` : Miscellaneous
        - `file.py` : Save files
        - `filters.py` : Some filters
        - `fix.py` : Show steps to fix an error
        - `group.py` : Functions about group
        - `ids.py` : Modify id lists
        - `receive.py` : Receive data from exchange channel
        - `telegram.py` : Some telegram functions
        - `tests.py` : Some test functions
        - `timers.py` : Timer functions
        - `user.py` : Functions about user and channel object
    - handlers
        - `command.py` : Handle commands
        - `error.py` : Handle errors
        - `message.py`: Handle messages
    - `glovar.py` : Global variables
- `.gitignore` : Ignore
- `config.ini.example` -> `config.ini` : Configuration
- `LICENSE` : GPLv3
- `main.py` : Start here
- `README.md` : This file
- `requirements.txt` : Managed by pip

## Contribute

Welcome to make this project even better. You can submit merge requests, or report issues.

## License

Licensed under the terms of the [GNU General Public License v3](LICENSE).