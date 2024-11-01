# Accounts data writer to Excel

## Description

This Python script is designed to read private keys and proxy information from text files and write this data into an Excel spreadsheet. It utilizes the `openpyxl` library to facilitate the interaction with Excel files, making it easy to manage account information.

## Features

- Reads private keys from a specified text file.
- Reads proxy information from another text file.
- Automatically generates account names based on their index.
- Writes the data into designated columns in an Excel file.

## Requirements

To run this script, you need to have the following library installed:

- `openpyxl`

You can install the required library using pip:

```bash
pip install openpyxl

Usage
Set Up File Paths: Modify the file_path, privates_path, and proxies_path variables in the script to point to your Excel file and text files containing private keys and proxies.


file_path = r"C:\path\to\your\accounts_data.xlsx"
privates_path = r"C:\path\to\your\privates.txt"
proxies_path = r"C:\path\to\your\proxies.txt"
Prepare Your Text Files: Ensure that your privates.txt and proxies.txt files contain the private keys and proxies, respectively, with each entry on a new line.

Run the Script: Execute the script in your Python environment. The program will read the private keys and proxies from the text files and write them to the specified Excel file.

Check Output: After successful execution, the script will print a message indicating how many accounts were successfully updated.

Notes
The script assumes that the number of private keys in privates.txt matches the number of proxies in proxies.txt.
Data will be written starting from the second row of the Excel sheet to accommodate headers.
Ensure the Excel file exists and is not opened in another application while running the script.

Author
Divinus
0xCEbbc4B9930c97410A2d73C6644315F804568eBd
