# PyDoor

Encrypted Backdoor/Reverse Shell/RAT written in Python.

## Reposity is archived!

This repository was archived because no real development has been happening for a long time. PyDoor was a great experience for learning python. It's quite outdated now and there are infinite ways I would improve on the project if I made it today, but everybody starts somewhere right.

## Cross-Platform Features

* Multi-client support
* TLSv1.3 Encryption
* Real-time Shell
* Python Interpreter
* File Transfer
* Copy/Paste Clipboard
* Capture Webcam
* Take Screenshots
* File Downloader
* Background Tasks
* Restart Sessions

## Windows Specific Features

* Lock Client Machines

Windows Specific Features can be done manually on other OS's

## Feature Roadmap

* Threaded Shell
* Broadcasting commands
* Keylogger
* Adding Client to Startup (Windows)

## Installation

You will need:

* [Python 3.10+](https://www.python.org/downloads)

1. Download the repository via github or git eg. `git clone https://github.com/tidely/PyDoor`
2. Install the required modules by running `python3 -m pip install -r requirements.txt`

## Usage

Run server:
`python3 server.py`

Run client:
`python3 client.py`

## FAQ

### Setup Remote Server

Read [setup.md](./setup.md#server-setup)

### Connect to Remote Server

Read [setup.md](./setup.md#client-setup)

### See available commands

type `help`

### Run commands as root

`echo SUDOPASSWORD | sudo -S COMMAND`

### See Importable packages in python interpreter

`help("modules")`

## Help

If you need any help at all, feel free to post a "help" issue.

## Contributing

Contributing is encouraged and will help make a better program. Please refer to [this](https://gist.github.com/MarcDiethelm/7303312) before contributing.

## Disclaimer

For educational purposes only! I am not responsible for anything you do with it.

## License

[License](./LICENSE)

Project heavily inspired by [buckyroberts/Turtle](https://github.com/buckyroberts/Turtle) and [xp4xbox/Python-Backdoor](https://github.com/xp4xbox/Python-Backdoor)
