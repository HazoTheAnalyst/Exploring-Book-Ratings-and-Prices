# Exploring Book Ratings and Prices 
Web scraping project using Python to collect and analyze book data from a public website.

---

##  Project Overview
This project involves scraping book information such as **titles, prices, and ratings** from the website **books.toscrape.com**. The goal of this project was to:

-  Practice real-world **web scraping techniques**
-  Perform **data cleaning and organization**
-  Build a **portfolio project** showcasing Python and data analysis skills

---

##  Tools & Technologies Used
| Tool | Purpose |
|------|---------|
| Python | Programming |
| BeautifulSoup | Parsing HTML content |
| Requests | Sending HTTP requests |
| Pandas | Data cleaning & analysis |

### Dataset Preview

Here is a preview of the dataset I scraped:

![Dataset Preview](https://raw.githubusercontent.com/YourUsername/YourRepo/main/images/scraped%20data%20csv.png)


---

##  Project Structure

```bash
Exploring-Book-Ratings-and-Prices/
│
├── data/
│   └── books_scraped_data.csv                
├── notebooks/
│   └── Exploring Book Ratings and Prices via Web Scraping.ipynb 
├── src/
│   ├── scraper.py               
│   ├── parser.py                
│   └── utils.py                 
├── requirements.txt             
└── README.md                    

git clone https://github.com/HazoTheAnalyst/Exploring-Book-Ratings-and-Prices.git
cd Exploring-Book-Ratings-and-Prices

pip install -r requirements.txt

python src/scraper.py

Exploring Book Ratings and Prices via Web Scraping.ipynb



