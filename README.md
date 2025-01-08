# Netflix Data Analysis Project  

### **Introduction**  
Netflix is one of the most popular streaming platforms, offering a wide array of movies and TV shows globally. Since its inception in 1997, Netflix has grown exponentially, delivering quality content that captivates millions of viewers. This project delves into an exploratory data analysis of Netflix's vast content library, providing insights and visualizations about its movies and TV shows.

**View the Project Here**: https://github.com/AkshayS80/Netflix_Data_Visualisation/blob/main/netflix-data-visualisation.ipynb

### **Project Features**  

1. **Dataset Overview**  
   - The dataset consists of 8807 records and 12 attributes.  
   - Attributes include information about movies, TV shows, their ratings, release years, and more.  

2. **Pre-Requisites**  
   - Import essential Python libraries such as Pandas, Matplotlib, Seaborn, and Plotly.  
   - Load and inspect the dataset to understand its structure and dimensions.  

3. **Statistical Insights**  
   - Generate descriptive statistics to understand data distribution.  
   - Analyze null values, mean, standard deviation, and other dataset characteristics.  

4. **Data Cleaning**  
   - **Duplicates:** Verified and removed duplicate entries (none found in the dataset).  
   - **Missing Values:** Removed rows with missing values, reducing the dataset to 5332 records.  
   - **Irrelevant Columns:** Dropped columns such as "show_id" and "cast" for being non-contributory to visualizations.  
   - **Data Normalization:** Split multi-value fields like "country" and "listed_in" into separate rows for better analysis.  

5. **Data Visualizations**  
   A set of intuitive visualizations was created to draw insights, including:  

   - **Histograms:**  
     - Distribution of ratings for movies and TV shows.  
     - Count of movies released over the years.  
   - **Bar Charts:**  
     - Top 10 most-streamed genres on Netflix.  
   - **Pie Charts:**  
     - Ratio of TV Shows to Movies.  
     - Distribution of TV Shows based on the number of seasons.  
   - **Scatter Plots:**  
     - Relationship between release year and ratings.  

### **How to Run the Project**  

1. Clone this repository to your local machine.  
2. Install necessary libraries using:  
   ```bash  
   pip install pandas matplotlib seaborn plotly  
   ```  
3. Run the Jupyter Notebook to view and execute code step-by-step.  

### **Key Visualizations**  

1. **Types of Movies and TV Shows Based on Rating**  
   - Provides a histogram displaying the distribution of ratings for movies and TV shows.  

2. **Number of Movies Released Over the Years**  
   - Showcases a histogram of movie release trends over time.  

3. **Top 10 Genres Streamed on Netflix**  
   - A bar chart highlighting the most popular genres among Netflix's audience.  

4. **Ratio of TV Shows to Movies**  
   - Visualized using a pie chart with precise percentage labels.  

5. **Relationship Between Release Year and Rating**  
   - Scatter plot exploring potential trends between release years and ratings.  

### **Insights and Findings**  

- The highest number of movies released on Netflix peaked in certain years.  
- Genres like Drama, Comedy, and Action dominate Netflix's content library.  
- Movies slightly outnumber TV shows in Netflix's catalog.  
- Ratings distribution is diverse, reflecting varying audience preferences.  

### **Conclusion**  
This project provides a comprehensive exploratory data analysis of Netflix content, delivering insights into trends, popular genres, and audience preferences. It highlights the power of data visualization in uncovering patterns and enhancing decision-making.
