# Web Scraping tratencongty.com using BeautifulSoup, Requests, and Tesseract

## Overview

This project is focused on scraping data from the website `tratencongty.com`. The main goal is to extract company information, including Tax ID numbers and phone numbers, using Python's `BeautifulSoup` and `Requests` libraries for web scraping. However, the website presents a challenge: the Tax ID and phone numbers are displayed as images rather than text. To overcome this, I used the `Tesseract` OCR (Optical Character Recognition) engine to extract text from the images.

## Key Features

- **Web Scraping**: The project uses `BeautifulSoup` to parse HTML content and extract relevant data from `tratencongty.com`.
- **Handling Image-based Data**: Tax ID numbers and phone numbers are displayed as images on the website. The project uses `Tesseract` OCR to extract this information.
- **Data Extraction**: Successfully scrapes and extracts most of the data, including company names, addresses, and other relevant details.

## Challenges

- **Inconsistent OCR Results**: Despite using `Tesseract`, some of the extracted text from images is incorrect. This is a limitation of OCR technology, especially when dealing with low-quality or complex images.
  
## Requirements

- Python 3.x
- `BeautifulSoup4` for parsing HTML content
- `Requests` for making HTTP requests
- `Tesseract-OCR` for optical character recognition
- `pytesseract` for integrating Tesseract with Python
  
## Future Improvements

- **Image Preprocessing**: Implementing image preprocessing (e.g., resizing, thresholding, denoising) before feeding images into Tesseract may improve the accuracy of text extraction.
- **Error Handling**: Adding more robust error handling to manage incorrect data extraction and retries for failed requests.

## Contributing

I welcome contributions to improve the scraper's efficiency and accuracy. Feel free to fork the repository and submit pull requests.
