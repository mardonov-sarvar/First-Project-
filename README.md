# HeadHunter Vacancy Collector

This project collects all job vacancies in Tashkent from the HeadHunter.uz website and saves them into a SQL Server database.

##  What has been done in this project:
- Collected vacancies via API (`hh.ru API`)
- Performed scraping using Selenium + BeautifulSoup
- Merged data and removed duplicates
- Converted dates into `datetime` format
- Saved vacancies into SQL Server database

##  Technologies
- Python 3
- Pandas
- Requests
- Selenium
- BeautifulSoup4
- PyODBC (for connecting to SQL Server)

##  How to run
1. Clone the repository:
   ```bash
   git clone https://github.com/mardonov-sarvar/First-Project-.git
   cd First-Project-
