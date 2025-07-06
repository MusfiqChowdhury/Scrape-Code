# 🧠 Research Paper Scraper

A robust research paper metadata scraper for Google Scholar, developed using Python and `undetected_chromedriver`. This tool helps you gather academic paper information like titles, authors, citation counts, and links based on user-defined keywords.

---

## 🚀 Features

- ✅ Search Google Scholar using your custom list of keywords
- 📄 Extract metadata for each result:
  - Title
  - Authors
  - Citations
  - Link
  - Snippet
  - Query
  - Page No.
- 📦 Save all results in a structured CSV file
- 🔒 Bypass bot detection using undetected ChromeDriver
- 🌍 Recommend using VPN for safer and uninterrupted scraping

---

## 📂 Project Structure

``` bash
📦 Research-Paper-Scraper/
├── Scraping_Code.ipynb         # Main scraping notebook
├── requirements.txt            # Python dependencies
├── .env.sample                 # Sample env config
├── README.md                   # Project documentation
```

---

## ⚙️ Requirements

- Python 3.x
- Google Chrome browser installed
- VPN (Recommended for anonymity and avoiding IP block)

---

## 🛠️ Setup Instructions

1. Clone the Repository
```bash
git clone https://github.com/Raihan4520/Research-Paper-Scraper.git
```
2. Go to `Research-Paper-Scraper` Folder
```bash
cd Research-Paper-Scraper
```
3. Install Dependencies
```bash
pip install -r requirements.txt
```
4. Set up the Environment Variables

Copy the sample environment file
```bash
cp .env.sample .env
```
5. Edit your Keywords in `.env` File
```ini
# Sample Values:
FIXED_KEYWORDS = '"Artificial Intelligence", "Machine learning"'
OPTIONAL_KEYWORDS = '"Natural Language Processing", "Generative AI", GPT, Chatbot, "Conversational AI"'
FILTER_KEYWORDS = '' # Optional
```

---

## ▶️ How to Use

Run the scraper using the Jupyter notebook:
```bash
jupyter notebook Scraping_Code.ipynb
```

### 🛡️ Important:

- Make sure Google Chrome is installed on your system.
- It is recommended to use a VPN to mask your real IP and avoid being rate-limited or blocked by Google Scholar.

---

## 📌 Notes

- Scraping from Google Scholar may be blocked or limited. Using a VPN is strongly advised.
- Do not overload Google with too many requests too quickly.
- `undetected_chromedriver` is used to bypass bot detection but Chrome must be installed on your system.

---

## 👋 Contact

For questions or collaboration, feel free to connect via GitHub or open an issue in this repository.

---

⚠️ Disclaimer: Scraping Google Scholar may violate their terms of service. Use this tool responsibly and only for academic purposes.
