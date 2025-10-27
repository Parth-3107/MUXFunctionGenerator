# Python Multiplexer Function Generator

This project implements an 8:1 multiplexer as a function generator capable of converting any given Sum of Products (SOP) or Product of Sums (POS) function into a suitable simplified expression. 

## Project Structure

```
python-mux-function-generator
├── src
│   ├── muxgen
│   │   ├── __init__.py
│   │   ├── main.py
│   │   ├── mux.py
│   │   ├── parser.py
│   │   ├── simplifier.py
│   │   └── utils.py
│   └── cli.py
├── tests
│   ├── test_mux.py
│   ├── test_parser.py
│   └── test_simplifier.py
├── pyproject.toml
├── requirements.txt
├── README.md
└── LICENSE
```

## Features

- **Multiplexer Logic**: Implements the behavior of an 8:1 multiplexer.
- **Expression Parsing**: Parses SOP and POS expressions for processing.
- **Expression Simplification**: Simplifies logical expressions to their simplest forms.
- **Command-Line Interface**: Provides a user-friendly CLI for interaction.

## Installation

To install the required dependencies, run:

```
pip install -r requirements.txt
```

## Usage

To run the application, use the command line interface:

```
python src/cli.py
```

Follow the prompts to input your SOP or POS expressions and receive the simplified output.

## Testing

To run the tests, navigate to the `tests` directory and execute:

```
pytest
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.
