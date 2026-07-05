# COVID-19 Data Analysis using Pandas

## Project Overview

This project performs a complete Exploratory Data Analysis (EDA) on the **Worldometer Coronavirus Summary Dataset** using **Python**, **Pandas**, **Matplotlib**, and **Seaborn** in **Google Colab**.

The objective is to clean the dataset, analyze COVID-19 statistics, visualize key trends, and generate meaningful insights through data analysis.

---

## Dataset

**Dataset:** `worldometer_coronavirus_summary_data.csv`

The dataset contains COVID-19 statistics for various countries, including:

* Country Name
* Total Cases
* Total Deaths
* Total Recovered
* Active Cases
* Total Tests
* Population
* Other COVID-19 related statistics

---

## Technologies Used

* Python 3
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Project Workflow

### Step 1: Load & Inspect Data

* Imported dataset using Pandas
* Checked dataset shape
* Inspected data types
* Identified missing values
* Detected duplicate records
* Generated descriptive statistics

---

### Step 2: Data Cleaning

Performed the following preprocessing steps:

* Removed duplicate rows
* Removed unnecessary columns
* Converted numeric columns to proper data types
* Filled missing numerical values using the median
* Filled missing categorical values with "Unknown"
* Prepared the dataset for analysis

---

### Step 3: Exploratory Data Analysis (EDA)

The following questions were answered:

1. Which countries have the highest total COVID-19 cases?
2. Which countries have the highest number of deaths?
3. What are the overall descriptive statistics of the dataset?
4. Which continent has the highest number of cases? (if available)
5. Which countries conducted the highest number of COVID-19 tests?

---

### Step 4: Data Visualization

The project includes six different visualization types:

*  Bar Chart
*  Line Chart
*  Histogram
*  Scatter Plot
*  Pie Chart
*  Correlation Heatmap

Each chart includes appropriate titles, axis labels, and readable formatting.

---

### Step 5: Insights

Key insights derived from the analysis include:

* Countries with the highest COVID-19 cases.
* Relationship between total cases and deaths.
* Distribution of COVID-19 cases across countries.
* Correlation among numerical variables.
* Contribution of the top affected countries to global cases.

---

##  Project Structure

```
COVID-19-Data-Analysis/
│
├── worldometer_coronavirus_summary_data.csv
├── ExploratoryDataAnalysis.ipynb
├── README.md
```

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/COVID-19-Data-Analysis.git
```

2. Open the project in **Google Colab** or **Jupyter Notebook**.

3. Install the required libraries if needed.

```bash
pip install pandas numpy matplotlib seaborn
```

4. Run the notebook cells sequentially.

---

## Sample Output

The notebook generates:

* Dataset summary
* Cleaned dataset
* Statistical analysis
* Six visualizations
* Business insights

---

## Learning Outcomes

This project demonstrates:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Analysis using Pandas
* Python Programming for Data Analytics

---

## License

This project is created for educational and learning purposes.

---

## Author

**Kushal L K**

GitHub: https://github.com/Kushal0410
