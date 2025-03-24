# ShadowFox

__TASK - 1 AUTOCORRECT SYSTEM__
<br> <br>
The Autocorrect Keyboard System is a simple Python-based tool that automatically corrects misspelled words in user input. It utilizes the pyspellchecker library to identify and suggest corrections for misspelled words, improving the overall typing experience.

To use this project, install the necessary dependency in Google Colab:

> pip install pyspellchecker

Run the Python script and enter text. If any word is misspelled, the system will suggest a correction.

Code Workflow:
1. User Input: The program waits for user input via the command line.
2. Word Splitting: The text is split into individual words.
3. Spell Checking: Each word is checked against the spellchecker dictionary.
4. Correction Suggestion: If a word is misspelled, the most probable correction is suggested.
5. Reconstruction: The corrected words are joined back into a complete sentence.
6. Output Display: The corrected text is displayed to the user.
7. Exit Option: The user can exit by typing "exit".

Libraries Used:
<br>
pyspellchecker --> used for spell checking and corrections
<br>
<br>
<br>
__TASK - 2 STORE SALES AND PROFIT ANALYSIS__
<br> <br>
This Python script is designed to analyze sales and profit performance from a retail dataset. It provides valuable insights into sales trends, profitability, top-performing product categories, and customer segment contributions. The goal is to assist businesses in making data-driven decisions to optimize inventory, pricing strategies, and marketing efforts.

Features:
1. Monthly Sales Trends: Tracks sales trends over time.
2. Top Performing Categories & Sub-Categories: Identifies which product categories and sub-categories generate the most sales.
3. Monthly Profit Trends: Analyzes profitability trends on a monthly basis.
4. Most Profitable Categories & Sub-Categories: Highlights the most profitable product categories and sub-categories.
5. Profitability by Customer Segment: Evaluates which customer segments contribute the most to profits.
6. Sales-to-Profit Ratio by Category: Assesses efficiency and profitability across different product categories.
7. Customer Segment Performance: Analyzes total sales and profit contributions from each customer segment.

Ensure you have the following libraries installed:

> pip install pandas plotly.express

How to Use:
1. Upload the Dataset:
The script uses Google Colab’s file upload feature.
Upload the CSV dataset(provided the dataset "Superstore.csv") containing sales data.

2. Run the Script:
The script dynamically extracts the uploaded filename and loads the dataset.
Converts the 'Order Date' column to datetime format.
Handles missing values by forward-filling data.

3. Analyze Sales and Profit:
Generates monthly sales and profit trends.
Identifies top-performing and most profitable product categories.
Evaluates customer segment profitability.

4. Visualize Data:
Uses Plotly to generate interactive line plots for sales and profit trends.
Monthly sales and profit trends are plotted using Plotly’s interactive line charts.

Libraries Used:
<br>
pandas –-> For data manipulation and analysis.

plotly.express –-> For creating interactive visualizations.

google.colab(pre-installed in Google Colab) –-> For handling file uploads in Google Colab (used for uploading files).
