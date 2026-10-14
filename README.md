# 🏏 Cricket World Cup Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Cricket World Cup match data using Python. The objective is to explore historical match records, analyze team performance, understand scoring distributions, and identify meaningful patterns through data analysis and visualization.

The project demonstrates practical skills in data cleaning, preprocessing, statistical analysis, and data visualization using popular Python libraries.

## 🎯 Objectives

- Analyze Cricket World Cup match records.
- Identify the top 10 teams by recorded match wins.
- Explore and compare the scoring distributions of both teams.
- Investigate the relationship between Team 1 and Team 2 scores.
- Visualize match-win distribution across selected teams.
- Identify missing values and duplicate records.
- Extract useful date-related information for further analysis.

## 📂 Project Structure

```text
Cricket-World-Cup-EDA/
│
├── Worldcup EDA Project.ipynb
├── worldcup.csv
└── README.md
```

**Note:** The `worldcup.csv` dataset should be included in the repository if you have permission to share it.

## 🛠️ Technologies & Libraries Used

- **Python** – Programming language for data analysis.
- **Pandas** – Data manipulation and preprocessing.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical charts and visualization.
- **Jupyter Notebook** – Interactive environment for analysis.

## 📊 Dataset Overview

The dataset contains **454 match records and 15 original columns**, covering information related to Cricket World Cup matches.

The data includes information such as:

- Match dates and seasons
- Host countries and stadiums
- Participating teams
- Team scores
- Match winners
- Winning conditions and margins
- Tournament-related information

The notebook also creates additional columns for extracted numeric scores, year, and month during preprocessing.

## 🧹 Data Cleaning & Preprocessing

The following steps were performed:

1. Loaded the dataset using Pandas.
2. Inspected dataset information and column names.
3. Checked missing values in relevant columns.
4. Examined unique values and mode values for selected columns.
5. Handled missing entries in team score and winning-condition columns.
6. Converted match dates into datetime format.
7. Extracted year and month from match dates.
8. Extracted numeric run values from team score columns.
9. Checked for duplicate records.
10. Generated a statistical summary of the dataset.

## 📈 Data Visualization & Analysis

### 1. Bar Plot — Top 10 Teams by Match Wins

Analyzes recorded match wins to identify the leading teams in the dataset.

**Key Findings:**
- Australia recorded the highest number of wins, with 69.
- New Zealand ranked second, with 54 wins.
- India followed with 53 wins.
- South Africa recorded 38 wins among the selected teams.

### 2. Histogram — Distribution of Cricket Scores

Visualizes the distribution of numeric runs scored by the two teams.

**Key Findings:**
- Team 1 had 445 valid numeric score observations.
- Team 2 had 440 valid numeric score observations.
- Team 1's average score was approximately 238.22 runs.
- Team 2's average score was approximately 195.99 runs.
- The average-score difference was approximately 42.24 runs.

### 3. Scatter Plot — Team 1 Runs vs Team 2 Runs

Compares the scores of both teams to explore scoring patterns across matches.

**Purpose:**
- Identify matches with similar team scores.
- Observe differences between the two teams' scores.
- Explore the relationship between scoring performance.
- Highlight matches with substantially different scores.

### 4. Pie Chart — Cricket World Cup Match Wins by Team

Shows the distribution of recorded match wins among selected teams.

**Purpose:**
- Compare recorded wins across teams.
- Identify teams with larger shares of wins.
- Understand relative team performance within the selected group.

*Note: Recorded match wins are different from Cricket World Cup tournament titles.*

## 🔍 Key Insights

- Australia leads the recorded match-win comparison in this dataset.
- New Zealand and India have similar recorded win counts.
- Team 1 has a higher average recorded score than Team 2 in the analyzed data.
- Missing-value handling and date conversion help prepare the dataset for analysis.
- Visualizations make team performance and scoring patterns easier to understand.

## 🚀 How to Run This Project

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the Project Folder

```bash
cd Cricket-World-Cup-EDA
```

### Step 3: Install the Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Notebook

Open `Worldcup EDA Project.ipynb` and execute the notebook cells sequentially.

Make sure `worldcup.csv` is available in the correct directory before running the notebook.

## 💡 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Missing-Value Handling
- Data Type Conversion
- Statistical Analysis
- Data Visualization
- Python Programming
- Pandas and NumPy
- Matplotlib and Seaborn
- Analytical Thinking and Insight Generation

## DATA:
<img width="1477" height="721" alt="Screenshot 2026-10-14 163707" src="https://github.com/user-attachments/assets/1e754c26-8ea4-4091-b50c-28ed711539d2" />

---
## DATA:
<img width="1483" height="688" alt="Screenshot 2026-10-14 163720" src="https://github.com/user-attachments/assets/0ba344e8-12de-43ee-8aa8-6ab439bf3cc4" />

---
## DATA:
<img width="800" height="461" alt="Screenshot 2026-10-14 215729" src="https://github.com/user-attachments/assets/a7145303-667b-48e1-a8f6-66fe565edf31" />

---
## DATA:
<img width="1202" height="543" alt="Screenshot 2026-10-14 215746" src="https://github.com/user-attachments/assets/8939f7f0-03b4-4643-85f7-907f6c54b31f" />

---
## DATA:
<img width="1075" height="541" alt="Screenshot 2026-10-14 215756" src="https://github.com/user-attachments/assets/0c19a0a4-50cb-4698-8aab-cb145103031d" />

---
## DATA:
<img width="1459" height="525" alt="Screenshot 2026-10-14 215809" src="https://github.com/user-attachments/assets/bd0c981d-3dd7-4181-a6cd-520c2a53c162" />

---
## DATA:
<img width="1452" height="403" alt="Screenshot 2026-10-14 215822" src="https://github.com/user-attachments/assets/a221ba8b-9865-4763-a1e3-238b3d6ab1fe" />

---
## DATA:
<img width="1128" height="729" alt="Screenshot 2026-10-14 215843" src="https://github.com/user-attachments/assets/ff70d338-e055-44de-97ed-21670405503e" />

---
## DATA:
<img width="1396" height="690" alt="Screenshot 2026-10-14 215857" src="https://github.com/user-attachments/assets/725eed7b-27e5-479f-b3f4-761ebd0239d8" />

---
## DATA:
<img width="1431" height="650" alt="Screenshot 2026-10-14 215920" src="https://github.com/user-attachments/assets/a274d669-7be5-4d6a-90c7-d75372674efd" />

---
## DATA:
<img width="1433" height="405" alt="Screenshot 2026-10-14 215931" src="https://github.com/user-attachments/assets/e463a934-b849-4aea-bafc-8a91a6911d49" />

---
## DATA:
<img width="1358" height="675" alt="Screenshot 2026-10-14 215953" src="https://github.com/user-attachments/assets/afd00b09-c5ce-446a-9259-97942615c72a" />

---
## DATA:
<img width="1477" height="314" alt="Screenshot 2026-10-14 220003" src="https://github.com/user-attachments/assets/66f93813-988c-47ef-994a-79039b3322ac" />

---
