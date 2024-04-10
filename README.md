# Img2Desmos

This is a simple python script that converts an image to the bezier curves which can be plotted on desmos.

## Requirements

- Python 3.11
- Poetry
- [Optional] Chafa (for previewing the images in terminal)

## Installation

```bash
poetry install
```

## Usage

```bash
poetry run python img2desmos.py --help
╭─ Arguments ─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╮
│ *    img      TEXT  Path to the image to convert into graph [default: None] [required]                                                                                                  │
╰─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╯
╭─ Options ───────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╮
│ --output   -o      TEXT     Output formulas file path [default: None]                                                                                                                   │
│ --preview  -p               Preview the img in a window (chafa required)                                                                                                                │
│ --upper            INTEGER  Upper threshold for the edge detection [default: 200]                                                                                                       │
│ --lower            INTEGER  Lower threshold for the edge detection [default: 100]                                                                                                       │
│ --help                      Show this message and exit.                                                                                                                                 │
╰─────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────╯

```
