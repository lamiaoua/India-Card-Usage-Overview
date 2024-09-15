# India-Card-Usage-Overview


![Logo](https://media.licdn.com/dms/image/D5612AQFfKS70Lv09HA/article-cover_image-shrink_720_1280/0/1679919905983?e=2147483647&v=beta&t=5AchgDacsdbdOIobrR0JWKfHjoQb9JPfsjoc13rKynA)


# Dashboard-to-Monitor-Debit-and-Credit-Cards-Usage-in-India

This project is a comprehensive data analysis initiative aimed at extracting valuable insights from data related to the usage of bank cards.
The project's main goal is to assess HDFC Bank's performance in the debit and credit card sector compared to the overall banking industry. It includes a detailed comparative evaluation, the development of specific Key Performance Indicators (KPIs) for objective measurements, historical trend analysis, and strategic recommendations to enhance the bank's position in the card sector. The initial step involves scraping data from the Reserve Bank of India (RBI) website.

# TASK 1 
# Scrape Data from the RBI website

  The project commenced by utilizing Python's Selenium library for web scraping to extract data from the Reserve Bank of India's website [RBI](https://www.rbi.org.in/Scripts/ATMView.aspx), focusing on the data from the last 10 months. Selenium, a powerful tool for automating web browser interactions, was employed to navigate the website, gather the required information, and subsequently download the extracted data to the local machine.
- Tools Utilized: Python, Selenium, web scraping
## Cleaning and Organizing Data in Excel:

Once the data was downloaded, we noticed some problems that needed fixing. We carefully cleaned up the information in the Excel files by following a set of rules to make sure everything was consistent and reliable. This included getting rid of unnecessary columns, combining certain cells, grouping transactions, converting values into Indian Rupees (₹), and removing rows with no information. We also made changes to how the data was organized to better distinguish between different banks and their types.



## Data set for the project 

Here's a brief definition for each of the columns:

1. **Type:** Indicates the type of bank, whether it's a Scheduled Commercial Bank or a Private Sector Bank.

2. **Bank Name:** Represents the name of the specific bank for which the data is reported.

3. **Credit Cards:** Denotes the number of outstanding credit cards as of the month-end.

4. **Debit Cards:** Represents the number of outstanding debit cards as of the month-end.

5. **cc_transactions:** Refers to the volume of credit card transactions across various channels, such as PoS (Point of Sale), online (e-commerce), and others.

6. **dc_transactions:** Indicates the volume of debit card transactions across different channels, including PoS, online, and others.

7. **cc_inr_values:** Represents the value of credit card transactions in Indian Rupees (₹).

8. **dc_inr_values:** Denotes the value of debit card transactions in Indian Rupees (₹).

## Usages

```javascript

!pip install selenium

from selenium import webdriver
from selenium.webdriver.chrome.options import Options
from selenium.webdriver.common.by import By
from urllib.parse import urljoin
import os
import requests



```


## Conclusion 1 

In the initial phase of the project, our focus was on organizing the data effectively. This involved using web scraping to collect the necessary information, followed by a meticulous data cleaning and restructuring process in Excel. The goal was to prepare the data for the subsequent task, which is creating visualizations



# Task2 
Debit cards usage dashboard:

![debit1](https://github.com/user-attachments/assets/2b28d323-3e1f-4f32-9eb2-746697c5bead)

Credit cards usage dashboard:

![credit1](https://github.com/user-attachments/assets/f8fd2e5d-4448-4dde-a281-c2450b59439c)

# Insights:
Total Usage insights for credit cards:

- Total transactions: 3,70 bn
- Total cards issued: 946 M
- Total market share: 13,45 T

Total usage insights for debit cards:

- Total transactions: 3,66 bn
- Total cards issued: 946 M
- Total market share: 6,56 T

Cards usage trends:

- Debit cards: The top three banks interms of total spend vs total transactions are: State bank of india, HDFC bank ltd, Icici bank ltd. 
- Credit cards: The top three banks interms of total spend vs total transactions are: HDFC bank ltd, ICICI bank ltd State bank of india

Month-wise Analysis:
- Total spendind for credit cards was highest in march 2023.
- Total spendind for debit cards was highest in october 2022.
- The total number of credit/debit cards issued peaked in march 2023

## Conclusion 2
This project illustrates how data analysis can uncover financial trends. Through web scraping, data cleaning and visualization techniques, we gained valuable insights into credit and debit card usage across various banks and types. The dashboards offer an interface to explore usage trends, facilitating improved decision-making for finance industry stakeholders.

## License

Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License. See LICENSE for more information 


## Authors

- [Lamia Oualili](https://github.com/lamiaoua)

