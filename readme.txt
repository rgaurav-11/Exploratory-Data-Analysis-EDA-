# Student Performance Exploratory Data Analysis (EDA)

This repository contains a Python script for performing exploratory data analysis (EDA) on a student performance dataset. The analysis helps to understand the distribution, relationships, and patterns within students' math, reading, and writing scores.

Features

- Summary statistics of the dataset  
- Histograms showing distributions of math, reading, and writing scores  
- Boxplots comparing score distributions across subjects  
- Correlation heatmap highlighting relationships between scores  
- Interactive scatter plot showing reading vs writing scores colored by gender  

 Tools Used

- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Plotly  

 How to Run

1. Clone the repository:
git clone https://github.com/yourusername/student-performance-eda.git
   cd student-performance-eda

2. Create and activate a virtual environment (optional but recommended):
python -m venv venv
.\venv\Scripts\activate

3. Install dependencies:
pip install -r requirements.txt

4. Place your dataset file studentsperformance.csv in the project directory.

5. Run the EDA script:

Dataset
The dataset should contain at least the following columns:

math score

reading score

writing score

gender (for interactive plot coloring)

If you don't have the dataset, a sample can be created or downloaded from relevant sources.


Output

The script will display various plots and statistics in the console and in pop-up windows:

Histograms

Boxplots

Correlation heatmap

Interactive scatter plot
