# ET-MLAM-matplotib_CodeSaviours
📊 Complete Matplotlib Practice Notebook

A beginner-friendly, teacher-style Matplotlib practice notebook focused on understanding why different charts are used, what problem each chart solves, and how to create and customize visualizations in Python.

The notebook uses heavily commented examples and ends each main section with a practice exercise so you can apply what you learned.

📘 Notebook

Notebook: matplotlib_full_course_solved.ipynb

Language: Python

Format: Jupyter Notebook

Python version recorded in the notebook: 3.12.3

🎯 Learning Goals

By working through this notebook, you will learn:

Why data visualization is useful

How to choose an appropriate chart for a question

How to create line charts

How to compare multiple trends on one chart

How to create vertical, horizontal, and grouped bar charts

How to visualize distributions with histograms

How to explore relationships with scatter plots

How to show proportions with pie charts

How to create multi-chart dashboards with subplots

How to save charts as image files

How to customize and style Matplotlib figures

How to add annotations and customize axes

🗂️ Course Structure

0️⃣ Why Do We Visualize Data?

Introduces the purpose of visualization and explains how charts can make patterns, trends, outliers, and comparisons easier to identify than raw tables.

The notebook also introduces Matplotlib as a foundational Python plotting library and emphasizes an important principle:

Every chart should have one clear purpose.

1️⃣ Your First Plot — Line Chart

Purpose: Line charts are used to show how a value changes over a continuous range, especially over time.

The section introduces the fundamentals of creating a line plot and labeling it clearly.

Practice Exercise 1

You will:

Create hours from 1 to 10 and a list of 10 sales values.

Plot them as a line chart.

Add a title, x-axis label, and y-axis label.

Customize the line with:

Green color

Square markers (s)

Dotted linestyle (:)

2️⃣ Multiple Lines on One Chart

Purpose: Multiple lines allow you to compare two or more trends on the same chart.

The exercise uses monthly sales for three products and introduces the idea of using a legend to distinguish different lines.

Practice Exercise 2

Create three lists of six monthly sales values and plot all three products on the same chart with a legend.

3️⃣ Bar Charts — Comparing Categories

Purpose: Bar charts are appropriate for comparing discrete categories, such as products, countries, or other categorical groups.

The practice covers:

Vertical bar charts

Horizontal bar charts

Grouped bar charts

Practice Exercise 3

You will create:

A bar chart showing prices for five fruits.

A horizontal bar chart showing populations for five countries.

A grouped bar chart comparing 2020 and 2021 sales for four products.

4️⃣ Histograms — Understanding Distributions

Purpose: Histograms show how a single numeric variable is distributed across ranges, or bins.

The notebook specifically distinguishes histograms from bar charts:

Bar chart: compares separate categories.

Histogram: shows the distribution of one continuous numeric variable.

The examples use NumPy-generated random data.

Practice Exercise 4

You will:

Generate 500 normally distributed random numbers with:
np.random.normal(loc=50, scale=15, size=500)

Plot a histogram with 20 bins.

Compare the appearance using 5 and 100 bins.

5️⃣ Scatter Plots — Relationships Between Two Variables

Purpose: Scatter plots visualize the relationship between two numeric variables, where each point represents an observation.

The notebook uses the example of study time and exam scores to explain relationships between variables.

Practice Exercise 5

You will:

Create two related arrays with 40 points.

Generate values similar to y = 2*x + random noise.

Plot them as a scatter plot.

Customize the points with red color and alpha=0.5.

6️⃣ Pie Charts — Showing Proportions

Purpose: Pie charts show how categories contribute to a whole.

The notebook also gives a caution about pie charts: they can be difficult to compare accurately and are best kept to a small number of categories when emphasizing parts of a whole.

Practice Exercise 6

Create a pie chart showing how 24 hours are divided among:

Sleep

Study

Leisure

Other

Add percentage labels using autopct.

7️⃣ Subplots — Multiple Charts in One Figure

Purpose: Subplots allow several related charts to be displayed together, which is useful for dashboard-style visualizations.

Practice Exercise 7

Create a 1x2 subplot layout containing:

A line chart

A bar chart

Both charts should have titles, and the figure should use:

plt.tight_layout()

8️⃣ Saving Your Charts

Purpose: Charts often need to be exported for reports, presentations, websites, or other applications.

Practice Exercise 8

Recreate a chart from an earlier section and save it as a PNG file using:

dpi=200

9️⃣ Styling & Customization

Purpose: Styling and customization can improve the appearance and communication of a chart.

The notebook introduces concepts such as:

Matplotlib styles

Annotations

Custom axis limits

Figure customization

Practice Exercise 9

You will:

Apply the "ggplot" style.

Recreate a line chart.

Add an annotation pointing to the highest value.

Reset the style to "default" afterward.

🏆 Final Challenge — Class Performance Dashboard

The final challenge combines the visualization techniques covered throughout the notebook.

Scenario

Build a Class Performance Dashboard for a teacher using six students and their scores in:

Math

Science

English

Dashboard Requirements

Create a 2x2 subplot dashboard containing:

Top-left — Grouped Bar Chart

Compare all three subjects for all six students.

Top-right — Pie Chart

Show the contribution of each subject's class average to the total marks.

Bottom-left — Histogram

Display the distribution of all 18 scores combined.

Bottom-right — Scatter Plot

Plot:

Math score on the x-axis

Science score on the y-axis

Each point represents a student.

Figure Requirements

Add a main figure title:

fig.suptitle("Class Performance Dashboard")

Use:

plt.tight_layout()

to prevent overlap.

Finally, save the dashboard as:

class_dashboard.png

This challenge combines:

Bar charts

Pie charts

Histograms

Scatter plots

Subplots

Figure titles

Saving figures

📦 Dependencies

The notebook uses:

import matplotlib.pyplot as plt
import numpy as np
import matplotlib

Install the required packages with:

pip install matplotlib numpy jupyter

🚀 Getting Started

1. Install the dependencies

pip install matplotlib numpy jupyter

2. Start Jupyter Notebook

jupyter notebook

3. Open the notebook

Open:

matplotlib_full_course_solved.ipynb

4. Run the cells in order

Use:

Shift + Enter

to execute each cell.

The notebook is designed to be followed sequentially so that you can read the explanations, run the examples, and then attempt each practice exercise.

🧠 Recommended Learning Method

For the best learning experience:

Read the explanation before running the example.

Pay attention to the comments explaining the purpose of each operation.

Run the example and inspect the resulting chart.

Attempt each practice exercise yourself before looking at other solutions.

Experiment with different data, labels, styles, and chart settings.

Complete the final dashboard as a mini-project.

📊 Chart Selection Cheat Sheet

Chart

Main Purpose

Line chart

Show trends or changes over a continuous range

Multiple lines

Compare several trends

Bar chart

Compare discrete categories

Horizontal bar chart

Compare categories when horizontal labels are useful

Grouped bar chart

Compare multiple groups across categories

Histogram

Understand the distribution of one numeric variable

Scatter plot

Explore the relationship between two numeric variables

Pie chart

Show parts of a whole

Subplots

Display multiple related visualizations together

📈 Next Steps

After completing this notebook, the notebook recommends moving on to:

Seaborn — a statistical visualization library built on Matplotlib.

Pandas — for loading and working with real datasets.

Combining Pandas, NumPy, and Matplotlib to build visualizations from real-world data.

Building larger dashboards from datasets rather than manually created values.

Made with ❤️ for learning Matplotlib — practice daily, and you'll master it fast.
