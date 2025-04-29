# 🎲 Random Dice & Marks Visualization 
This project contains two simple but illustrative data visualization tasks using Python's data science libraries: NumPy, Pandas, Seaborn, and Matplotlib. The visualizations include a simulation of dice rolls and a bar chart of students' marks across subjects.

## 📌 Features

Dice Roll Simulation
Simulates 100 dice rolls using numpy.random.randint.
Plots the frequency of each outcome (1 to 6) using seaborn.countplot.
Students' Marks Visualization
Reads student marks data from an Excel file (Marks.xlsx).
Transforms the data to long format using pandas.melt.
Displays a grouped bar chart for each student and their subject-wise marks.

## 📁 Files
main.py — Contains the visualization code.

Marks.xlsx — Excel file with students' marks (ensure this file exists in the same directory).

README.md — Project documentation.

## 🛠️ Requirements
Install the required Python packages before running the script:

```bash
pip install numpy pandas seaborn matplotlib openpyxl
```
## 🚀 Usage
Run the Python script:

```bash
python main.py
```

Make sure the Marks.xlsx file is present in the project directory.

## 📊 Output Samples
- Dice Simulation: Bar plot of dice face counts.
- Marks Chart: Colored bar chart showing subject-wise marks for each student.
### Author
- ankit yadav
