# Create a README file
with open('README.md', 'w') as f:
  f.write('''
# Cybersecurity Jobs Data Analysis

This project uses the Indeed API to retrieve and analyze entry-level cybersecurity job listings in New York.

## Steps:
1. **Fetch job data:** The code sends a request to the Indeed API to retrieve job listings for "entrylevelcybersecurity" in "newyork".
2. **Store data in CSV:** The retrieved data is then stored in a CSV file named "cyberjobs_data.csv".
3. **Clean data:** The code reads the CSV file, removes rows with missing company names, and saves the cleaned data to a new CSV file named "cyberjobs_data_cleaned.csv".

## Requirements:
- requests library
- json library
- csv library
- pandas library

## API Key:
- You will need an API key from Indeed to use this code. Replace `"f016c95904mshcb5f883e445ac1ep1b864ejsn4a7ffae93426"` with your actual API key.
''')
