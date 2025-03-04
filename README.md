# Filter-and-OCR-App

![Python Logo](https://www.python.org/static/community_logos/python-logo.png)

## 📌 Projects Overview
This repository contains AI projects developed using Python and Streamlit. Each project serves a unique purpose, leveraging machine learning and deep learning techniques for real-world applications.

---

## 🚀 Projects Details

### 1️⃣ Filter App

🔹 **Description:**
The **Filter App** is an interactive web application built using Streamlit that allows users to apply various image processing filters in real time. It supports multiple filters, including grayscale conversion, edge detection, and other enhancements, making it a useful tool for image analysis and processing.

🔹 **Key Features:**
- Upload and process images directly in the browser.
- Apply multiple filters such as grayscale, edge detection, blurring, and more.
- Real-time preview of applied transformations.
- User-friendly interface powered by Streamlit.
- Allows users to download processed images.
- Supports multiple image formats (JPEG, PNG, etc.).

🔹 **Technologies Used:**
- Python 🐍
- OpenCV 🎥
- Streamlit 🌐
- NumPy 🔢
- Pillow 🖼️

🔹 **How to Run:**
```bash
pip install -r requirements.txt
streamlit run filter_app.py
```

🔹 **Usage Example:**
1. Run the application.
2. Upload an image.
3. Choose a filter from the sidebar.
4. View and download the processed image.
5. Experiment with different filters and settings.

---

### 2️⃣ Business Card Scanner

🔹 **Description:**
The **Business Card Scanner** is an AI-powered application that scans and extracts text from business cards using Optical Character Recognition (OCR). It automates data extraction, making it easier to store and manage business contact details efficiently.

🔹 **Key Features:**
- Upload an image of a business card.
- Extracts text using **Tesseract OCR**.
- Processes and structures the extracted text.
- Provides an option to save the details in a structured format.
- Supports multiple languages for OCR extraction.
- Allows users to copy extracted text to clipboard.
- Displays extracted text in a well-structured format.

🔹 **Technologies Used:**
- Python 🐍
- OpenCV 🎥
- Tesseract OCR 🔎
- Streamlit 🌐
- Pandas 📊

🔹 **How to Run:**
```bash
pip install -r requirements.txt
streamlit run business_card_scanner.py
```

🔹 **Usage Example:**
1. Run the application.
2. Upload a business card image.
3. The app extracts and displays the text.
4. Save the extracted details for future reference.
5. Copy text to clipboard for easy sharing.

---

## ⚙️ Installation Guide
To get started with these projects, follow these steps:

1️⃣ Clone this repository:
```bash
git clone git@github.com:MomenBhais/Filter-and-OCR-App.git
```

2️⃣ Navigate to the project directory:
```bash
cd your-repo
```

3️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

4️⃣ Run the desired application using:
```bash
streamlit run <app_name>.py
```
(Replace `<app_name>.py` with either `filter_app.py` or `business_card_scanner.py`.)

---

## 📂 Project Structure
```
📦 AI Projects Repository
│-- 📂 filter_app
│   │-- filter_app.py
│   │-- sample_images/
│-- 📂 business_card_scanner
│   │-- business_card_scanner.py
│   │-- sample_cards/
│-- requirements.txt
│-- README.md
│-- .gitignore
```

---

## 🤝 Contributing
We welcome contributions from the community! If you find a bug or have suggestions for improvements, feel free to submit an issue or open a pull request.

### How to Contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request with a detailed explanation of your changes.

---

## 📜 License
This project is licensed under the MIT License. You are free to use, modify, and distribute it under the terms of this license.

---

## 📧 Contact
For any inquiries or suggestions, feel free to reach out!
- **Name:** Momen Mohammed Bhais
- **Email:** [momenbhais@outlook.com](mailto:momenbhais@outlook.com)



