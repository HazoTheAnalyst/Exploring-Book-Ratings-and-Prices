# Exploring Book Ratings and Prices — Web Scraping Project

This project focuses purely on **web scraping** book data from an online bookstore using Python’s `BeautifulSoup` and `requests` libraries.  
The scraped data includes **book titles, prices, and ratings**, which are saved into a CSV file for future analysis or exploration.
---
##  Project Overview

- **Goal:** To collect basic book details (title, price, and rating) from a website.  
- **Scope:** Web scraping only — no data analysis or visualization was performed.  
- **Output:** A CSV file named `books_scraped_data.csv` containing structured book data.

##  Dataset Preview

Below is a sample of the dataset used in this project:

![Dataset Screenshot](scraped%20data%20csv.png)
The dataset contains the following columns:
- **Title** – Name of the book
- **Price** – Price of the book
- **Rating** – Star rating of the book


---

##  Tools and Libraries Used

- **Python 3.x**
- **requests** – To send HTTP requests and fetch web pages.
- **BeautifulSoup (bs4)** – To parse HTML and extract specific elements.
- **csv / pandas** – To store the scraped data into a CSV file.
- **Jupyter Notebook** – Used to run and document the scraping process.


---

##  Project Workflow
1. Data scraping
#
---



##  Project Structure

---

## ⚙️ How the Scraper Works

1. Sends a GET request to the website’s book listing pages using `requests`.  
2. Parses the HTML response using `BeautifulSoup`.  
3. Extracts:
   - **Title** – The book’s name.
   - **Price** – The listed price (including currency symbol).
   - **Rating** – The star rating (e.g., One, Two, Three, etc.).  
4. Stores each record in a list of dictionaries.  
5. Writes the final data into a CSV file named `books_scraped_data.csv`.

---

##  How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/HazoTheAnalyst/Exploring-Book-Ratings-and-Prices.git
   cd Exploring-Book-Ratings-and-Prices

