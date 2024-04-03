# UTF-8 Validation

This project focuses on implementing a method in Python to determine whether a given dataset represents a valid UTF-8 encoding. The task involves utilizing knowledge of bitwise operations, understanding the UTF-8 encoding scheme, and Python programming skills.

## Table of Contents

- [General Information](#general-information)
- [Concepts Needed](#concepts-needed)
- [Additional Resources](#additional-resources)
- [Requirements](#requirements)
- [Tasks](#tasks)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## General Information

The **UTF-8 Validation** project aims to validate whether a given dataset adheres to the UTF-8 encoding standards. UTF-8 is a widely used encoding scheme to represent characters in Unicode. This project provides an opportunity to apply bitwise operations, logical reasoning, and Python programming skills to analyze and validate data integrity.

## Concepts Needed

To effectively tackle this project, it is essential to have an understanding of the following concepts:

- Bitwise Operations in Python: Familiarity with manipulating bits using operations like AND, OR, XOR, shifts, etc.
- UTF-8 Encoding Scheme: Understanding the rules and patterns of UTF-8 encoding.
- Data Representation: Knowledge of representing and working with data at the byte level.
- List Manipulation in Python: Ability to iterate through lists and access list elements.
- Boolean Logic: Applying logical operations to make decisions within the program.

## Additional Resources

- [UTF-8 Wikipedia](https://en.wikipedia.org/wiki/UTF-8)
- [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)
- [Python Bitwise Operators](https://realpython.com/python-bitwise-operators/)
- [Python Lists](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)

## Requirements

- **Allowed editors**: vi, vim, emacs
- **Interpreted/compiled on**: Ubuntu 20.04 LTS using python3 (version 3.4.3)
- **Code style**: PEP 8
- **Executable files**
- **README.md**: Mandatory, providing essential project information and instructions.

## Tasks

### 0. UTF-8 Validation

Write a method `validUTF8(data)` that determines if a given dataset represents a valid UTF-8 encoding.

- **Prototype**: `def validUTF8(data)`
- **Return**: `True` if data is a valid UTF-8 encoding, else return `False`.
- The data set can contain multiple characters.
- Each integer represents 1 byte of data, therefore, you only need to handle the 8 least significant bits of each integer.

## How to Use

To use the `validUTF8` method, import it into your Python script and pass the data set as a list of integers. The method will return `True` if the data is a valid UTF-8 encoding, otherwise `False`.

```python
from 0-validate_utf8 import validUTF8

data = [65, 195, 130, 226, 152, 131]  # Valid UTF-8 encoding
print(validUTF8(data))  # Output: True
```

## Contributing

Contributions are welcome! Feel free to open an issue or create a pull request with suggestions, improvements, or new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
