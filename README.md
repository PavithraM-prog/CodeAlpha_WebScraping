# 📚 CodeAlpha Task 1 - Web Scraping

## Project Overview

This project was completed as part of the **CodeAlpha Python Programming Internship**.

The objective is to scrape book information from a website using Python and export the extracted data into a CSV file.

---

## Features

- Sends HTTP requests to a webpage
- Parses HTML using BeautifulSoup
- Extracts:
  - Book Title
  - Price
  - Availability
  - Rating
- Stores the extracted data in a Pandas DataFrame
- Exports the data to a CSV file

---

## Technologies Used

- Python
- Google Colab
- Requests
- BeautifulSoup4
- Pandas

---

## Website Used

https://books.toscrape.com/

> This website is created specifically for learning and practicing web scraping.

---

## Project Structure

```
CodeAlpha_WebScraping/
│── CodeAlpha_Task1_WebScraping.ipynb
│── books_data.csv
│── README.md
```

---

## Output

The generated CSV file contains the following columns:

| Title | Price | Availability | Rating |
|-------|-------|--------------|--------|

Example:

| Title | Price | Availability | Rating |
|-------|-------|--------------|--------|
| A Light in the Attic | £51.77 | In stock | Three |

---

## Skills Demonstrated

- Web Scraping
- HTML Parsing
- Data Collection
- Data Cleaning
- CSV File Generation
- Python Programming

---

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries:

```bash
pip install requests beautifulsoup4 pandas
```

3. Run all notebook cells.
4. The output file `books_data.csv` will be generated automatically.

---

## Author

**Pavithra M**

GitHub: https://github.com/PavithraM-prog

---

## Internship

Submitted as **Task 1** for the **CodeAlpha Python Programming Internship**.
