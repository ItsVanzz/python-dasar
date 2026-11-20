# Python Dasar

A collection of code examples and study notes covering Python fundamentals, from basic syntax to object-oriented programming, modules, and packages. Most examples live in `main.py`, with comments in Indonesian at every step.

## Topics

`main.py` is organized in order:

1. Program structure, comments, indentation, and input and output
2. Variables, data types, and type conversion
3. Constants and constants in a module
4. Operators: arithmetic, comparison, logical, assignment, membership, and identity
5. Control flow: `if`, `elif`, `else`, `for`, `while`, `break`, `continue`
6. Functions: parameters, default values, return values, `*args`, `**kwargs`
7. Lists, tuples, and sets
8. Dictionaries, including nested dictionaries
9. OOP: classes and objects, attributes and methods, encapsulation, inheritance, polymorphism, and abstraction
10. Exception handling: `try`, `except`, `else`, `finally`, `raise`
11. File handling: read, write, append, and the `with` statement
12. Modules and packages, including the standard library (`math`, `os`, `datetime`)

## Project Structure

```
python-dasar/
├── main.py            # main code examples
├── constants.py       # module with constants (PI, GRAVITY, MAX_RETRY)
├── matematika.py      # module with tambah() and kali()
├── my_package/        # example package
│   ├── __init__.py
│   ├── operasi.py     # kurang()
│   └── geometri.py    # luas_persegi()
├── data.txt           # sample file used by the file handling examples
├── contoh.txt         # sample file used by the file handling examples
├── screenshot/        # tutorial screenshots (tutorial-1.png to tutorial-18.png)
├── requirements.txt   # dependency list (empty, standard library only)
├── .gitignore
└── README.md
```

## Requirements

- Python 3.10 or newer. The project was developed with Python 3.14.
- No extra packages. See `requirements.txt`.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/ItsVanzz/python-dasar.git
cd python-dasar
```

Create and activate a virtual environment (optional, but recommended).

Bash or Zsh:

```bash
python -m venv venv
source venv/bin/activate
```

Fish:

```fish
python -m venv venv
source venv/bin/activate.fish
```

Windows (PowerShell):

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
```

Install dependencies, then run:

```bash
pip install -r requirements.txt
python main.py
```

Run the script from the project folder. The module and package examples import `constants`, `matematika`, and `my_package` from the current directory, and the file handling examples read and write `data.txt` and `contoh.txt` there.

To leave the virtual environment, run `deactivate`.

## Notes

- Some lines in `main.py` are commented out on purpose because they raise errors (for example, reassigning a constant, using a private attribute directly, or creating an object from an abstract class). Remove the leading `#` to see the error message.
- The file handling examples overwrite `data.txt` and `contoh.txt` each time you run them.
- The `venv/` and `__pycache__/` folders are not committed. Both are listed in `.gitignore`.

## Author

[ItsVanzz](https://github.com/ItsVanzz)
