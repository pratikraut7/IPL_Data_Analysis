# 🏏 IPL 2022 Data Analysis

## 📌 Project Overview

This project focuses on analyzing the Indian Premier League (IPL) 2022 season using Python and data analysis libraries. The aim is to explore team performance, match results, toss decisions, player achievements, batting performance, bowling statistics, and match venues.

The project uses Pandas for data manipulation and Matplotlib and Seaborn for data visualization.

## 🎯 Objectives

- Analyze the match-winning performance of different teams.
- Understand toss decisions and their impact on matches.
- Identify players with the most Player of the Match awards.
- Analyze batting performance and top scorers.
- Explore bowling performance and wicket-taking records.
- Visualize matches played at different venues.
- Perform exploratory data analysis (EDA) to discover useful insights.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Project Structure

```text
IPL_Data_Analysis/
│
├── IPL_2022_DA.ipynb
├── IPL_Dataset.csv
└── README.md
```

## 📊 Dataset Description

The dataset contains information about IPL 2022 matches, including match results, participating teams, toss decisions, scores, player awards, bowling figures, and venues.

Important columns include:

| Column | Description |
|---|---|
| `match_id` | Unique identifier for each match |
| `date` | Date of the match |
| `venue` | Stadium where the match was played |
| `team1` | First participating team |
| `team2` | Second participating team |
| `toss_winner` | Team that won the toss |
| `toss_decision` | Decision to bat or field |
| `first_ings_score` | First innings score |
| `second_ings_score` | Second innings score |
| `match_winner` | Team that won the match |
| `won_by` | Type of victory |
| `margin` | Victory margin |
| `player_of_the_match` | Player receiving the award |
| `top_scorer` | Top scorer recorded for the match |
| `highscore` | Highest individual score recorded |
| `best_bowling` | Bowler with the best bowling performance |

## 🔍 Analysis Performed

### 1. Data Loading and Exploration
- Imported the required libraries.
- Loaded the dataset using Pandas.
- Examined the dataset's rows, columns, and data types.
- Checked for missing values.

### 2. Team Performance Analysis
- Calculated the number of wins for each team.
- Compared team performances using bar charts.

### 3. Toss Decision Analysis
- Analyzed toss-winning teams and their decisions.
- Visualized the distribution of batting and fielding decisions.

### 4. Player of the Match Analysis
- Identified players who received the most awards.
- Compared award counts using bar charts.

### 5. Batting Performance Analysis
- Analyzed top scorers and recorded high scores.
- Used grouping and sorting to identify leading batting performances.

### 6. Bowling Performance Analysis
- Examined recorded bowling figures.
- Extracted wicket counts and compared aggregated performances.

### 7. Venue Analysis
- Counted matches played at different venues.
- Visualized venue distribution using pie charts and bar charts.

### 8. Custom Analysis
- Identified the highest recorded individual score.
- Examined the best recorded bowling figures.

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/pratikraut7/IPL_Data_Analysis.git
cd IPL_Data_Analysis
```

### Step 2: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

Open `IPL_2022_DA.ipynb` and run the cells sequentially.

Make sure the notebook loads the dataset using its relative path:

```python
import pandas as pd

df = pd.read_csv("IPL_Dataset.csv")
```

## 📈 Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Pandas filtering and aggregation
- GroupBy operations
- Sorting and ranking
- Data manipulation using NumPy
- Data visualization using Matplotlib and Seaborn
- Extracting insights from sports data

## 🚀 Future Improvements

- Analyze the relationship between toss decisions and match outcomes.
- Compare team performance across different venues.
- Explore batting and bowling trends in greater detail.
- Build an interactive IPL dashboard using Power BI.
- Add further visualizations and conclusions.

## 👨‍💻 Author

**Pratik Laxman Raut**

- GitHub: [pratikraut7](https://github.com/pratikraut7)
- LinkedIn: [Pratik Raut](https://linkedin.com/in/pratik-raut-942490273)

## 📄 License

This project is intended for educational purposes and data analysis practice.
