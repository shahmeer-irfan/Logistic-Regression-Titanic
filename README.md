
<body>

<h1>🚢 Titanic - Machine Learning from Disaster</h1>
<p>Predicting survival using logistic regression and sklearn.</p>

<h2>📁 Dataset</h2>
<ul>
  <li>Source: <a href="https://www.kaggle.com/c/titanic/data" target="_blank">Kaggle Titanic Dataset</a></li>
  <li>Target: <strong>Survived</strong></li>
  <li>Features: Pclass, Sex, Fare, Embarked, FamilySize</li>
</ul>

<h2>🛠️ Preprocessing</h2>
<ul>
  <li>Filled missing <code>Embarked</code> with mode</li>
  <li>Dropped <code>Cabin</code> and <code>Age</code></li>
  <li>Created <code>FamilySize = SibSp + Parch + 1</code></li>
  <li>One-Hot Encoding: <code>Sex</code>, <code>Embarked</code></li>
  <li>Scaled <code>Fare</code> using <code>RobustScaler</code></li>
</ul>

<h2>🤖 Model</h2>
<ul>
  <li><strong>Algorithm:</strong> Logistic Regression (sklearn)</li>
  <li><strong>Train/Test Split:</strong> 80/20</li>
  <li><strong>Accuracy:</strong> ~77%</li>
</ul>

<h2>📈 EDA</h2>
<ul>
  <li>Heatmap for correlation</li>
  <li>Countplots by survival, sex, class, and embarked</li>
</ul>

<h2>📎 Run Locally</h2>
<pre>
git clone https://github.com/yourusername/titanic-ml-logistic.git
cd titanic-ml-logistic
pip install -r requirements.txt
jupyter notebook
</pre>

<h2>📦 Requirements</h2>
<pre>
pandas
numpy
seaborn
matplotlib
scikit-learn
</pre>


</body>
</html>
