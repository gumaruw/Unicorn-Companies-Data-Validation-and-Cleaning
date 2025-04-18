# 🦄 Unicorn Companies Data Validation and Cleaning

> This project was completed as part of my scholarship in the Data Science program at the Artificial Intelligence and Technology Academy. It was undertaken within the scope of the "Go Beyond the Numbers: Translate Data into Insights" chapter of the Google Advanced Data Analytics course.

## 📊 Overview

In this project, I performed data validation and cleaning techniques on a dataset of unicorn companies — private companies with a valuation of over $1 billion. The goal was to prepare the data for analysis and gain insights into the business strategies of top unicorn investors.

## 📁 Dataset

- **Name:** `Unicorn_Companies.csv`
- **Source:** Kaggle
- **Rows:** 1,074 unicorn companies
- **Columns:** 10 (including company name, valuation, funding, industry, investors, etc.)

### Key Columns:

- `Company`: Name of the unicorn company  
- `Valuation`: Company valuation (in billions)  
- `Date Joined`: Date the company became a unicorn  
- `Industry`: Business industry  
- `Funding`: Total funding raised  
- `Year Founded`: Year the company was founded  
- `Select Investors`: Top investors  
- `Country/Region`, `Continent`, `City`: Geolocation details  

## 🛠 Technologies Used

- **Python**
- **Pandas**
- **Numpy**
- **Seaborn**
- **Matplotlib**
- **Jupyter Notebook**

## 🧪 Key Steps Taken

1. Cleaned and validated data (removed duplicates, fixed incorrect entries)
2. Converted categorical data to numerical values using label and dummy encoding
3. Created new columns for analysis (e.g., "Years to Unicorn")
4. Performed data transformation for better insights

## 📈 Example Insights

- Companies with quicker growth to unicorn status tend to have larger early funding rounds.
- North America has the highest concentration of unicorn companies, while Africa has the least.
- The "E-commerce & direct-to-consumer" industry has the highest number of unicorn companies.

## ✅ Outcome

By the end of this project, we were able to:

- Successfully clean and validate the dataset, ensuring its accuracy and consistency for analysis.
- Identify and fix data issues such as duplicates, missing values, and incorrect entries.
- Create new insightful features, such as the "Years to Unicorn," to better understand company growth patterns.
- Apply appropriate encoding techniques to convert categorical data into a format suitable for machine learning models.
- Gain actionable insights about unicorn companies, including industry trends, geographical distributions, and funding patterns, helping investors make informed decisions.

## 📌 How to Run

1. Clone the repository  
2. Open the Jupyter Notebook file  
3. Ensure that `Unicorn_Companies.csv` is in the same directory  
4. Run the notebook step-by-step

```bash
git clone https://github.com/gumaruw/Unicorn-Companies-Data-Validation-and-Cleaning.git
cd Unicorn-Companies-Data-Validation-and-Cleaning
jupyter notebook
```

## 📌 Additional Notes
This project demonstrates essential data cleaning, validation, and transformation techniques, which are crucial in preparing real-world data for analysis and machine learning models. Through this analysis, I gained insights into unicorn companies and their growth patterns, offering valuable data-driven insights for investors.

## ⚖️ License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
