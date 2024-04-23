This project implements a movie recommendation system using Python's pandas library and collaborative filtering techniques. It also incorporates exploratory data analysis (EDA) to understand user ratings and movie trends.

Key Features:

Data Preprocessing:
Loads movie rating data from a CSV file.
Merges the data with movie titles for better readability.
Exploratory Data Analysis (EDA):
Analyzes average ratings per movie and the distribution of ratings and number of ratings.
Visualizes the relationships between these variables using histograms and jointplots.
Collaborative Filtering:
Creates a movie-user rating matrix.
Calculates movie-to-movie correlations based on user ratings.
Generates recommendations for each movie based on highly correlated movies (with at least 100 ratings).
Recommendation Output:
Stores recommendations with corresponding ratings data in a separate CSV file for reusability.
Interactive Recommendation Retrieval:
Provides a user interface using Jupyter Notebook widgets where users can input a movie title.
Retrieves and displays recommendations for that movie based on the stored data.
Requirements:

Python 3.x
pandas
matplotlib.pyplot (optional for EDA visualizations)
seaborn (optional for EDA visualizations)
Jupyter Notebook (for interactive recommendation retrieval, optional)
Installation:

Ensure you have Python 3 and the required libraries installed. You can install them using pip install pandas matplotlib seaborn.
Clone or download this repository.
Running the Script:

Open the Jupyter Notebook file (if using Jupyter Notebook for interactive recommendations).
Execute the code cells sequentially.
Cells 1-13 perform data loading, preprocessing, EDA, and recommendation generation.
Cells 14-21 provide the interactive recommendation retrieval interface (optional).
Using the Interactive Recommendations (Optional):

Select or copy a movie title from the list generated early in the code's execution.
Paste the title into the text box below the code cell marked "### How to get Recommendations?".
Click the "Submit" button or press Enter in the text box.
The code will display your recommended movies for the chosen title.
