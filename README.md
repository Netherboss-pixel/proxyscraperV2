# 🕵️‍♂️ ProxyScraper V2

**ProxyScraper V2** is a high-performance, multithreaded proxy scraper and validator. It fetches proxies from **80+ sources**, optionally checks their validity, and saves the working list in a plain `.txt` format — purrfect for use in scraping, pen testing, or any project that needs anonymity.

## ✨ Features

- 🔥 Fetch proxies from over 80 curated sources
- 💨 Insanely high threading capability (default: 99,999,999 threads!)
- 🧪 Optional proxy testing against `http://ip-api.com/json/`
- 🧾 Saves valid proxies to `proxies.txt`
- ⏱ Customizable timeout for proxy validation
- 🐍 Written in pure Python — no dependencies beyond `requests`

## ⚙️ Configuration

You can tweak the following variables in the script:

```python
THREADS = 99999999          # Number of threads for proxy checking
PROXY_TIMEOUT = 5           # Timeout in seconds for each proxy request
OUTPUT_FILE = "proxies.txt" # Output file name
CHECK_PROXIES = False       # Toggle proxy validation (True/False)

git clone https://github.com/Railgun1337/proxyscraperV2.git
cd proxyscraper-v2

python proxyscraperV3.py
