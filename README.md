<!-- ===================================================== -->
<!--  CPE310 – FUNDAMENTALS OF DATA SCIENCE (IE22S1)        -->
<!--  DARK CYBER • FULL COURSE README                      -->
<!-- ===================================================== -->

<h1 align="center" style="font-family: monospace; color:#58a6ff;">
⚡ CPE310 — FUNDAMENTALS OF DATA SCIENCE
</h1>

<h3 align="center" style="font-family: monospace; color:#8b949e;">
IE22S1 | Data • Code • Patterns • Intelligence
</h3>

<p align="center">
  <img src="https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif" width="520">
</p>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🌌 WHAT IS DATA SCIENCE?
</h2>

<p style="font-family: monospace;">
<b>Data Science</b> is about using data to understand problems and make smart decisions.
It turns raw numbers into useful knowledge.
</p>

<pre>
📊 Data = raw facts
🧠 Insight = meaning from data
🎯 Goal = better decisions
</pre>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🔁 THE DATA SCIENCE PIPELINE
</h2>

<pre>
📥 COLLECT DATA
      ↓
🧹 CLEAN DATA
      ↓
🔍 EXPLORE DATA
      ↓
📊 VISUALIZE DATA
      ↓
🤖 BUILD MODELS
      ↓
📢 SHARE INSIGHTS
</pre>

<p>
💡 Fun fact: Data scientists spend about <b>70%</b> of their time cleaning data.
</p>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🛠 TOOLS USED IN THIS COURSE
</h2>

<pre>
🐍 Python        → main programming language
📓 Jupyter       → code + results together
📊 Pandas        → tables (DataFrames)
📈 Matplotlib    → charts & graphs
🤖 Scikit-learn  → machine learning
🗂 GitHub        → save & share work
</pre>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🐍 PYTHON & DATAFRAME EXAMPLE
</h2>

<pre>
import pandas as pd

data = {
    "Name": ["Ana", "Ben", "Cara", "Dan", "Eli"],
    "Score": [85, 90, 78, 92, 88]
}

df = pd.DataFrame(data)
print(df)

average = df["Score"].mean()
highest = df["Score"].max()
lowest = df["Score"].min()

print("Average:", average)
print("Highest:", highest)
print("Lowest:", lowest)
</pre>

<p>
📌 A <b>DataFrame</b> is simply a table with rows and columns.
</p>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
📊 DATA VISUALIZATION
</h2>

<pre>
import matplotlib.pyplot as plt

plt.bar(df["Name"], df["Score"], color="cyan")
plt.title("Student Scores")
plt.xlabel("Student")
plt.ylabel("Score")
plt.show()
</pre>

<p>
📈 Charts help us see patterns faster than numbers alone.
</p>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🤖 SIMPLE MACHINE LEARNING
</h2>

<pre>
from sklearn.linear_model import LinearRegression

X = [[1], [2], [3], [4], [5]]
y = [2, 4, 6, 8, 10]

model = LinearRegression()
model.fit(X, y)

prediction = model.predict([[6]])
print("Prediction for X=6:", prediction)
</pre>

<p>
🤖 Machine learning lets computers learn patterns from data.
</p>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🎯 MINI CHALLENGES
</h2>

<pre>
CHALLENGE 1:
Add a column called "Passed" (Score ≥ 85).

CHALLENGE 2:
Sort the table from highest score to lowest.

CHALLENGE 3:
Change the bar chart into a line chart.

CHALLENGE 4:
Predict the value when X = 7.
</pre>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🧩 QUICK QUIZ
</h2>

<pre>
1) What is a DataFrame?
A) A chart
B) A table of data
C) A model

2) What comes first?
A) Modeling
B) Visualization
C) Data Collection

3) True or False:
Clean data gives better results.
</pre>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🤯 INTERESTING DATA FACTS
</h2>

<pre>
📌 Netflix uses data to recommend shows
📌 One wrong value can break analysis
📌 Charts explain faster than tables
📌 Python is one of the most used data languages
📌 Data science mixes logic and creativity
</pre>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🌍 WHERE DATA SCIENCE IS USED
</h2>

<pre>
🏦 Finance
🏥 Healthcare
🛒 Online Shopping
📱 Mobile Apps
🎮 Games
🤖 Artificial Intelligence
</pre>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🚀 WHY CPE310 MATTERS
</h2>

<pre>
✔ Learn how to think with data
✔ Solve real-world problems
✔ Prepare for AI and ML
✔ Build future-ready skills
</pre>

<hr>

<p align="center">
<i>“Data is powerful. Understanding data is a superpower.”</i>
</p>

<p align="center">
🚀 <b>Welcome to CPE310 — where raw data becomes insight.</b>
</p>
