# Titanic-Passengers-data-extraction-and-cleaning
In this file we have extracted the data of titanic passengers using "titanic.csv"

This notebook loads the Titanic dataset and produces several exploratory plots using pandas and matplotlib.

What the notebook does
- Loads the dataset from 'titanic.csv' into a pandas DataFrame (`Dataset`).
- Shows the raw DataFrame.
- Visualizes passenger survival as a bar chart (counts of `Survived`).
- Shows passenger class distribution (bar chart of `Pclass`).
- Plots age distribution as a histogram (uses `Age.fillna(0)`).
- Plots gender distribution as a pie chart (counts of `Sex`).
- Visualizes number of siblings/spouses and parents/children aboard (bar charts on `Siblings/Spouses Aboard` and `Parents/Children Aboard`).
- Plots fare distribution as a histogram (uses `Fare.fillna(0)`).
