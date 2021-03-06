[![PyPI version](https://badge.fury.io/py/passflip.svg)](https://badge.fury.io/py/passflip) [![PyPI](https://img.shields.io/pypi/dm/passflip.svg)]()

# passflip

An easy-to-use command-line tool that lets you secure your passwords.

* Use a single master password to generate unique passwords for different websites.

* Generated passwords are 56 characters long by default, making them very time-consuming for a computer to crack.

## Installation

Installable via pip:

`sudo pip install passflip`

## Usage

1. Start the program by running `passflip` as a command.

2. Enter your master password (e.g. `byxor_rocks_1337`)

3. Enter your salt (e.g. `twitter`)

The program will then return your unique secured password for twitter.

## Tips

* You can enable "check" mode with the `-c` or `--check` option. This requires input to be entered twice.

* You can limit the length of a password using the `-l <number>` option.

## Contribution

See anything you want to improve? Want to add any features? Make a pull request and I'll be happy to accept it if it's good.
