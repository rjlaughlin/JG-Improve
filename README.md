# Macro-based Spreadsheet

This repository contains a set of macros designed to facilitate the management of Creo Parametric files and streamline the workflow for inventory data imports. Below is a detailed list of each macro included in this spreadsheet, along with their functions and usage.

## Table of Contents

- [List of Macros](#list-of-macros)
  - [Copy Files](#copy-files)
  - [Change Creo Version](#change-creo-version)
  - [Audit Release Directory](#audit-release-directory)
  - [ECN Import Generator](#ecn-import-generator)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## List of Macros

### Copy Files

- **Function**: Copies the latest version of Creo Parametric files and stores them in a new folder.
- **Usage**: 
  - Select the files you wish to copy.
  - Run the macro to create a new folder containing the copied files in the format `XXX-XXX.prt.1`.

### Change Creo Version

- **Function**: Changes the index number of a Creo Parametric file to a desired number.
- **Usage**:
  - Specify the file and the desired version number.
  - Execute the macro to update the file's version index accordingly.

### Audit Release Directory

- **Function**: Moves files from the Release directory to the Archive directory based on file name and type.
- **Usage**:
  - Run the macro to automatically sort and archive files using the naming pattern `XXX-XXX_A -> XXX-XXX_B`.

### ECN Import Generator

- **Function**: Converts data from a Google Sheets spreadsheet into an importable CSV file for Fishbowl Inventory.
- **Usage**:
  - Ensure your Google Sheets data is formatted correctly (code will need to be modified to match a new format)
  - Use the macro to generate a CSV file ready for import into Fishbowl Inventory.

## Installation

To use these macros, you will need to have the following software installed:

- **Creo Parametric**
- **Microsoft Excel or a compatible spreadsheet editor**

1. **Download the spreadsheet containing the macros**.
2. **Open the spreadsheet in Excel**.
3. **Enable macros** by adjusting your Excel settings: Go to `File` > `Options` > `Trust Center` > `Trust Center Settings` > `Macro Settings` and choose `Enable all macros`.

## Usage

1. **Open the Spreadsheet**: Launch Excel and open the macro-enabled spreadsheet.
2. **Select a Macro**: Choose the desired macro from the list and execute it by following the specified usage instructions.
3. **Review Results**: Check the results of the macro operation in the specified directories or generated files.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

