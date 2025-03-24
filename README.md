# San Francisco Salaries Dataset Analysis

## Overview
This project analyzes the **San Francisco Salaries Dataset**, exploring salary distributions, job roles, overtime trends, and other financial aspects of public employee wages.

## Dataset
The dataset contains information about:
- **Employee Name**
- **Job Title**
- **Base Pay**
- **Overtime Pay**
- **Other Pay**
- **Total Pay & Benefits**
- **Year**

## Objectives
- **Data Cleaning & Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Salary Trend Analysis**
- **Overtime Impact on Total Pay**
- **Top-Paid Job Titles**
- **Predicting Salary Trends**

## Prerequisites
Ensure you have the following installed:
- Python (>= 3.7)
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-Learn (for predictions, if needed)

### Installation
Install the required dependencies:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Getting Started
Clone this repository and navigate to the project folder:
```sh
git clone https://github.com/yourusername/San-Francisco-Salaries-Dataset.git
cd San-Francisco-Salaries-Dataset
```

### Running the Analysis
1. **Data Preprocessing & Cleaning**
   ```sh
   python data_cleaning.py
   ```
2. **Exploratory Data Analysis (EDA)**
   ```sh
   python eda.py
   ```
3. **Salary Prediction (Optional)**
   ```sh
   python salary_prediction.py
   ```

## Example Code
### Loading the Dataset
```python
import pandas as pd

data = pd.read_csv("data/SF_Salaries.csv")
print(data.head())
```

### Analyzing Salary Distribution
```python
import matplotlib.pyplot as plt
import seaborn as sns

sns.histplot(data["TotalPay"], bins=50, kde=True)
plt.title("Distribution of Total Pay")
plt.show()
```

## Project Structure
```
.
├── data/                     # Dataset
├── notebooks/                # Jupyter Notebooks
├── scripts/                  # Python scripts for analysis
├── results/                  # Output visualizations
├── README.md                 # Documentation
└── requirements.txt          # Dependencies
```

## Insights
- Identified **highest-paid job titles** in San Francisco.
- Analyzed trends in **overtime pay vs base salary**.
- Found patterns in **salary growth over years**.

## Contributing
1. Fork the repository
2. Create a new branch (`feature-name`)
3. Commit changes (`git commit -m "Added salary trend analysis"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions, open an issue or reach out on [LinkedIn](https://www.linkedin.com/in/your-profile).

