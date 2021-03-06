# Rewind

![Badge for GitHub repo top language](https://img.shields.io/github/languages/top/legionxvx/rewind?style=flat&logo=appveyor) 
![Badge for GitHub last commit](https://img.shields.io/github/last-commit/legionxvx/rewind?style=flat&logo=appveyor)
![Tests](https://github.com/legionxvx/rewind/actions/workflows/test.yaml/badge.svg)

Check out the badges hosted by [shields.io](https://shields.io/).


## Description 
Rewind is a wrapper around the Streamlink library to allow for custom plugins 
that are 'past broadcast' aware (like Twitch VODs)

### Currently supported plugins:
- Twitch

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [Tests](#tests)
* [License](#license)

# Installation
You will need [poetry](https://python-poetry.org/) to install a development 
environment. 

You probably do not `poetry` if you don't intend on development, but I've 
never tried it without it :)

## Easiest Method (Not Intended for Development)
I plan on publishing this on PyPI when I get around to it (and can land on a 
non-conflicting name), until then —
```bash
$ git checkout https://github.com/legionxvx/rewind.git
$ cd rewind
$ pip install . --user
```

## For Everyone Else (Intended for Developers or Others)
```bash
$ git checkout https://github.com/legionxvx/rewind.git
$ cd rewind
$ poetry install
$ poetry run python -m rewind
```

# Usage
Because he never streams...
```bash
$ rewind www.twitch.tv/clinststevens best --twitch-check-vods
```

# Tests
Tests are just stubs right now, and have very poor coverage, but I'll fix that 
in the future...
```bash
$ poetry run pytest
```

# License
GNU GPLv3

# Contributing
Currently there is no formal method of contribution. Obviously PRs are welcome
however, they must have tests associated with them!

## Questions?
For any questions, please contact me with the information below:

GitHub: [@legionxvx](https://api.github.com/users/legionxvx)
