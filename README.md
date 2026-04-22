 Project Name: BooksToScrape Web Scraper

1. Project Overview
* **Target Website:** http://books.toscrape.com/
* **Data Fields Extracted:** Title, Price, Rating, Page Number
* **Tools Used:** Python, requests, BeautifulSoup, pandas

 2. Setup Instructions
1. Clone this repo: `git clone []`
2. Install dependencies: `pip install -r requirements.txt`
3. Run script: `python scraper.ipynb`

3. Challenges & Solutions
One challenge was handling pagination across multiple pages. This was solved by dynamically updating the page number in the URL and stopping the loop when a page returned a non-200 status code.
