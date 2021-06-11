# datasette-plugin-template-demo

[![PyPI](https://img.shields.io/pypi/v/datasette-plugin-template-demo.svg)](https://pypi.org/project/datasette-plugin-template-demo/)
[![Changelog](https://img.shields.io/github/v/release/simonw/datasette-plugin-template-demo?include_prereleases&label=changelog)](https://github.com/simonw/datasette-plugin-template-demo/releases)
[![Tests](https://github.com/simonw/datasette-plugin-template-demo/workflows/Test/badge.svg)](https://github.com/simonw/datasette-plugin-template-demo/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/simonw/datasette-plugin-template-demo/blob/main/LICENSE)

Demonstrating https://github.com/simonw/datasette-plugin

## Installation

Install this plugin in the same environment as Datasette.

    $ datasette install datasette-plugin-template-demo

## Usage

Usage instructions go here.

## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:

    cd datasette-plugin-template-demo
    python3 -mvenv venv
    source venv/bin/activate

Or if you are using `pipenv`:

    pipenv shell

Now install the dependencies and test dependencies:

    pip install -e '.[test]'

To run the tests:

    pytest
