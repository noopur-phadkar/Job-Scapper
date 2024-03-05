# Job Scraper (Indeed)

This project is a Python-based web scraper that automates the process of extracting job listings from Indeed.com. It allows users to specify job titles and locations to find relevant job postings. The results include job titles, companies, links to the postings, and the date they were listed, all saved conveniently into an Excel file.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation

Before running the scraper, ensure you have Python 3 and pip installed on your machine. Then, follow these steps to set up the project environment:

1. **Clone the Repository:**
   Open your terminal and run:
   ```
   git clone https://github.com/noopur-phadkar/job-scraper-indeed.git
   ```

2. **Navigate to the Project Directory:**
   ```
   cd job-scraper-indeed
   ```

3. **Create a Virtual Environment (optional but recommended):**
   ```
   python -m venv venv
   ```
   Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS/Linux: `source venv/bin/activate`

4. **Install Dependencies:**
   Ensure your virtual environment is activated, then run:
   ```
   pip install -r requirements.txt
   ```

## Usage

To use the scraper, follow these instructions:

1. **Configure the Scraper:**
   Open `scraper.py` with your favorite text editor. Modify the `desired_characs` list to include the characteristics you want to extract (e.g., titles, companies). Update the job title and location in the `__main__` block to reflect your search criteria.

2. **Run the Scraper:**
   With your terminal still open, ensure you are in the project directory and your virtual environment is activated. Run:
   ```
   python scraper.py
   ```
   The script will begin scraping Indeed for job listings based on your specifications.

3. **View Results:**
   Once the script completes, find the `results.xls` file in the project directory. Open it to view the scraped job listings.

## Features

- **Dynamic Web Scraping:** Utilizes BeautifulSoup and Requests to parse and extract data from web pages dynamically.
- **Customizable Search Queries:** Easily modify the job title and location directly in the script for tailored job searches.
- **Excel Integration:** Export the scraped data into an Excel file, making it easy to view, share, and analyze the job listings.
- **Error Handling:** Includes basic error handling to ensure the scraper runs smoothly, even if it encounters unexpected page structures.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
