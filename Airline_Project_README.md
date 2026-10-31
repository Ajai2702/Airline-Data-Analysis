# Airline Passenger Satisfaction Dashboard

## Project Overview

The **Airline Passenger Satisfaction Dashboard** analyzes airline passenger survey data to understand passenger experience and service quality. The project uses Python for data cleaning and exploratory data analysis (EDA), and a dashboard/report to present important satisfaction metrics and insights.

The analysis is based on **25,976 passenger records**.

## Objectives

- Analyze overall airline passenger satisfaction.
- Compare satisfaction across travel classes and travel purposes.
- Study satisfaction patterns across passenger age groups.
- Evaluate in-flight and other airline service ratings.
- Identify weak service areas and opportunities for improvement.

## Dataset

The project uses an airline passenger survey dataset containing passenger and flight details, including:

- Passenger age and gender
- Customer type
- Type of travel
- Travel class
- Flight distance
- Departure and arrival delays
- Service ratings, including Wi-Fi, seat comfort, food, entertainment and cleanliness
- Overall passenger satisfaction

**Dataset size used in the dashboard:** 25,976 passengers.

## Tools and Technologies

- **Python** – data analysis
- **Pandas** – data loading, cleaning and manipulation
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualizations
- **Jupyter Notebook** – analysis environment
- **Power BI** – dashboard/report project

## Project Workflow

1. Load the airline dataset.
2. Inspect the rows, columns, data types and summary information.
3. Check missing values, duplicate records and unusual values.
4. Clean the data by removing duplicates, dropping an unnecessary index column when present, and filling missing arrival-delay values with the median.
5. Perform exploratory data analysis (EDA).
6. Calculate passenger satisfaction percentages and service-rating averages.
7. Compare satisfaction by travel class, travel purpose and age group.
8. Visualize the findings and summarize the results in a dashboard/presentation.

## Key Findings

- **Total passengers:** 25,976
- **Satisfied passengers:** 11,403
- **Overall satisfaction rate:** 43.9%
- **Average departure delay:** 14.3 minutes
- **Business class satisfaction:** 69.5% (highest among the listed travel classes)
- **Eco Plus satisfaction:** 24.8%
- **Eco satisfaction:** 19.4%
- **Business travel satisfaction:** 58.8%
- **Personal travel satisfaction:** 10.0%
- **Highest satisfaction age group:** 45–54 years (58.1%)
- **Lowest average service rating:** Wi-Fi (2.72 out of 5)
- **Highest average service rating:** Seat comfort (3.45 out of 5)

The analysis also shows that satisfaction rises with higher Wi-Fi ratings. This is an observed association in the dataset and does not prove that Wi-Fi rating alone causes higher satisfaction.

## Project Files

- `Airline_Project.ipynb` – Python notebook containing data inspection, cleaning, EDA and visualizations.
- `Airlines cleaned` – cleaned airline dataset supplied with the project.
- `airline_project.zip` – Power BI report/project files.
- `Airlines_Project.pptx` – project presentation.
- `README.md` – project documentation.

## How to Run the Python Notebook

1. Install Python and Jupyter Notebook, or open the notebook in Google Colab.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Place the airline CSV dataset in the notebook's working folder.
4. Make sure the CSV filename and path match the notebook's data-loading line. The notebook currently reads:

   ```python
   df = pd.read_csv("/content/Airline.csv")
   ```

   If your file has a different name or location, update this path before running the notebook.

5. Open `Airline_Project.ipynb` and run the cells in order.

## Conclusion

This project highlights differences in passenger satisfaction across travel class, travel purpose and age groups. Wi-Fi received the lowest average service rating, making it an important area for airlines to review. The findings can help identify service improvements that may create a better passenger experience.

---

**Project:** Airline Passenger Satisfaction Dashboard  
**Category:** Data Analytics / Exploratory Data Analysis  
**Primary language:** Python
