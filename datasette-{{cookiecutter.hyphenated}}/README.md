# datasette-{{ cookiecutter.hyphenated }}

[![PyPI](https://img.shields.io/pypi/v/datasette-{{ cookiecutter.hyphenated }}.svg)](https://pypi.org/project/datasette-{{ cookiecutter.hyphenated }}/){% if cookiecutter.github_username %}
[![Changelog](https://img.shields.io/github/v/release/{{ cookiecutter.github_username }}/datasette-{{ cookiecutter.hyphenated }}?include_prereleases&label=changelog)](https://github.com/{{ cookiecutter.github_username }}/datasette-{{ cookiecutter.hyphenated }}/releases)
[![Tests](https://github.com/{{ cookiecutter.github_username }}/datasette-{{ cookiecutter.hyphenated }}/workflows/Test/badge.svg)](https://github.com/{{ cookiecutter.github_username }}/datasette-{{ cookiecutter.hyphenated }}/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/{{ cookiecutter.github_username }}/datasette-{{ cookiecutter.hyphenated }}/blob/main/LICENSE){% endif %}

{{ cookiecutter.description or "" }}

## Installation

Install this plugin in the same environment as Datasette.

    $ datasette install datasette-{{ cookiecutter.hyphenated }}

## Usage

Usage instructions go here.

## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:

    cd datasette-{{ cookiecutter.hyphenated }}
    python3 -mvenv venv
    source venv/bin/activate

Or if you are using `pipenv`:

    pipenv shell

Now install the dependencies and test dependencies:

    pip install -e '.[test]'

To run the tests:

    pytest
