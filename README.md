# Amazon Trends Webscraping
This project demonstrates how to collect and analyze real-time product trend data from the Amazon Bestseller page using Selenium, a powerful Python library for browser automation and dynamic web scraping.

---

## Project Overview

In today’s data-driven environment, accessing real-time market data can offer a strategic edge.  
This project scrapes Amazon's Bestseller page to uncover consumer trends and product rankings, showcasing the power of Selenium in automating complex browser interactions and handling dynamic content.

The final output includes:
- A Jupyter Notebook showcasing the scraping process
- Key challenges and solutions (e.g., handling infinite scroll)
- Insights into how this data can be used for trend analysis and business strategy

---

## Tools & Technologies

- **Python 3**
- **Selenium**
- **Jupyter Notebook**
- **ChromeDriver**
- **Amazon Bestseller page**: [https://www.amazon.com/gp/bestsellers/](https://www.amazon.com/gp/bestsellers/)

---

## How to Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/amazon-trends-webscraping.git
   cd amazon-trends-webscraping

2. Install required packages:
   ```bash
   pip install -r requirements.txt

3. Download and set up [ChromeDriver](https://sites.google.com/chromium.org/driver/) that matches your browser version. Ensure it's added to your system PATH.

4. Open the notebook:
   ```bash
   jupyter notebook amazon_scraper_jung.ipynb

---

## Key Features

- Scrapes dynamic web pages that load content via JavaScript
- Automatically scrolls to load full bestseller lists
- Parses and structures product data for further analysis
- Designed with flexibility for adapting to other Amazon departments

---

## Challenges Faced
- Dealing with Amazon's **infinite scroll**
- Ensuring data loads completely before extraction
- Adapting scraping logic to handle layout variations across departments

---

## Project Context
This project was created as part of the <i> Programming for Business Analytics</i> course at Babson College (Spring 2024).
It reflects a hands-on application of automation and data collection techniques for real-world business analysis.

---

## Author
**Jung Kim**
Babson MBA | Business Analytics & Global Management
[LinkedIn Profile](https://www.linkedin.com/in/jayjungkim/)

---

## License
This project is for educational purposes only. Please review Amazon's [robots.txt](https://www.amazon.com/robots.txt) and terms of service before conducting scraping on a large scale or for commercial purposes.

---
