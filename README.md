# FML: Fibonacci Markup Language

A humorous markup language where indentation levels must follow the Fibonacci sequence (0, 1, 1, 2, 3, 5, 8, 13, 21, etc.) — or else!

## What is FML?

FML is a markup language that enforces mathematical harmony in your documents by requiring all indentation levels to follow the Fibonacci sequence. If your indentation doesn't match a Fibonacci number, the parser will reject it with a snarky error message.

## Example

```fml
This line has 0 spaces of indentation
 This line has 1 space of indentation
 This line also has 1 space of indentation
  This line has 2 spaces of indentation
   This line has 3 spaces of indentation
     This line has 5 spaces of indentation
        This line has 8 spaces of indentation
             This line has 13 spaces of indentation
                          This line has 21 spaces of indentation
```

## Features

- Enforces Fibonacci sequence indentation (0, 1, 1, 2, 3, 5, 8, 13, 21, etc.)
- Converts valid FML documents to HTML or other formats
- Provides humorous error messages for non-compliant indentation
- Includes a CLI tool for processing FML files

## Installation

```
pip install fml-markup
```

## Usage

```
fml convert input.fml output.html
```

## Why FML?

Because regular markup languages are too predictable. Embrace the mathematical chaos!
