# Web Crawler for Data Extraction
## Computer Networks Academic Project

---

## Overview
This project was developed as part of the **Computer Networks** course and focuses on building a **modular Python-based web crawler** to understand **HTTP-based client–server communication** and **automated data extraction** from websites.

The crawler starts from a **root URL**, navigates internal links within a **controlled depth**, extracts relevant content, and stores the data in a **structured JSON format** for analysis.

---

## Key Features
- **Automated website crawling** starting from a root URL  
- **Extraction of page titles, textual content, and image URLs**  
- **Randomized User-Agent headers** to mimic browser behavior  
- **Structured data storage** using JSON  
- **Modular and configurable design**

---

## Technologies Used
- **Python 3**
- **Requests**
- **BeautifulSoup (bs4)**
- **Fake-UserAgent**
- **JSON**

---

## Networking Concepts Applied
- **HTTP request–response model**
- **Client–server communication**
- **User-Agent handling**
- **Controlled crawling depth**

---

## Project Structure
```text
Web-Crawler-Data-Extraction
│
├── src/
│   ├── main.py          # Entry point of the crawler
│   ├── crawler.py       # Crawling logic and link traversal
│   ├── parser.py        # HTML parsing and data extraction
│   ├── storage.py       # JSON data storage
│   ├── utils.py         # Utility functions
│   └── config.py        # Configuration settings
│
├── report/
│   └── Project-report.pdf
│
├── sample-output/
│   └── output.json
│
└── requirements.txt

---

## Installation & Usage
```bash
pip install -r requirements.txt
python main.py


Configuration options such as target URL, crawl depth, and output file name can be modified in config.py.


## Use Cases
- **Academic research and learning**
- **Content aggregation**
- **Market and competitor analysis**
- **SEO and website structure analysis**

---

## Disclaimer
This project was developed **strictly for academic and educational purposes** as part of a university course.  
It demonstrates web crawling and data extraction concepts and follows **ethical web scraping practices**.  
The author does **not** support or encourage unauthorized or abusive use of this project.
