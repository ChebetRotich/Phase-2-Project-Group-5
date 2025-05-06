# **From Scripts to Screens: Analyzing Revenue, Genre Evolution, and Industry Trends in Movie Production**

### Project Overview

This project analyzes historical box office data to provide insights into film production trends, genre popularity, budget allocations, and seasonal revenue influences. These insights are designed to assist a new movie studio in making informed decisions about the types of films to produce for optimal profitability and audience engagement.

### Business Problem

With the rise of original video content by major industry players, the company wants to establish a new movie studio. However, it lacks foundational insights into creating successful movies. The objective is to analyze current trends and revenue drivers in the box office to identify the most profitable film types, budget allocations, and optimal release timings for maximizing box office success.

### Data Sources

The project utilizes datasets from various reputable movie industry sources, including:
- **The Numbers**: For box office and budget data.
- **Rotten Tomatoes**: For movie information and reviews.

### Project Objective

To identify the types of films currently performing best at the box office and translate findings into actionable insights. The key goals include:
1. Understanding the relationship between production budgets and profitability in both Domestic and Worldwide Earnings.
2. Identifying the most profitable genres and key trends in box office performance.
3. Analyzing director influence and determining which directors consistently contribute to higher box office success.
4. Assessing the correlation between critic/audience ratings and box office performance.
5. Evaluating seasonal and annual market trends that influence box office success.

### Methods and Analysis

The analysis follows a structured approach using Python and libraries like Pandas, Matplotlib, and Seaborn:

1. **Data Cleaning**:
   - Standardized column values to a favorable format for analysis.
   - Converted date columns to `datetime` format.
   - Addressed rows with missing or erroneous values in key columns.
   
2. **Data Exploration**:
   - Analyzed revenue trends across genres, seasons, and budget categories based on the objectives.
   - Calculated profitability based on production budget vs. domestic and worldwide gross.

3. **Visualizations**:
   - Created bar charts for revenue by genre and best-performing directors.
   - Used scatter plots to show budget vs. gross revenue correlations, and critic ratings vs. production budgets.
   - Developed area plots for overall box office trends over the years.

4. **Hypothesis Testing**:
   - Conducted correlation analysis to determine relationships between critic ratings and both domestic and worldwide gross.
   
5. **Modeling**:
   - Built models to identify factors predicting profitability, focusing on features like domestic gross, runtime, and release year.
   - Included Production Budget and Worldwide Gross to improve model accuracy.

### Recommendations

1. Focus on Low and Medium Budget films, with selective high-budget ventures to optimize profitability. Increasing the frequency of low and medium films can help match the revenue of high and very high-budget categories.
2. To manage risk and maximize returns, prioritize high-margin genres like Musical, Romance, and Comedy, while also investing in low-budget, high-margin genres like Horror.
3. Collaborate with high-grossing directors with proven revenue-generating portfolios, using film count and gross revenue metrics for benchmarking.
4. Prioritize understanding audience preferences over critic ratings, and consider budget distribution across ratings for effective budget allocation.
5. Align release schedules with seasonal genre trends, focusing on high-quality dramatic and comedic films to boost engagement and refine marketing strategies.

### Key Insights

1. **Genre Dominance**: Drama and Comedy consistently rank high, while Horror yields high returns, especially in the low-budget category.
2. **Revenue Trends**: Box office revenue has generally trended upward from the 1980s to 2010s, with streaming causing some market shifts.
3. **Impact of Budget**: High-budget films generate more revenue but with smaller margins, whereas low-budget films, particularly in genres like Horror and Comedy, offer high profitability.
4. **Seasonal Popularity**: Aligning releases with seasonal preferences can optimize revenue based on audience engagement.

### Conclusion

The new movie studio should adopt a strategy that emphasizes low and medium-budget films, particularly in high-margin genres like Musical, Romance, and Comedy, with selective investment in high-budget projects. By focusing on audience preferences, aligning release schedules with seasonal trends, and collaborating with high-grossing directors, the studio can maximize box office success and allocate budgets effectively. This approach will help the studio navigate the competitive landscape of original video content successfully.

### Contact

For questions or collaboration, please reach out to any of the team members:

- Larry Ng'etich - kipkirui.ngetich@gmail.com
- Caren Kyalo - caren.kkyalo@gmail.com
- Derrick Waititu - derricknturibi1317@gmail.com
- Tracy Rotich - Tracyrotich.c@gmail.com
- Doreen Chepkonga - Doreenchepkonga@student.moringaschool.com
- Knight Mbithe - knightmbithe17@gmail.com
