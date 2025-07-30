# web_scrapping_project
GitHub Project Description: Web Scraping the List of Largest U.S. Companies by Revenue
This project provides a Python-based web scraping solution that extracts and organizes structured data from the Wikipedia page: List of largest companies in the United States by revenue. The script leverages libraries such as BeautifulSoup, Requests, and Pandas to collect tabular information about the biggest public and private companies in the U.S. by revenue, along with profitability and other key statistics for 2024.
Features
	•	Automated data scraping from the Wikipedia page for current financial data on top U.S. companies.
	•	Extracts details including company name, industry, revenue, revenue growth, profits, employees, and headquarters location.
	•	Captures data for:
	•	Top 100 public companies by revenue
	•	Top 10 private companies by revenue
	•	Top 10 most profitable companies
	•	Outputs the data in a clean tabular format (CSV/Excel/JSON) for easy analysis or visualization.
	•	Includes error handling for robust extraction when the underlying page structure changes.
	•	Open-source and easy to customize for different Wikipedia tables.
Use Cases
	•	Market research: Rapidly analyze the structure of the U.S. corporate landscape.
	•	Business intelligence: Power dashboards about leading employers, top profit-makers, or fastest-growing industries.
	•	Academic projects or case studies: Utilize up-to-date, authoritative data for financial and management research.

How It Works
	1.	Fetches page content with  requests .
	2.	Parses HTML tables using  BeautifulSoup .
	3.	Cleans and normalizes raw tabular data.
	4.	Exports data for downstream applications.
