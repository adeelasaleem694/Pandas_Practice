

# PandasPractice  

This repository contains a collection of exercises and examples demonstrating the practical use of **pandas** for data analysis. The dataset used involves exploring Udemy course data to answer interesting questions and perform insightful analyses.  

## Features  

### Key Pandas Methods Demonstrated:  
1. **`parse_dates`**:  
   The `parse_dates` parameter in `read_csv` is used to specify columns to be treated as dates or datetimes during data import.  

2. **`value_counts()`**:  
   Returns a Series containing the counts of unique values in a column.  

3. **`countplot()`**:  
   Used to show the counts of observations in each categorical bin using bars.  

4. **`barplot()`**:  
   Displays relationships between categorical data and numerical variables.  

---

### Questions Answered Using Pandas  

1. **Display Top 10 Rows of The Dataset**: Get a quick view of the first 10 entries to understand the data.  
2. **Check Last 5 Rows of The Dataset**: Inspect the last few rows to identify tail-end patterns.  
3. **Find Shape of Our Dataset**: Determine the number of rows and columns.  
4. **Get Dataset Information**: Understand the structure of the dataset, including row and column counts, data types, and memory usage.  
5. **Check Null Values**: Identify any missing data.  
6. **Check For Duplicate Data and Drop Them**: Ensure data integrity by handling duplicates.  
7. **Find Number of Courses Per Subject**: Analyze the distribution of courses across different subjects.  
8. **Identify Course Levels**: Explore the course levels offered (e.g., beginner, intermediate, advanced).  
9. **Count Paid vs. Free Courses**: Compare the number of paid and free courses.  
10. **Which Course Has More Lectures (Free or Paid)?**: Determine the relationship between course type and the number of lectures.  
11. **Which Courses Have Higher Subscriber Counts (Free or Paid)?**: Analyze which course type attracts more subscribers.  
12. **Which Level Has The Highest Number of Subscribers?**: Find the most popular course level.  
13. **Find The Most Popular Course Title**: Identify the course title with the highest number of subscribers.  
14. **Display 10 Most Popular Courses**: Rank courses by the number of subscribers.  
15. **Find The Course With The Highest Number of Reviews**: Highlight the most reviewed course.  
16. **Does Price Affect The Number of Reviews?**: Analyze the relationship between course price and reviews.  
17. **Count Total Python-Related Courses**: Filter and count Python-related courses.  
18. **Top 10 Python Courses By Subscribers**: List the most popular Python courses.  
19. **Year With Highest Number of Course Posts**: Analyze trends in course posting over the years.  
20. **Category-Wise Subject Counts By Year**: Track the yearly distribution of subjects across categories.  

---

## Tools and Libraries Used  

- **Python**  
- **Pandas**  
- **Seaborn**  
- **Matplotlib**  

---

## How to Use  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/adeelasaleem694/PandasPractice.git  
   ```  

2. Install the required libraries:  
   ```bash  
   pip install pandas matplotlib seaborn  
   ```  

3. Download the dataset from Kaggle:  
   [Udemy Courses Dataset](https://www.kaggle.com/datasets/andrewmvd/udemy-courses)  

4. Place the dataset in the project directory.  

5. Run the Jupyter Notebook or Python script to explore the dataset and answers to the questions.  

