# Regex Matcher in C

A simple regex matcher implemented in C, based on the approach described in [A Regular Expression Matcher](https://www.cs.princeton.edu/courses/archive/spr09/cos333/beautiful.html). This project provides a basic implementation of regular expression matching functionality.

## Features

- Supports basic regex patterns such as:
  - `.`: Matches any single character.
  - `*`: Matches zero or more of the preceding character.
  - `^`: Matches the start of a string.
  - `$`: Matches the end of a string.
- Matches strings against regex patterns using recursive algorithms.
