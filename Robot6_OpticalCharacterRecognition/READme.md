# PDF data scrapper

This bot processes 1,000 PDF invoices, extracts key details (invoice number, date, company name, total amount), and outputs the data to an Excel spreadsheet. Additionally, it logs successes and failures, moving invoices to respective folders.

**Key Features:**

* Loops through PDF invoices, extracting and appending data to Excel.
* Handles errors gracefully without stopping the process.
* Logs failures with error messages and suggested fixes.
* Moves invoices to "successful" or "failed" folders based on outcomes.

**Key Learning Concepts:**
* Looping through files in a folder.
* Exception handling for error resilience.
* Scraping text from PDFs and optimizing selectors.
* Working with data tables and Excel spreadsheets.
* Moving files between folders.
