<h1>Admission Prediction System</h1>

<h2>Overview</h2>
<p>This project is an end-to-end Machine Learning system that predicts a student's chances of admission 
based on academic and profile parameters such as GRE score, TOEFL score, CGPA, SOP, LOR, 
university rating, and research experience.</p>
<p>Multiple regression models are implemented and compared to identify the best-performing model, 
along with a dynamic prediction system that supports a user-defined college name.</p>

<h2> Key Features</h2>
<ul>
  <li>Data preprocessing and cleaning</li>
  <li>Exploratory Data Analysis (EDA) with visualizations</li>
  <li>Feature scaling using StandardScaler</li>
  <li>Multiple regression models:
    <ul>
      <li>Linear Regression</li>
      <li>Lasso Regression</li>
      <li>Support Vector Regression (SVR)</li>
      <li>Decision Tree Regressor</li>
      <li>Random Forest Regressor</li>
      <li>K-Nearest Neighbors (KNN)</li>
    </ul>
  </li>
  <li>Model evaluation using RMSE and R² Score</li>
  <li>Tabular comparison of all models</li>
  <li>Dynamic prediction with user-defined college name</li>
</ul>

<h2>Tech Stack</h2>
<ul>
  <li>Python</li>
  <li>Pandas, NumPy</li>
  <li>Matplotlib, Seaborn</li>
  <li>Scikit-learn</li>
</ul>

<h2>Workflow</h2>
<ol>
  <li>Data Cleaning & Preprocessing</li>
  <li>Exploratory Data Analysis</li>
  <li>Feature Scaling</li>
  <li>Model Training (Multiple Algorithms)</li>
  <li>Model Evaluation & Comparison</li>
  <li>Prediction System</li>
</ol>

<h2>Output</h2>
<p>The model predicts admission probability in percentage format:</p>
<pre>Chance of getting into Harvard is: 94.12%</pre>

<h2>Note</h2>
<p>The model predicts admission chances based on academic features only and does not account for 
specific university admission policies. The college name is user-defined and used only for display purposes.</p>

<h2>Future Enhancements</h2>
<ul>
  <li>College-specific prediction system</li>
  <li>Hyperparameter tuning (GridSearchCV)</li>
  <li>Deployment using Flask / React</li>
  <li>Interactive UI</li>
  <li>Real-time prediction API</li>
</ul>

<h2>Example Usage</h2>
<pre>predict_admission("Harvard", [330, 115, 5, 5, 5, 9.8, 1])</pre>
