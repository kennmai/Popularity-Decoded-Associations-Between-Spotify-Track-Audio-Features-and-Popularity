## The Danceability Effect: Associating Spotify Track Popularity Through Statistical Analysis in R
*Contributors include Maia Kennedy, Ryan Farhat-Sabet, and William Seward from the University of California, Berkeley*

<img width="544" alt="Spotify" src="https://github.com/user-attachments/assets/21811db6-6005-49fe-a208-47a59d9de1e6" />

**Project Overview:**
This study explores the statistical relationship between Spotify’s danceability metric and track popularity, utilizing a dataset of over 30,000 songs. By applying regression analysis and multivariate models in R, this project investigates how various Spotify audio features, including energy and instrumentalness, relate to track popularity. The analysis seeks to quantify the extent to which danceability correlates with popularity, addressing the nuances of music's appeal. 

**Methodology and Approach:**
Using R, we conducted a series of statistical analyses to evaluate the relationship between audio features and track popularity. A baseline linear regression model was employed to explore the danceability-popularity association, with additional multivariate regression models applied to account for confounding factors. Key steps include:

* Data Cleaning & Preprocessing: Addressed data quality issues such as duplicates and songs with zero popularity. This involved advanced data wrangling techniques in dplyr and tidyr.
* Exploratory Data Analysis (EDA): Used ggplot2 to visualize correlations and distributions of audio features and popularity metrics.
* Model Development: Developed baseline regression models and extended the analysis with multivariate regression to control for additional variables like energy, instrumentalness, and valence.
* Statistical Testing: Employed hypothesis testing and p-values to evaluate the statistical significance of the relationships, confirming a modest but significant correlation.
* Assumption Checking: Validated model assumptions using residual analysis, normality tests, and multicollinearity diagnostics (e.g., VIF).

**Results and Insights:**
* **Significant, but Modest Correlation:** The initial regression analysis reveals that danceability explains a small fraction of the variance in popularity, suggesting that while it is a contributing factor, it is not a dominant predictor.
* **Complexity of Popularity:** The analysis underscores the multifaceted nature of musical popularity, with many factors influencing a song's success beyond individual audio features.
* **Implications for Stakeholders:** The study offers actionable insights for artists, record labels, and marketers looking to optimize music production by understanding how specific audio features (like danceability) might influence listener engagement and popularity.

**Challenges and Future Work:**
* **Data Challenges:** Addressing songs with zero popularity and cleaning duplicate entries presented initial hurdles.
* **Model Limitations:** The modest predictive power of danceability highlights the need for further exploration of additional features and advanced statistical techniques (e.g., regularization or principal component analysis).
* **Further Exploration:** Future iterations of this analysis could include time-series models to explore how popularity trends evolve or machine learning techniques to build more predictive models for track success.
