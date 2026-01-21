*Technical Highlights:*

Smart Navigation: The script first extracts all Genre links from the sidebar and then iterates through them to classify books automatically.

Data Extraction: Used BeautifulSoup to locate specific elements (Title hidden in attributes, Rating hidden in CSS classes).

Error Handling: Implemented try-except blocks to ensure the scraper continues running even if specific pages fail or time out.

Data Cleaning:
Converted text ratings ("Three", "Five") into numerical values (3, 5).
Cleaned currency symbols and formatted prices.

Output: Structured Excel file.
Tools Used: Python, BeautifulSoup4, Requests, Pandas.
