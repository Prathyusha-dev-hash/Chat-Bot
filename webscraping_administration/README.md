# Web Scraping - Administration Section

## Description
This module scrapes the college website's administration section and stores the data in a CSV file, which is then inserted into the database.

## Files
- `scraper.py`: Scrapes admin data (name, designation, email).
- `insert_to_db.py`: Loads scraped data into the database.
- `scraped_admin_data.csv`: Temporarily holds raw scraped data.

## To Run
```bash
python scraper.py
python insert_to_db.py
