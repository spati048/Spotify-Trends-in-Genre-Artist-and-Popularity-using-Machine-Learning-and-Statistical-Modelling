# Spotify Trends in Genre Artist and Popularity using Machine Learning and Statistical Modelling

## Project Overview  
This project analyzes how music popularity has evolved over the past century using data-driven methods.  
We identify the key features driving popularity, track how they shift across decades, and evaluate predictive models.  

**Brief Description:**  
Exploring evolution of music popularity using regression, Lasso/Ridge, Random Forest, PCA, and time-series analysis.  
Results show danceability, loudness, and energy drive popularity, while valence and speechiness decline, revealing how modern hits are louder, faster, and more emotionally complex than ever before.  

## Models & Methods  

### 1. **Multiple Linear Regression**  
- Baseline statistical model for interpretability  
- Identified key predictors: Danceability, Loudness, Energy (+) and Valence, Speechiness (-)  
- Adjusted R square = 0.31, RMSE = 15.29  

### 2. **Lasso and Ridge Regression**  
- Regularization to handle multicollinearity  
- Cross-validation tuned lambda values  
- Retained core predictors while shrinking less important coefficients  
- Similar RMSE to linear regression, with more stability  

### 3. **Random Forest**  
- Captured non-linear relationships and interactions  
- Best predictive performance (RMSE = 13.87)  
- Feature importance: Loudness, Energy, Acousticness, and Valence ranked highest  

### 4. **Time-Series Analysis**  
- Explored long-term trends from 1921-2020  
- Found steady increases in Loudness and Energy, with Valence declining since 2000s  

### 5. **Principal Component Analysis (PCA)**  
- Reduced dimensionality and visualized feature evolution  
- PC1 and PC2 captured ~69% of variance  
- Showed clear trajectory of modern music becoming more energetic, loud, and rhythm-driven  

## Key Insights  
- Popularity is most positively associated with **danceability, loudness, and energy**.  
- **Valence** (happy/positive mood) and **speechiness** show negative effects, reflecting nuanced audience preferences.  
- Music has become **louder, faster, and more energetic** over time, while emotional tone has shifted darker.  
- Random Forest offers best predictive accuracy, while regression models provide valuable interpretability.  

## Skills & Tools Used  
- **Statistical Modeling:** Multiple Linear Regression, Lasso, Ridge  
- **Machine Learning:** Random Forest  
- **Exploratory Data Analysis (EDA):** Correlation heatmaps, scatterplots, genre-level comparisons  
- **Dimensionality Reduction:** PCA  
- **Time-Series Analysis:** Feature evolution across decades  
