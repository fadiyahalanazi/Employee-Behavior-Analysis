# Analysis of Work Behavior of Hafr Al-Batin University Employees

## Abstract
This project analyzes employee work behavior at the University of Hafr Al-Batin using a data-driven approach.  
The study explores how demographic and job-related factors such as gender, qualifications, rank, and job title influence employee discipline and punctuality.  
The dataset consists of more than **73,000 records** of employee demographics and attendance data.  
Using data preprocessing, exploratory data analysis (EDA), and machine learning models, we provide insights and recommendations to support HR and management decision-making.

## Objectives
- Identify key demographic and job-related factors influencing employee discipline.  
- Apply machine learning models to predict employee behavior.  
- Visualize patterns and insights using dashboards.  
- Provide recommendations for HR policy and strategy development.  

## Dataset
- Source: University of Hafr Al-Batin employee and fingerprint records (approved for academic use).  
- Size: 73,035 entries, 10 columns.  
- Main columns:
  - **ID**: Unique identifier.  
  - **Date Time**: Timestamp of entry.  
  - **Sex**: Gender of employee.  
  - **Qualification**: Educational level.  
  - **Rank**: Employee’s job rank.  
  - **Job Title**: Position title.  
  - **Class**: Employment classification.  

## Methodology
1. **Data Preprocessing**
   - Merged fingerprint and employee information files.  
   - Converted all column names to English.  
   - Cleaned null values, removed duplicates, standardized text.  

2. **Exploratory Data Analysis (EDA)**
   - Attendance commitment by gender, qualification, rank, and job title.  
   - Monthly and weekly attendance patterns.  

3. **Machine Learning Models**
   - Random Forest Classifier.  
   - K-Nearest Neighbors (KNN).  
   - Evaluation metrics: Accuracy, Precision, Recall, F1-Score.  

## Results
- **Gender**: Females more punctual (52.79%) than males (47.21%).  
- **Qualification**: Bachelor’s degree holders highest in attendance (49.11%), Ph.D. lowest (0.17%).  
- **Rank**: Seventh (29.66%), Sixth (28.50%), and Eighth (20.51%) ranks most punctual.  
- **Job Title**: Assistant Director most disciplined (23.42%), Librarian least (1.56%).  
- **Model Performance**:
  - Random Forest: Accuracy ≈ 73%, Precision 0.74, Recall 0.73, F1-Score 0.72.  
  - KNN: Accuracy ≈ 69%.  

## Recommendations
- Enhance diversity and inclusion programs.  
- Review work policies to improve fairness and flexibility.  
- Expand professional training opportunities.  
- Conduct regular evaluations of HR policies.  
- Integrate AI and big data solutions for long-term HR strategy.  

## Tools and Technologies
- Python 3.8  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn (Random Forest, KNN)  
- Google Colab / Jupyter Notebook  
- Tableau (interactive dashboards)  

## Project Structure
```
Employee-Behavior-Analysis
 ┣ notebooks/               # Jupyter Notebook with code and analysis
 ┣ report/                  # Final report, presentation, and poster (PDFs)
 ┣ images/                  # Visualizations and dashboard screenshots
 ┣ data/                    # Sample or placeholder data (if allowed)
 ┣ README.md                # Project documentation
 ┗ requirements.txt         # Python libraries required
```

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/USERNAME/Employee-Behavior-Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook in Jupyter or Colab:
   ```bash
   jupyter notebook notebooks/Wegdan_Final_Project.ipynb
   ```
## Dashboard Results

The following dashboard provides an overview of the analysis conducted on employee behavior:

![Dashboard Results](images/dashboard_results.png)

## Author
Fadiah Suleiman Alanzi  
Data Science Graduate – University of Hafr Al-Batin
