# 💻 Laptrix – Laptop Recommendation System

Laptrix is an intelligent laptop recommendation system that helps users make informed purchasing decisions by scraping real-time data from leading e-commerce websites. Built with a robust Java backend, clean front-end interface, and API integration, Laptrix allows users to filter laptops based on their preferences and receive up-to-date recommendations.

## 🚀 Features

- 🔍 **Real-time Web Scraping:** Uses Selenium to fetch data from multiple online retailers.
- 🧠 **Smart Filtering:** Enables selection by brand, processor, RAM, storage, and price range.
- ⚙️ **Java-based Backend:** Handles and processes data from over 500 laptop entries.
- 🌐 **Live Price & Availability:** Integrates with external APIs to ensure real-time data for smarter choices.
- 🎨 **User-Friendly UI:** Interactive and responsive front-end built with HTML, CSS, and JavaScript.
- 📊 **Improved Engagement:** Increased user interaction by 15% through dynamic filtering options.

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Java  
- **Web Scraping:** Selenium  
- **External APIs:** Integrated to enrich recommendation data  
- **Data Volume:** Handles 500+ products in real-time  

## 📁 Project Structure

```bash
laptop_recommendor-main/
├── backend/                 # Java backend logic
│   ├── Scraper.java         # Selenium-based scraping logic
│   └── FilterEngine.java    # Filtering logic
├── frontend/                # HTML/CSS/JS files for the UI
│   ├── index.html
│   ├── styles.css
│   └── app.js
├── data/                    # JSON/CSV for product data (if any)
├── README.md
└── requirements.txt         # Selenium and other dependencies (optional)
