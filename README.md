# Shopping Analysis

## Table of Contents
+ [Project Overview](#Project-overview)
+ [Technologies Used](#Technologies-Used)
+ [Usage](#Usage)
+ [Project Problem](#Project-Problem)
+ [Project Walkthrough](#Project-Walkthrough)
+ [Project Insights](#Project-Insights)
+ [Screenshots](#Screenshots)
+ [Source](#Source)


## Project Overview
In this project, we explore and analyze a dataset containing simulated shopping behaviors. The project is implemented in Python and involves data formatting, exploratory analysis using visualizations, and deriving insights from the data. The objective is to gain a deep understanding of how different factors influence shopping patterns.


## Technologies Used
+ Python - The programming language used for data analysis.
+ libraries installed
   + NumPy - For numerical operations and array manipulation.
   + Calendar - For handling date-related operations.
   + Pandas - For data manipulation and analysis.
   + Seaborn - For creating informative and attractive visualizations.
   + Matplotlib.pyplot - For additional visualization capabilities.


## Usage
To run the file locally, follow these steps:

1. Clone the repository.
2. Navigate to the shopping/ directory
3. Install the required Python packages using the following command:
   
   ```python
   pip install numpy pandas seaborn matplotlib
5. Launch Jupyter Notebook and open the shopping_analysis.ipynb notebook to perform data formatting and then proceed to the exploratory analysis.

## Project Problem
The project addresses several key questions related to shopping behaviors and demographics:
- Among males and females, who spends the most?
- What are the most commonly purchased product categories by females and males?
- What is the average amount of money spent in each product category?
- Are higher quantities associated with lower prices, or is there a different pattern observed?
- Are there any notable patterns or trends in shopping behavior across different gender and age groups?
- What are the preferred shopping locations?
- What are the top-selling product categories in different shopping locations?
- What payment method is most commonly used by customers?
- On which day of the week are the highest sales observed?
- On which month of the year are the highest sales observed?


## Project Walkthrough
1. Import the necessary libraries
2. Load the dataset and take a quick look at the first few rows
3. Check the dimensions and structure of the dataset
4. Handle any duplicate in the dataset
5. Create new columns based on the information of the dataset
6. Convert a column from object to datetime datatype
7. Extracting Date Components into new columns
8. After check the time span covered by the dataset it was decided to focus on a subset of the data
9. Use visualizations to explore the data and answer questions
10. Summarize all the findings


## Project Insights
Based on our analysis, we have uncovered several key insights into shopping behavior:
- Females, particularly adult women, dominate spending.
- Popular purchase categories include clothing, cosmetics, and food & beverages.
- In contrast, technology products generate the highest sales revenue, followed by shoes and clothing.
- Top shopping destinations include Mall of Istanbul, Kanyon, and Metrocity.
- Cash payments are the preferred payment method.
- Mondays witness the highest sales, and January stands out as the peak sales month.


## Screenshots
<div style="display: flex; flex-direction: row;">
  <img  style="margin-bottom: 10px;" src="https://github.com/NilArj/Shopping-Behaviors-Analysis/blob/a9c2ee2ff77060763f3a68e866195f2fef130ecf/images/Captura%20de%20pantalla%202023-08-23%20112959.png" alt="project index" width="600" height="280">

</div>


## Source
Dataset: [Retail Sales Data from Kaggel](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset)


