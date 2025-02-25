DUOLINGO HEATMAP INSIGHTS

This project analyzes Duolingo learning patterns using a heatmap visualization. The goal is to explore user engagement trends based on the time of day and day of the week.

DATASET SOURCE 

The dataset used for this project comes from Duolingo’s spaced repetition dataset. It contains 13 million learning traces, tracking users’ interactions, correct/incorrect answers, timestamps, and other details.

PROJECT PROCESS
1. Data Preprocessing (Google Colab)
This project was developed in Google Colab, making it easy to work with large datasets and visualize results.
* Loaded the dataset into a Pandas DataFrame.
* Converted timestamps to datetime format.
* Extracted key time-based features such as hour and day_of_week.
* Checked for missing values and duplicates and handled them accordingly.
* Filtered and structured the dataset for visualization.
  
2. Heatmap Visualization
* Used Seaborn and Plotly to create an interactive heatmap.
* The heatmap shows correct answers distributed by hour of the day and day of the week.
* Explored different color schemes and centered the plot title for better presentation.
  
3. Exporting & Uploading to GitHub
* Downloaded the cleaned dataset from Colab.
* Saved and uploaded the notebook & dataset to GitHub for sharing and collaboration.


HOW TO RUN THIS PROJECT

Since this was developed in Google Colab, you can either:
1. Run it directly on Google Colab by uploading the notebook and dataset.
2. Run it locally by following these steps:
   - Clone the repository
   - Install dependencies (pip install pandas matplotlib seaborn plotly)
   - Open and run the Jupyter Notebook or Google Colab

ACCESSING THE DATASET

You can access the dataset I used to visualize this data via this link: https://www.kaggle.com/datasets/charitygithogora/cleaned-duolingo-learning-data


RESULTS AND INSIGHTS

The final heatmap provides a clear pattern of user activity on Duolingo:
- Identifies peak learning hours.
- Shows the most active days of the week.
- Helps understand when users are most engaged in learning.


CONTRIBUTING

Feel free to fork this repository and suggest improvements

