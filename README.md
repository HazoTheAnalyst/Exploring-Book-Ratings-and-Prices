# 📚 Exploring Book Ratings and Prices via Web Scraping

This project demonstrates practical web scraping skills by extracting book data from the website **Books to Scrape**. The data includes **book titles, prices, and ratings**, which are collected and saved into a structured CSV file for further analysis. This project highlights data collection using Python and popular scraping libraries.

---

## 🔍 Project Objectives
- Extract book information (Title, Price, Rating) from http://books.toscrape.com  
- Demonstrate web scraping using **BeautifulSoup** and **Requests**  
- Clean and organize the data using **Pandas**  
- Export results into a CSV file  
- Showcase data scraping skills 

---

## ✅ Tools & Technologies Used
| Tool/Library      | Purpose |
|-------------------|---------|
| Python            | Programming language |
| BeautifulSoup     | HTML parsing and data extraction |
| Requests          | Sending HTTP requests to website |
| Pandas            | Data cleaning and saving to CSV |
| Jupyter Notebook  | Code execution and documentation |


## 🗂️ Project Structure


---

## 📦 Dataset Output
The scraped dataset contains the following columns:
| Column Name | Description |
|--------------|-------------|
| Title        | Name of the book |
| Price        | Price in GBP (£) |
| Rating       | Book rating (out of 5 stars) |

---

## 🔧 How to Run This Project

### ✅ Prerequisites
Make sure you have Python installed on your system. Then install dependencies:

```bash
pip install requests beautifulsoup4 pandas
git clone https://github.com/your-username/exploring-book-ratings-via-web-scraping.git
jupyter notebook "Exploring Book Ratings and Prices via Web Scraping.ipynb"
