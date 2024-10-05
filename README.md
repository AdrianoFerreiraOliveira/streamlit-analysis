<h1>Streamlit Analysis</h1>

<p>This project is an interactive data analysis dashboard built using <strong>Streamlit</strong>. It allows users to explore and analyze datasets, offering real-time visualizations and insights. The primary dataset used in this project is the <code>bank-additional.csv</code>, which contains data from direct marketing campaigns of a banking institution.</p>

<h2>📂 Project Structure</h2>

<pre>
📂 streamlit-analysis
 ├── 📁 dataset                # Folder containing the dataset
 ├── 📁 .heroku                # Config files for Heroku deployment
 ├── app_7.py                  # Main Streamlit application
 ├── requirements.txt          # Python dependencies
 └── Procfile                  # Configuration file for deployment
</pre>

<h2>🔨 Features</h2>

<ul>
  <li>Interactive data visualizations and analysis using <strong>Streamlit</strong>.</li>
  <li>Allows custom dataset uploads for dynamic analysis.</li>
  <li>Real-time updates based on user inputs through Streamlit widgets.</li>
</ul>

<h2>📊 Dataset</h2>

<p>The dataset used for analysis (<code>bank-additional.csv</code>) includes information related to marketing campaigns. It contains various customer attributes such as demographic information, contact history, and marketing success rates.</p>

<h2>🛠️ How to Run the Project</h2>

<ol>
  <li>Clone this repository:
    <pre><code>git clone https://github.com/AdrianoFerreiraOliveira/streamlit-analysis.git</code></pre>
  </li>
  <li>Navigate to the project directory:
    <pre><code>cd streamlit-analysis</code></pre>
  </li>
  <li>Install the required dependencies:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li>Run the Streamlit app:
    <pre><code>streamlit run app_7.py</code></pre>
  </li>
</ol>

<h2>✔️ Technologies Used</h2>

<ul>
  <li><strong>Streamlit</strong>: Framework for building data apps.</li>
  <li><strong>Pandas</strong>: Data manipulation and analysis.</li>
  <li><strong>Heroku</strong>: Deployment platform for hosting the app.</li>
</ul>

<h2>🚀 Deployment</h2>

<p>The application can be deployed to <strong>Heroku</strong>. The <code>Procfile</code> and <code>requirements.txt</code> are configured for easy deployment. To deploy, follow the instructions on the Heroku website.</p>
