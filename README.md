# Top 10 Largest Banks

## Description
This python code extract, transform, and load (ETL) data about the top 10 largest banks in the world by market capitalization. The data is converted into different currencies and stored both as a CSV file and in a SQLite database for querying.

### Steps:
1. Extract: The code scrapes data from a webpage to get the names and market capitalizations (in USD) of the top 10 largest banks.
2. Transform: The market capitalization values are converted from USD to GBP, EUR, and EGP using exchange rates from a CSV file.
3. Load: The transformed data is saved as a CSV file and also stored in a SQLite database.
4. Query: The code runs sample queries on the database to demonstrate how the data can be accessed.

## Installation
To set up the project, clone the repository and install the required dependencies.

```bash
# Clone the repository
git clone https://github.com/KhaledMSabry/Top_10_banks.git

# Navigate to the project directory
cd Top_10_banks

# Install dependencies
pip install -r requirements.txt

# Run the main script to execute the ETL process
python main.py
