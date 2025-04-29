MTWebCrawler is a lightweight Python web crawler that extracts and displays all internal links from a given website.
It navigates the site recursively, avoiding duplicates and mapping out the structure.

Features
Crawls through internal links of a website
Avoids visiting the same link more than once
Outputs all discovered links
Simple and efficient design


Technologies Used
Python 3
Requests
BeautifulSoup4


Installation
Clone the repository:

git clone https://github.com/Harris1250/MTWebCrawler.git
cd MTWebCrawler

Install the required libraries:
pip install requests beautifulsoup4

How to Run
Run the crawler script:
python crawler.py

Enter the URL of the website you want to crawl when prompted.

The program will print all the links it finds.

Example
Enter a website URL to crawl: https://example.com
Crawling: https://example.com
Found: https://example.com/about
Found: https://example.com/contact
...

Project Structure
MTWebCrawler/
│
├── crawler.py       # Main web crawler script
├── README.md        # Project documentation
