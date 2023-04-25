# LexiScan


**Language Detection Program**

This program allows you to detect the language of any text input. It uses the langdetect package, which requires large portions of text to make accurate predictions.

**Installation**

To use this program, you will need to have Python installed on your machine. You can download and install the latest version of Python from the official website: https://www.python.org/downloads/

Once you have Python installed, you can install the required packages by running the following command in your terminal:

pip install langdetect

**Usage**

To use the program, simply run the main.py file in your terminal. The program will prompt you to enter some text to detect its language.

The program will then use the langdetect package to detect the language of the text input. The detected language will be printed to the console, along with the input text.

Please note that the langdetect package uses a non-deterministic approach, which means you may get different results for the same text sample. To make the results deterministic, the program sets the seed of the DetectorFactory to 0.

**Contributions**

Contributions are always welcome! If you find a bug or have a suggestion for improvement, please feel free to create an issue or submit a pull request.

**License**

This program is licensed under the MIT License. Feel free to use and modify this program for your own purposes.
