# IMDb Top 100 Movies Analysis (2010-2019)

## Introduction  
This project explores the **Top 100 IMDb-rated movies** from the past decade (2010–2019) to uncover trends, audience preferences, and factors influencing movie success. Using **Python** and **Exploratory Data Analysis (EDA)**, the study analyzes attributes like genre, budget, profit, actor popularity, and demographic voting patterns to provide actionable insights for filmmakers and stakeholders.

---

## Objective  
The primary goals of this analysis are:  
1. Identify factors contributing to high IMDb ratings and commercial success.  
2. Analyze the relationship between movie attributes (genre, budget, runtime) and ratings.  
3. Investigate the impact of actors' popularity on movie performance.  
4. Understand demographic preferences (age, gender, region) for genres.  
5. Provide data-driven recommendations for content creation and marketing strategies.  

---

## Steps Conducted  
1. **Data Loading & Inspection**:  
   - Imported and inspected the dataset for missing values, data types, and summary statistics.  
2. **Data Cleaning**:  
   - Handled `NaN` values and converted units (e.g., budget to millions).  
3. **Profit Analysis**:  
   - Calculated profit (`Gross - Budget`) and identified top 10 profitable movies and loss-making films.  
4. **Actor Popularity**:  
   - Ranked actor trios by total Facebook likes and applied popularity constraints.  
5. **Genre & Demographic Analysis**:  
   - Aggregated genres and analyzed voting patterns across age, gender, and regions.  
6. **Visualizations**:  
   - Created heatmaps, box plots, bar charts, and scatter plots to highlight trends.  
7. **US vs. Non-US Movies**:  
   - Compared vote counts and ratings between US and international films.  

---

## Results  
1. **Profit Trends**:  
   - High budgets don’t guarantee profits (*e.g., Tangled*: -$60M loss).  
   - Top profit-makers: *Star Wars: Episode VII* ($691M), *The Avengers* ($403M).  
2. **Genre Preferences**:  
   - **Sci-Fi** and **Action** dominated among males (18–29 age group).  
   - **Drama** was the most frequent genre (65 movies) but ranked lower in audience engagement.  
3. **Actor Impact**:  
   - Top trio: **Ginnifer Goodwin, Jason Bateman, Idris Elba** (74,818 likes).  
4. **Demographics**:  
   - Under-18 voters actively engaged with R-rated movies (*e.g., Deadpool*).  
   - US films received 2x more votes than non-US films but had similar ratings.  
5. **Runtime**: 70% of movies were 120–130 minutes long.  

---

## Conclusion  
This project highlights actionable strategies for filmmakers:  
- Prioritize **Sci-Fi/Action** genres for broad audience appeal.  
- Balance budgets with content quality to avoid losses.  
- Leverage popular actor trios with balanced social media influence.  
- Target under-18 audiences strategically, even for restricted genres.  

The analysis demonstrates how data-driven insights can optimize movie production, marketing, and audience targeting in the film industry.

---

**Tools Used:**  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

**Author:** [Jay Thakur]
