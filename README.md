# pycodeComply

## Overview

`pycodeComply` is a Python script designed to ensure Pycodestyle (formerly known as PEP8) compliance for Python code files. Pycodestyle is a style guide for writing clean, readable, and consistent Python code.

## Features

- Automatically formats Python code files to comply with Pycodestyle guidelines.
- Supports the validation and correction of indentation, spacing, line lengths, and other Pycodestyle-related issues.
- Provides detailed error messages and suggestions for code improvements.
- Option to format multiple files or directories at once.
- Option to exclude specific files or directories from formatting.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Nmcleon/pycodeComply.git
   ```

2. Navigate to the project directory:

   ```bash
   cd pycodeComply
   ```

3. Make the script executable using chmod +x:

'''bash
chmod +x pycodeComply.sh
'''

4. Install the required dependencies (e.g., `autopep8`):

   ```bash
   pip install autopep8
   ```

## Usage

To format a single Python file, run the script with the following command:

```bash
./pycodeComply.sh your_file.py
```

To format all Python files in a directory and its subdirectories, use the following command:

```bash
./pycodeComply.sh your_directory/
```

## Configuration

You can configure the script by editing the `pycodeComply.sh` script. Here are some options you can customize:

- `IGNORED_FILES`: Add file names or patterns to exclude specific files from formatting.
- `IGNORED_DIRECTORIES`: Add directory names to exclude specific directories from formatting.
- Adjust any other Pycodestyle-related options according to your preferences.

## Examples

### Format a Single File

```bash
./pycodeComply.sh my_script.py
```

### Format All Python Files in a Directory

```bash
./pycodeComply.sh my_project/
```

### Exclude Specific Files and Directories

You can modify the `IGNORED_FILES` and `IGNORED_DIRECTORIES` arrays in the `pycodeComply.sh` script to exclude specific files or directories from formatting.

## Contributing

If you encounter any issues or have suggestions for improvements, please feel free to open an issue on our [GitHub repository](https://github.com/Nmcleon/pycodeComply). I welcome contributions from the community!

---

Still under development :smile_cat:
