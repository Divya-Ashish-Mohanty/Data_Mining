# SnowScrape_ETL
---
### Description
**SnowScrape_ETL** is a Python-based ETL (Extract, Transform, Load) pipeline designed for extracting data from websites, transforming it according to specific business or analytical needs, and storing it in a Snowflake data warehouse. This project leverages powerful Python libraries such as Beautiful Soup for web scraping, Pandas and NumPy for data transformation, and the Snowflake connector for seamless data integration.

### Key Features
- **Data Extraction:** Uses Beautiful Soup to scrape structured and semi-structured data from websites.
- **Data Transformation:** Utilizes Pandas and NumPy for cleaning, transforming, and preprocessing data to prepare it for analysis.
- **Data Loading:** Converts the transformed data into CSV format and loads it into a Snowflake data warehouse for scalable storage and querying.
- **Modular ETL Design:** The pipeline is modular, making it easy to adapt to different data sources and formats.

### Installation
To run this project, you will need Python and the following libraries:
- `beautifulsoup4`
- `pandas`
- `numpy`
- `snowflake-connector-python`

You can install the required libraries using pip:

```bash
pip install beautifulsoup4 pandas numpy snowflake-connector-python
```

### Usage
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Divya_Ashish_Mohanty/SnowScrape_ETL.git
   cd SnowScrape_ETL
   ```

2. **Configure Snowflake Connection:**
   Update the Snowflake connection details in the `config.py` file:
   ```python
   SNOWFLAKE_USER = 'your_user'
   SNOWFLAKE_PASSWORD = 'your_password'
   SNOWFLAKE_ACCOUNT = 'your_account'
   ```

3. **Run the ETL Pipeline:**
   Execute the `etl_pipeline.py` script to start the ETL process:
   ```bash
   python etl_pipeline.py
   ```
   
### Contributing
Contributions are welcome! Please fork this repository, make your changes, and submit a pull request. Ensure your code is well-documented and follows the project's coding style.

### Acknowledgments
- **Beautiful Soup** for web scraping.
- **Pandas** and **NumPy** for data processing.
- **Snowflake** for providing a powerful data warehousing solution.

### Contact
For any questions or feedback, please contact Divya Ashish Mohanty at mohantydivyaashish@gmail.com.

---
