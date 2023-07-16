# ⭐️ Cryptocurrency Web Scraper

<p align="center">
  <img src="https://github.com/gordonkwokkwok/Cryptocurrency-Web-Scraper/assets/112631794/bcd5da48-16df-462b-9401-5ab7aea8b6ea" alt="Cryptocurrency" width="700">
</p>

## 📚 Introduction
This project aims to collect and analyze data on the top 10 cryptocurrencies from CoinMarketCap. Using Python, the project extracts data on a weekly basis, starting from April 28, 2013, up until July 9, 2023. The extraction process involves scraping the cryptocurrency data for each specific date and storing it in a DataFrame. The collected data is then transformed through cleaning, formatting, and imputation of missing values. Finally, the project loads the processed data for further analysis. The analysis includes time series analysis, correlation analysis, trend analysis, volatility analysis, comparative analysis, and even predictive analysis. By utilizing web scraping techniques and data analysis tools, this project provides valuable insights into the behavior and performance of the top cryptocurrencies over time.

## 🎯 Objective
- Collect and Extract Data: Scrape and extract data on the top 10 cryptocurrencies from CoinMarketCap on a weekly basis from April 28, 2013, to July 9, 2023.

- Clean and Format Data: Ensure data accuracy and consistency by performing cleaning and formatting tasks, including handling missing values and standardizing data formats.

- Analyze Cryptocurrency Trends: Identify and analyze trends and patterns in the performance of the top cryptocurrencies, such as price fluctuations, market capitalization, and trading volume over time.

- Predict Future Trends: Utilize the collected data to develop predictive models that can forecast future trends in the cryptocurrency market, aiding in decision-making for investments or trading strategies.

## 🔍 About the Scraped Dataset
| Column Name       | Description                                                                                |
|-------------------|--------------------------------------------------------------------------------------------|
| Date              | The date on which the data was recorded.                                                   |
| Name              | The name of the cryptocurrency.                                                            |
| Symbol            | The symbol representing the cryptocurrency.                                                 |
| Market Cap        | The total value of all coins of a particular cryptocurrency.                               |
| Price             | The price of a single unit of the cryptocurrency.                                          |
| Circulating Supply| The number of coins that are circulating in the market and are in public hands.             |
| Volume (24hr)     | The total volume of the cryptocurrency traded in the last 24 hours.                        |
| % 1h              | The percentage change in price over the last hour.                                         |
| % 24h             | The percentage change in price over the last 24 hours.                                     |
| % 7d              | The percentage change in price over the last 7 days.                                       |

## 📋 Prerequisite
Creating a virtual environment is recommended for projects, and either venv or conda can be used based on personal preference. After creating the virtual environment, it is necessary to activate it before installing any required libraries. This project created a virtual environment called "cantekEnv"

### 🔧 Tool
- Python (Version: 3.9.6)
- Git (Version: 2.23.0)

Use following command to check version
```
python --version
git --version
```

### 📖 Library
Use following command to install the following libraries:
```
pip3 install requests
pip3 install beautifulsoup4
pip3 install requests_html

pip3 install numpy
pip3 install pandas
pip3 install matplotlib
pip3 install tensorflow
```

## ⚙️ Command to run the project:
```
conda activate cantekEnv
jupyter notebook
```

## 🌐 Scraped Dataset
- [Link](https://github.com/gordonkwokkwok/Cryptocurrency-Web-Scraper/blob/main/output.csv)

## 👥 Contributer
- [Gordon Kwok](https://www.linkedin.com/in/gordonkwokch/)

## 🤝 Acknowledgments

I would like to express our gratitude to the following individuals and organizations for their contributions and support in making this project possible:


- Will: an instructor of the course, provided valuable guidance, mentorship, and expertise throughout the project. His support was instrumental in shaping the direction of the project and ensuring its success.
- [Cantek IT Program](https://www.cantekcanada.com/): Cantek IT Program, an educational institution, played a significant role in supporting the project. They provided resources, facilities, and a conducive learning environment for the team to work on the project.

I am thankful for their valuable input, feedback, and assistance throughout the development process. Their expertise and dedication have greatly enhanced the quality and functionality of this project.

## 💪 Support
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/gordonhei25)

Give a ⭐️ if this project helped you!

<p align="center">
  <img src="https://github.com/gordonkwokkwok/Cryptocurrency-Web-Scraper/assets/112631794/33a3d07a-5e38-489e-b577-5177fb049aa0" alt="bitcoin" width="150">
</p>
