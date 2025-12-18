<!-- ===================================================== -->
<!--  CPE310 – FUNDAMENTALS OF DATA SCIENCE (IE22S1)        -->
<!--  DARK CYBER DATA SCIENCE THEME                        -->
<!-- ===================================================== -->

<div style="background-color:#0d1117; color:#c9d1d9; padding:20px;">

<h1 align="center" style="font-family: monospace; color:#58a6ff;">
⚡ CPE310 — FUNDAMENTALS OF DATA SCIENCE
</h1>

<h3 align="center" style="font-family: monospace; color:#8b949e;">
IE22S1 | Data • Code • Intelligence
</h3>

<p align="center">
  <img src="https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif" width="520">
</p>

<hr style="border:1px solid #30363d;">

<h2 style="font-family: monospace; color:#7ee787;">
🧠 WHAT IS DATA SCIENCE?
</h2>

<p style="font-family: monospace;">
<b>Data Science</b> means using data to understand the world.
It helps answer questions like:
</p>

<pre style="background:#161b22; color:#c9d1d9; padding:15px;">
• What is happening?
• Why is it happening?
• What may happen next?
</pre>

<p align="center">
  <img src="https://media.giphy.com/media/3oKIPEqDGUULpEU0aQ/giphy.gif" width="420">
</p>

<hr style="border:1px solid #30363d;">

<h2 style="font-family: monospace; color:#7ee787;">
🔁 THE DATA SCIENCE FLOW
</h2>

<pre style="background:#161b22; color:#c9d1d9; padding:15px; font-size:15px;">
📥 COLLECT DATA
      ↓
🧹 CLEAN DATA
      ↓
🔍 EXPLORE DATA
      ↓
📊 VISUALIZE DATA
      ↓
🤖 SIMPLE MODELS
      ↓
📢 SHARE INSIGHTS
</pre>

<p style="font-family: monospace;">
Most data is messy. Cleaning data is the <b>hardest</b> and <b>most important</b> step.
</p>

<hr style="border:1px solid #30363d;">

<h2 style="font-family: monospace; color:#7ee787;">
🛠 PYTHON IN DATA SCIENCE
</h2>

<p style="font-family: monospace;">
Python is the main language used in this course.
Below is a simple example.
</p>

```python
import pandas as pd

# Create a small dataset
data = {
    "Student": ["Ana", "Ben", "Cara", "Dan"],
    "Score": [85, 90, 78, 92]
}

df = pd.DataFrame(data)

# Show the data
df

<p style="font-family: monospace;"> This code creates a table and displays it. </p> <hr style="border:1px solid #30363d;"> <h2 style="font-family: monospace; color:#7ee787;"> 📊 SIMPLE DATA VISUALIZATION </h2>

import matplotlib.pyplot as plt

plt.bar(df["Student"], df["Score"])
plt.title("Student Scores")
plt.xlabel("Student")
plt.ylabel("Score")
plt.show()

<p style="font-family: monospace;"> Charts help us <b>see patterns</b> quickly. </p> <hr style="border:1px solid #30363d;"> <h2 style="font-family: monospace; color:#7ee787;"> 🎯 MINI CHALLENGES </h2> <pre style="background:#161b22; color:#c9d1d9; padding:15px;"> 🔹 CHALLENGE 1 Change the scores and add one more student. 🔹 CHALLENGE 2 Find the average score using Python. 🔹 CHALLENGE 3 Change the chart color and title. 🔹 CHALLENGE 4 Which student has the highest score? </pre> <hr style="border:1px solid #30363d;"> <h2 style="font-family: monospace; color:#7ee787;"> 🤯 DATA SCIENCE FACTS </h2> <pre style="background:#161b22; color:#c9d1d9; padding:15px;"> 📌 Data scientists spend more time cleaning than modeling 📌 One good chart can explain a whole dataset 📌 Bad data leads to bad decisions 📌 Python is one of the most used data languages </pre> <hr style="border:1px solid #30363d;"> <h2 style="font-family: monospace; color:#7ee787;"> 🚀 WHY THIS COURSE MATTERS </h2> <p style="font-family: monospace;"> Data skills are useful in almost every field today. </p> <pre style="background:#161b22; color:#c9d1d9; padding:15px;"> ✔ Builds logical thinking ✔ Teaches problem-solving ✔ Prepares you for AI and ML ✔ Useful for future jobs </pre> <hr style="border:1px solid #30363d;"> <p align="center" style="font-family: monospace; color:#8b949e;"> <i>“In data we trust. In insight we decide.”</i> </p> <p align="center" style="font-family: monospace; color:#58a6ff;"> 🚀 <b>Welcome to CPE310 — enter the data world.</b> </p> </div> ```
