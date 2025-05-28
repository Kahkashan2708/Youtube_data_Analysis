# Youtube Comments Analysis

This project performs exploratory data analysis (EDA) on a dataset of YouTube video comments from the US. It focuses on cleaning, visualizing, and deriving insights from the comment data.

##  Dataset

- **File Used**: `UScomments.csv`
- The dataset contains comments on various YouTube videos from the US, including metadata such as likes, replies, and sentiment indicators.
- ## 🔗 Dataset Access

You can access the `UScomments.csv` dataset used in this project from the following Google Drive link:

 [Download from Google Drive](https://drive.google.com/drive/u/0/folders/1makDwgfKzmqOSikEnOLkmMskT3609dAo)

> Make sure to download the CSV file and place it in the same directory as the notebook before running it.


##  Tools & Libraries

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

##  Features

- Handles missing values and cleans the dataset.
- Visualizes distributions and patterns in user comments.
- Identifies popular comments using likes and reply metrics.
- Highlights trends and potential anomalies in the comment data.

##  Data Cleaning

- Dropped rows with missing values in `comment_text`.
- Skipped malformed lines during CSV import using `on_bad_lines='skip'`.

##  Visualizations

- Frequency of comments.
- Most liked comments.
- Reply count distributions.
- Potential sentiment indicators.

##  How to Run

1. Clone the repository or download the notebook.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Place `UScomments.csv` in the same directory as the notebook.
4. Open and run `Youtube Analysis.ipynb` using Jupyter Notebook or any compatible environment.

##  Sample Output

- Bar plots, histograms, and heatmaps illustrating comment activity and engagement.
- Text insights from comments with high likes or replies.
