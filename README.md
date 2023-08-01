# RegEx_DataEntry

## Description
RegEx_DataEntry is a Python project designed to read user data from a text file using regular expressions (RegEx) and process it by adding the extracted information to a CSV file. The project focuses on grouping data distinctly based on specific values, making it easy to organize and analyze the data.

The main objectives of this project are as follows:
- Read data from a text file using RegEx patterns.
- Extract relevant information such as names, phone numbers, addresses, emails, etc.
- Organize the extracted data and save it in a CSV file for further analysis.

## How to Use
1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/RegEx_DataEntry.git
   cd RegEx_DataEntry
   ```

2. Make sure you have Python installed on your system (Python 3.6 or above).

3. Place the data text file you want to process in the same directory as the project files and name it `data.txt`.

4. Run the Python script:

   ```bash
   python main.py
   ```

5. The script will process the data from `data.txt`, extract relevant information, and save it to a new CSV file named `data.csv`.

## Dependencies
The project relies on the following Python libraries, which should be installed:

- `re`: Python's built-in regular expression library.
- `csv`: Python's built-in library for reading and writing CSV files.

## Example
Assuming you have a `data.txt` file with the following format:

```
John Doe
123-456-7890
123 Main St, City
john.doe@example.com

Jane Smith
987-654-3210
456 Park Ave, Town
jane.smith@example.com
```

The Python script will extract the data and create a `data.csv` file with the following content:

```
Sr.,FirstName,LastName,Street,Locality,Email,Domain
1,John,Doe,123 Main St,City,john.doe@example,com
2,Jane,Smith,456 Park Ave,Town,jane.smith@example,com
```

## License
This project is licensed under the [MIT License](LICENSE).

## Contribution
Contributions to the project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## Acknowledgments
- The project was inspired by the need to efficiently process user data using regular expressions and CSV manipulation.

---

Happy Data Processing!

Thank you for using RegEx_DataEntry! 🚀
