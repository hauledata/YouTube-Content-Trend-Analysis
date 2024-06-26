<body>
    <h1>YouTube Content Trend Analysis</h1>
    <p>This project involves analyzing trends in YouTube content to understand what factors contribute to the popularity of videos. The analysis is performed using a dataset of YouTube video statistics.</p>
    <h2>Overview</h2>
    <p>The <strong>YouTube Content Trend Analysis</strong> project covers the following areas:</p>
    <ul>
        <li><strong>Data Collection</strong>: Downloading and loading the YouTube dataset.</li>
        <li><strong>Data Preparation</strong>: Cleaning and preprocessing the data for analysis.</li>
        <li><strong>Exploratory Data Analysis (EDA)</strong>: Visualizing and understanding the data through various plots and statistical summaries.</li>
        <li><strong>Trend Analysis</strong>: Identifying key trends and patterns in the data.</li>
    </ul>
  <h2>Applied Skills</h2>
<p>Data Analysis, Data Visualization, Market Research, YouTube Trend Awareness</p>
    <h2>Key Features</h2>
    <ul>
        <li><strong>Data Collection</strong>: The dataset is downloaded from Google Drive and loaded into a pandas DataFrame.</li>
        <li><strong>Data Preparation</strong>: Steps to clean and preprocess the data, including handling missing values and converting data types.</li>
        <li><strong>Exploratory Data Analysis (EDA)</strong>: Use of seaborn, matplotlib, and plotly for data visualization to explore trends in video views, likes, comments, and other metrics.</li>
        <li><strong>Statistical Analysis</strong>: Application of statistical tests to identify significant patterns.</li>
    </ul>
  <h2>Key Findings</h2>
<ul>
    <li><strong>Popular Content:</strong> Leveraging bar charts and histograms, we identified Entertainment and Music as the most popular genres, amassing over 5 billion subscribers.</li>
    <li><strong>YouTube Channel Trends:</strong> Employing line and scatter plots, we analyzed trends across YouTube channels from 2005 to 2023. While Entertainment and Music remained dominant, a gradual decline and saturation were observed from 2012 onwards.</li>
    <li><strong>Creator Demographics:</strong> Visualizing YouTube data with world maps and bar charts, we revealed the top four content creator countries: United States, India, Brazil, and the United Kingdom. These countries predominantly focus on Entertainment and Music content.</li>
</ul>

![country - category](https://github.com/hauledata/YouTube-Content-Trend-Analysis/assets/172208927/57321014-fa99-4949-a453-97ceb317bc68)
![newplot](https://github.com/hauledata/YouTube-Content-Trend-Analysis/assets/172208927/096d93ca-5b13-401f-8ec3-25957589c505)

<h2>Outcomes</h2>
<ul>
    <li>Provided valuable insights into YouTube content and trends for strategists and content creators.</li>
    <li>Supported informed decision-making regarding content strategies and investments for YouTube channels.</li>
</ul>
    <h2>Usage</h2>
    <p>Open the provided Jupyter Notebook file <code>YouTube Content Trend Analysis.ipynb</code> to explore the analysis. The notebook is organized into sections, allowing you to follow along with the data collection, preparation, EDA, and trend analysis.</p>
    <h3>Example Code</h3>
    <p>Here's a snippet of the initial setup in the notebook:</p>
    <pre><code>import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import gdown
import plotly.express as px
from datetime import datetime
from scipy import stats
import matplotlib.lines as mlines

### Download the dataset
file_id = "1PPVpY0Zxsnu3gRx2hNIvP_wONvwquy_B"
file_path = f"/content/{file_id}.csv"
!gdown --id $file_id -O $file_path
### Load the dataset
yt_df = pd.read_csv(file_path, encoding='latin-1')
yt_df.head()
</code></pre>
    <h2>Project Structure</h2>
    <p>The project includes the following main components:</p>
    <ul>
        <li><code>YouTube Content Trend Analysis.ipynb</code>: The main Jupyter Notebook containing all the analysis and explanations.</li>
        <li><code>README.md</code>: This file, providing an overview and usage instructions.</li>
    </ul>
    <h2>Getting Started</h2>
    <p>To use this project, follow these steps:</p>
    <ol>
        <li>Clone the repository to your local machine.</li>
        <li>Ensure you have Jupyter Notebook installed.</li>
        <li>Open the notebook file and execute the cells in order.</li>
    </ol>
    <pre><code>git clone https://github.com/yourusername/youtube-content-trend-analysis.git
cd youtube-content-trend-analysis
jupyter notebook
</code></pre>
    <h2>License</h2>
    <p>This project is licensed under the MIT License. Feel free to use and modify the code as needed.</p>
</body>
</html>
