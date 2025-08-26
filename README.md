## Roman Numerals:

[Roman Numerals Repo](https://github.com/sigreipel/RomanNumerals)

_Roman Numerals Converter_ is a Python-based utility designed to convert between Arabic numerals (standard integers) and Roman numerals. It includes both the core conversion logic `RomanNumerals.py` and a suite of tests `test_roman_numerals.py` to verify correctness and robustness. 

<ins>Features:</ins>
Bidirectional Conversion

- Supports converting integers to Roman numerals and vice versa (also tested via unit tests in `test_roman_numerals.py` 

Modular Design

- Core conversion functions are encapsulated in `RomanNumerals.py`, allowing for reuse and extension.

Test Suite

- Automated tests ensure the conversion logic handles typical cases, edge cases, and invalid inputs reliably. 

<ins>TechStack:</ins>

Language: Python (100%) 

Structure:

- `RomanNumerals.py`: Conversion logic
- `test_roman_numerals.py`: Unit tests

<ins>Future Improvements</ins>

- Add input validation and error handling—for example, rejecting zero, negatives, or values above the standard Roman numeral range.
- Extend support for subtractive notation beyond the classical range (e.g., overline notation for values > 3,999).
- Develop a CLI (command-line interface) with arguments to allow users to easily convert values via the terminal.
- Incorporate a graphical user interface (GUI) or web front-end for improved user interaction.
- Expand the test suite to cover edge cases more comprehensively, including invalid strings and formatting variants.
