# Excel to PDF Converter

This Python program converts Excel files to PDF format. It provides a convenient way to transform Excel spreadsheets into PDF documents, making it easier to share and distribute data in a standardized format.

## Features

- Converts Excel files to PDF format.
- Retains the formatting and structure of the original Excel sheets in the resulting PDF.
- Supports multiple sheets within a single Excel file.
- Customizable headers and footers for each page in the PDF.

## Usage

1. Clone the repository or download the source code files.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Prepare your Excel file(s) that need to be converted to PDF.
4. Modify the `main.py` file to specify the path to your Excel file(s) and any desired customization for headers and footers.
5. Run the `main.py` script using Python: `python main.py`.
6. The program will generate the corresponding PDF file(s) with the same name as the Excel file(s) in the same directory.

## Example

The program is accompanied by an example `topics.csv` file, containing a list of topics and the number of pages for each topic. You can use this file to test the program's functionality. Simply replace the contents of `topics.csv` with your own data, following the same format.

## Requirements

- Python 3.6 or above
- `openpyxl` library
- `fpdf` library
- `pandas` library

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or new features to add, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/licenses/MIT) file for more information.

## Acknowledgements

- [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - A library for reading and writing Excel files in Python.
- [fpdf](https://pyfpdf.readthedocs.io/en/latest/) - A Python library for PDF generation.
- [pandas](https://pandas.pydata.org/) - A powerful data manipulation library for Python.

Feel free to customize the above template to include specific details about your project, such as installation instructions, additional features, or any other relevant information.