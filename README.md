# LegiCert

LegiCert is a tool designed to validate the legitimacy of companies listed on internship certificates. By extracting the company name from the certificate, LegiCert retrieves essential information such as the establishment date, CEO name, and more, ensuring students and educational institutions can verify internships accurately.

## Features

- Extracts company name from internship certificates using Optical Character Recognition (OCR).
- Gathers company information from various reliable sources via web scraping and APIs.
- Displays company details including:
  - Establishment Date
  - CEO Name
  - Company Location
  - Website Information
- User-friendly interface for easy interaction.

## Technologies Used

- **Python**: The primary programming language for the tool.
- **pytesseract**: Library for OCR to extract text from images/PDFs.
- **BeautifulSoup**: Used for web scraping HTML data.
- **Selenium**: For interacting with dynamic content.
- **Requests**: For making API calls and handling HTTP requests.
- **Flask/Django**: For creating a web-based user interface (UI).
- **SQLite/MongoDB**: For storing retrieved company data.
