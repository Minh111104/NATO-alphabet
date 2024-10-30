# NATO Phonetic Alphabet Converter

This project is a simple Python program that converts user-input words into NATO phonetic alphabet codes. It uses the `pandas` library to load a CSV file containing the NATO phonetic alphabet, then creates a dictionary for mapping each letter to its respective code. The user can input any word, and the program will output the corresponding phonetic code words.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Features

- **Phonetic Code Conversion**: Converts user-input words into NATO phonetic codes.
- **Error Handling**: Prompts the user to re-enter input if it includes non-alphabet characters.
- **Dictionary Generation**: Uses dictionary comprehension to map letters to phonetic codes.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/nato_phonetic_converter.git
    ```

2. Navigate to the project directory:
    ```bash
    cd nato_phonetic_converter
    ```

3. Ensure Python 3.x and `pandas` are installed:
    ```bash
    pip install pandas
    ```

4. Place the `nato_phonetic_alphabet.csv` file in the project directory. The file should contain two columns: `letter` and `code`, representing each letter and its phonetic code word.

## Usage

1. Run the script:
    ```bash
    python main.py
    ```

2. Enter a word when prompted. The program will display the phonetic code words for each letter in the word.

3. If non-alphabet characters are entered, the program will prompt the user to enter a valid word.
