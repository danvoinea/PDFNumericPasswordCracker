# PDF Numeric Password Cracker
Technique used - Brute Force

## Requirements
Requires Python 3.* and pikepdf
```sh
pip install pikepdf
``` 
## Usage
```sh
python crack.py PATH_TO_PDF_FILE [-m MIN_DIGITS] [-n MAX_DIGITS]
``` 

Example - If the password is between 3 to 5 digits long
```sh
python crack.py /home/elliot/Desktop/file.pdf -m 3 -n 5
``` 
#### This is for educational purpose only, and may not work on all .pdf files.


