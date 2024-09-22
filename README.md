
![1689955599097](https://github.com/kbay/Indian-Start-up-Funding-Analysis-2018-2021/assets/78024760/5ffd69d9-9b8f-429e-a465-4c0d51baeec0)

# Indian Start-up Funding Analysis (2018 - 2021)
## Data Analysis Project

## Project Description:
This project aims to analyze the funding trends of Indian start-ups from 2018 to 2021. By examining the data on start-up funding across these years, the project will identify key patterns, investment behaviors, and emerging sectors within the Indian start-up ecosystem. The analysis will provide insights into the types of industries receiving the most investment, the most active investors, the average funding amounts, and the geographical distribution of funded start-ups. The findings will guide strategic decisions for entering the Indian start-up market.

**Column names and description:**

- **Company/Brand**: Name of the company/start-up
- **Founded**: Year start-up was founded
- **Sector**: Sector of service
- **What it does**: Description about Company
- **Founders**: Founders of the Company
- **Investor**: Investors
- **Amount($)**: Raised fund
- **Stage**: Round of funding reached

**Hypotheses:**
- **Null Hypothesis (H0)**: The funds a company receives does not depend on the sector_Group the company invests in.
- **Alternative Hypothesis (H1)**: The funds a company receives depends on the sector_Group a company invests in.

## Business Questions
1. Does the funding a start-up receives depend on its sector group?
2. Which industries have received the most funding in each year, and how has this distribution changed over time?
3. What are the average funding amounts for different funding stages (e.g., Seed, Series A, Series B, etc.) each year?
4. How does funding for start-ups vary within the various geographical locations?
5. What is the relationship between the number of investors and the amount of funding received by startups?

## Steps in the Analysis
### Data Loading:
- Load data from CSV files for each year from 2018 to 2021.
- Additional data may be loaded from a database for comprehensive analysis.

### Data Cleaning:
- Clean the data by handling missing values, correcting data formats, and standardizing data entries.

### Data Analysis:
- Perform statistical analyses to understand investment types, key sector players, and regional funding trends.
- Generate insights on the growth and challenges within the startup ecosystem.

### Data Visualization:
- Use Matplotlib and Seaborn to visualize data through various charts and graphs to illustrate the trends and insights derived from the analysis.

#### [Power BI Link](https://app.powerbi.com/view?r=eyJrIjoiNjg2MTI2MDMtM2JjMi00ZDliLWEyY2EtYTU2YTNjNGM4ZDZjIiwidCI6IjQ0ODdiNTJmLWYxMTgtNDgzMC1iNDlkLTNjMjk4Y2I3MTA3NSJ9 )

![Screenshot 2024-06-10 120926](https://github.com/kbay9/Indian-Start-up-Funding-Analysis-2018-2021/assets/78024760/77251849-14a9-438b-9721-10a419c0656d)

## Usage
To run this analysis, follow these steps:

```bash
pip install -r requirements.txt
git clone https://github.com/your-username/indian-startup-funding.git
cd indian-startup-funding
jupyter notebook main.ipynb
```

## Technologies Used
This project utilizes several technologies and libraries in Python to manage data operations, perform statistical analysis, and visualize trends:
- **pyodbc**: Used for connecting to databases using ODBC drivers, allowing data extraction from various database systems directly into Python for analysis.
- **dotenv**: Facilitates the loading of environment variables from a `.env` file into the Python script. This is crucial for managing sensitive data such as database credentials without hardcoding them into the source code.
- **Pandas**: A powerful data manipulation and analysis library for Python. It is used extensively for data cleaning, transformation, and preparation tasks.
- **NumPy**: Essential for numerical operations on large, multi-dimensional arrays and matrices in Python. It provides support for a wide range of mathematical functions to operate on these arrays.
- **re (Regular Expressions)**: Utilized for data cleaning and preprocessing to find, match, and manipulate text patterns in the data.
- **Matplotlib**: A foundational plotting library in Python, used for creating static, interactive, and animated visualizations in Python.
- **Seaborn**: Built on top of Matplotlib, it provides a high-level interface for drawing attractive and informative statistical graphics. This library simplifies many complex visualization tasks.

### Data Visualization Tools
For data visualization, this project employs Matplotlib and Seaborn to create a variety of charts and graphs that illustrate the trends and insights derived from the analysis. These visualizations include line plots, bar charts, histograms, among others.


## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any queries regarding this project, please contact:

Kobena Badu Enyam - kobenaenyam@gmail.com

Thank you for visiting this repository, and we hope you find the data insights useful!
