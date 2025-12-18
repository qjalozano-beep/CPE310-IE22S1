




<!-- ===================================================== -->
<!--  CPE310 – FUNDAMENTALS OF DATA SCIENCE (IE22S1)        -->
<!--  DARK CYBER • FULL COURSE README                      -->
<!-- ===================================================== -->

<h2>👤 ABOUT ME</h2>

<p>
My name is <b>James Lozano</b> and I’m 19 years old. I am the coolest guy on Earth.  
I have <b>300 pesos</b> in my bank account, <b>100 problems</b>,  
<b>20 bad habits</b>, <b>5 pending assignments</b>, but at least I got the van. 🚐 ok corny
</p>

<p align="center">
  <img src="https://media1.tenor.com/m/VFshO4Ld52gAAAAd/michael-pena-but-i-got-the-van.gif" width="520">
</p>


## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/jamesezano) 

# 💻 Tech Stack:
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Riot Games](https://img.shields.io/badge/riotgames-D32936.svg?style=for-the-badge&logo=riotgames&logoColor=white) ![Steam](https://img.shields.io/badge/steam-%23000000.svg?style=for-the-badge&logo=steam&logoColor=white) ![Epic Games](https://img.shields.io/badge/epicgames-%23313131.svg?style=for-the-badge&logo=epicgames&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=qjalozano-beep&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=qjalozano-beep&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=qjalozano-beep&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=qjalozano-beep&icon=0&color=0)](https://visitcount.itsvg.in)


<h1 align="center" style="font-family: monospace; color:#58a6ff;">
⚡ CPE310 — FUNDAMENTALS OF DATA SCIENCE
</h1>

<h3 align="center" style="font-family: monospace; color:#8b949e;">
IE22S1 | Data • Code • Patterns • Intelligence
</h3>

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZWt2dThjMjdyNmMydzU5ZGlxMDgxd2s4YWNiMmtsMTd6cDVpazI1aCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/cInyJSYeuHw1Sduv8X/giphy.gif" width="520">
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

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZWt2dThjMjdyNmMydzU5ZGlxMDgxd2s4YWNiMmtsMTd6cDVpazI1aCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/V4NSR1NG2p0KeJJyr5/giphy.gif" width="520">
</p>


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
<h2>🧩 INTERACTIVE QUIZ (CLICK & CHECK)</h2>

<p><b>Quiz 1: What is a DataFrame?</b></p>

- [ ] A chart  
- [x] A table of data  
- [ ] A machine learning model  

<details>
<summary>✅ Show Answer</summary>
A DataFrame is a table with rows and columns.
</details>

<hr>

<p><b>Quiz 2: Which step comes FIRST in data science?</b></p>

- [x] Data Collection  
- [ ] Visualization  
- [ ] Modeling  

<details>
<summary>✅ Show Answer</summary>
Data must be collected before it can be analyzed.
</details>

<hr>

<p><b>Quiz 3: True or False</b></p>

- [x] True — Clean data gives better results  
- [ ] False  

<details>
<summary>✅ Show Answer</summary>
Clean data reduces errors and improves analysis.
</details>

<hr>

<h2>🎯 MINI CHALLENGES (TRY IN PYTHON)</h2>

- [ ] Add a new column called <b>Passed</b> (Score ≥ 85)  
- [ ] Sort the DataFrame by highest score  
- [ ] Change a bar chart into a line chart  
- [ ] Predict a value using the model  

<details>
<summary>💡 Hint</summary>
Use pandas conditions, <code>sort_values()</code>, and <code>plt.plot()</code>.
</details>

<hr>

<h2>🤯 BONUS FACT CHECK</h2>

- [ ] Data scientists spend most time modeling  
- [x] Data scientists spend most time cleaning data  

<details>
<summary>📊 Fact</summary>
About 60–70% of data science work is data cleaning.
</details>

<hr>

<p align="center">
<i>GitHub quizzes are self-check style — think, click, reveal.</i>
</p>

<p align="center">
🚀 <b>You are now thinking like a data scientist.</b>
</p>
