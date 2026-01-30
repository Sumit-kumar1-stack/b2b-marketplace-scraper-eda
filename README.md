1️⃣ Project Title

B2B Marketplace Data Collection and Exploratory Data Analysis

2️⃣ Project Description 

This project implements an end-to-end data collection and analysis workflow 
for B2B marketplaces such as Alibaba. It includes automated data extraction 
(web scraping), data cleaning and structuring, and exploratory data analysis (EDA)
to identify trends across suppliers, products, and regions.

3️⃣ Assignment Mapping

Part A – Data Collection

• Identified meaningful product categories: Industrial Machinery and Electrical Equipment
• Implemented a custom web scraper using Python
• Handled site blocking and rate-limiting scenarios with graceful fallback logic
• Extracted structured supplier and product information
• Stored clean data in CSV format

Part B – Exploratory Data Analysis (EDA)

• Performed summary statistics and distribution analysis
• Identified top suppliers, products, and countries
• Analyzed category-wise supplier distribution
• Generated visualizations to support findings
• Highlighted data quality limitations and inconsistencies

4️⃣ Project Structure (SHOWS ENGINEERING QUALITY)

b2b-marketplace-scraper-eda/
│
├── scraper/        # Data collection logic
├── utils/          # Utility and fallback mock data
├── eda/            # Exploratory data analysis
├── output/         # CSV data and generated plots
├── run.py          # Main execution script
├── requirements.txt
└── README.md

5️⃣ How to Run the Project 

1. Create virtual environment

   python -m venv venv
   venv\Scripts\activate   (Windows)

2. Install dependencies

   pip install -r requirements.txt

3. Run the project

   python run.py

6️⃣ Output Generated

• output/suppliers.csv          → Structured supplier dataset
• output/eda/*.png              → EDA visualizations

7️⃣ Tools & Technologies Used

• Python 3
• Playwright / Requests
• Pandas
• Matplotlib

8️⃣ Notes / Limitations 

Some B2B platforms restrict automated scraping.
In such cases, the system generates representative mock data to demonstrate
the full data analysis pipeline and ensure reproducibility.
