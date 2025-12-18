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
<b>Data Science</b> is the practice of using data to understand problems and make better decisions.
It turns raw numbers into useful knowledge.
</p>

<pre style="font-family: monospace;">
📊 Data = raw facts
🧠 Insight = meaning from data
🎯 Goal = better decisions
</pre>

<p align="center">
  <img src="https://media.giphy.com/media/3oKIPEqDGUULpEU0aQ/giphy.gif" width="420">
</p>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🔁 THE DATA SCIENCE PIPELINE
</h2>

<pre style="font-family: monospace; font-size: 15px;">
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

<p style="font-family: monospace;">
💡 <b>Fact:</b> 70% of a data scientist’s time is spent cleaning data.
</p>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🛠 TOOLS USED IN THIS COURSE
</h2>

<table>
  <tr>
    <th style="font-family: monospace;">Tool</th>
    <th style="font-family: monospace;">Purpose</th>
  </tr>
  <tr>
    <td>🐍 Python</td>
    <td>Main programming language</td>
  </tr>
  <tr>
    <td>📓 Jupyter Notebook</td>
    <td>Code + output in one place</td>
  </tr>
  <tr>
    <td>📊 Pandas</td>
    <td>Work with tables (DataFrames)</td>
  </tr>
  <tr>
    <td>📈 Matplotlib / Seaborn</td>
    <td>Create charts and graphs</td>
  </tr>
  <tr>
    <td>🤖 Scikit-learn</td>
    <td>Machine learning models</td>
  </tr>
  <tr>
    <td>🗂 GitHub</td>
    <td>Store and share projects</td>
  </tr>
</table>

<hr>

<h2 style="font-family: monospace; color:#7ee787;">
🐍 PYTHON + DATAFRAME BASICS
</h2>

```python
import pandas as pd

data = {
    "Name": ["Ana", "Ben", "Cara", "Dan", "Eli"],
    "Score": [85, 90, 78, 92, 88]
}

df = pd.DataFrame(data)
df

# Basic statistics
df["Score"].mean(), df["Score"].max(), df["Score"].min()

<p style="font-family: monospace;"> 📌 A <b>DataFrame</b> is a table made of rows and columns. </p> <hr> <h2 style="font-family: monospace; color:#7ee787;"> 📊 DATA VISUALIZATION </h2>

import matplotlib.pyplot as plt

plt.figure(figsize=(6,4))
plt.bar(df["Name"], df["Score"], color="cyan")
plt.title("Student Scores")
plt.xlabel("Student")
plt.ylabel("Score")
plt.show()

<p style="font-family: monospace;"> 📈 Charts help us understand data faster than numbers alone. </p> <hr> <h2 style="font-family: monospace; color:#7ee787;"> 🤖 INTRODUCTION TO MACHINE LEARNING </h2>

from sklearn.linear_model import LinearRegression

# Simple dataset
X = [[1], [2], [3], [4], [5]]
y = [2, 4, 6, 8, 10]

model = LinearRegression()
model.fit(X, y)

prediction = model.predict([[6]])
prediction

<p style="font-family: monospace;"> 🤖 Machine learning lets computers learn patterns from data. </p> <hr> <h2 style="font-family: monospace; color:#7ee787;"> 🎯 MINI CHALLENGES </h2> <pre style="font-family: monospace;"> CHALLENGE 1: Add a new column called "Passed" (Score ≥ 85). CHALLENGE 2: Sort the DataFrame by Score (highest to lowest). CHALLENGE 3: Change the chart to a line graph. CHALLENGE 4: Predict the score when X = 7 using the model. </pre> <hr> <h2 style="font-family: monospace; color:#7ee787;"> 🧩 QUICK QUIZ (TRY WITHOUT GOOGLE) </h2> <pre style="font-family: monospace;"> 1) What is a DataFrame? A) A chart B) A table of data C) A machine learning model 2) Which step comes first? A) Modeling B) Visualization C) Data Collection 3) True or False: Clean data always gives better results. </pre> <hr> <h2 style="font-family: monospace; color:#7ee787;"> 🤯 INTERESTING DATA SCIENCE FACTS </h2> <pre style="font-family: monospace;"> 📌 Netflix saves millions using data recommendations 📌 Self-driving cars learn from camera data 📌 One wrong value can break an entire analysis 📌 Data science mixes math, code, and creativity 📌 Python is one of the most loved data languages </pre> <hr> <h2 style="font-family: monospace; color:#7ee787;"> 🌍 WHERE DATA SCIENCE IS USED </h2> <p style="font-family: monospace;"> 🏦 Finance & Banking 🏥 Healthcare 🛒 Online Shopping 📱 Mobile Apps 🎮 Games 🤖 Artificial Intelligence </p> <hr> <h2 style="font-family: monospace; color:#7ee787;"> 🚀 WHY CPE310 MATTERS </h2> <pre style="font-family: monospace;"> ✔ Learn how to think with data ✔ Solve real-world problems ✔ Prepare for AI and ML courses ✔ Build job-ready skills </pre> <hr> <p align="center" style="font-family: monospace; color:#8b949e;"> <i>“Data is powerful. Understanding data is superpower.”</i> </p> <p align="center" style="font-family: monospace; color:#58a6ff;"> 🚀 <b>Welcome to CPE310 — where raw data becomes insight.</b> </p> ```
