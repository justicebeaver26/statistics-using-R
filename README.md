# statistics-using-R
The aim of this project is to apply computational mathematics and statistical methods using R.


# Body Fat Prediction Analysis  

## Project Overview  
This project was completed as part of **STAT805: Computational Mathematics and Statistics**. The purpose of the assignment is to apply statistical techniques and computational methods using R to a real-world dataset. The analysis includes estimation of distribution parameters, linear regression modelling, and principal component analysis (PCA).  

The chosen dataset is **BodyFat**, which contains physical measurements and body fat percentage. The main aim is to build predictive models that provide accurate, non-invasive estimates of body fat percentage.  

---

## Dataset  

### Background  
The dataset provides a foundation for studying the relationship between body fat percentage and various body measurements. Traditional body composition assessments, such as hydrostatic weighing, are often expensive and invasive. This dataset allows for the exploration of regression-based models that use simple physical measurements to predict body fat percentage.  

The data was originally collected by **K.W. Penrose and colleagues at Brigham Young University**, with the goal of developing a generalised prediction equation for body composition. Data was collected from 252 men, with the first 143 cases used for model development and the rest for validation.  

### Source  
The dataset is publicly available on Kaggle:  
[Body Fat Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/body-fat-prediction-dataset)  

### Variables  
- **Density**: Body density measured via hydrostatic weighing.  
- **BodyFat**: Estimated body fat percentage (response variable).  
- **Age**: Age in years.  
- **Weight**: Weight in pounds.  
- **Height**: Height in inches.  
- **Neck**: Neck circumference (cm).  
- **Chest**: Chest circumference (cm).  
- **Abdomen**: Abdomen circumference (cm).  
- **Hip**: Hip circumference (cm).  
- **Thigh**: Thigh circumference (cm).  
- **Knee**: Knee circumference (cm).  
- **Ankle**: Ankle circumference (cm).  
- **Biceps**: Biceps circumference (cm).  
- **Forearm**: Forearm circumference (cm).  
- **Wrist**: Wrist circumference (cm).  

---

## Methods and Analysis  

### Section 1: Estimation   
- Visualized the distribution of a selected variable.  
- Identified two suitable parametric distributions.  
- Estimated parameters using:  
  - Method of Moments.  
  - Maximum Likelihood Estimation (MLE).  

### Section 2: Linear Regression   
- Selected **BodyFat** as the response variable.  
- Used at least four explanatory variables (e.g., Density, Knee, Height, Wrist).  
- Built and interpreted a linear regression model.  
- Evaluated model fit using residual plots, R², and diagnostic tests.  

### Section 3: Principal Component Analysis (PCA)  
- Performed PCA on a subset of variables.  
- Justified variable standardization.  
- Determined the number of components retained.  
- Interpreted the first two principal components in terms of physical characteristics.  

---

## Results  
- **Estimation**: The chosen variable fitted reasonably well under two different distributions, with parameter estimates obtained via both moments and MLE.  
- **Regression**: The linear regression model demonstrated that **density** was the most significant predictor of body fat percentage.  
- **PCA**: The first two principal components explained a large proportion of variance, highlighting body size and limb measurements as key underlying factors.  

---

## Conclusion  
This project demonstrated the application of computational statistics methods in R, including parameter estimation, regression modeling, and PCA. The analysis confirmed that simple, non-invasive body measurements can provide reliable predictions of body fat percentage.  

---

## Requirements  
- R and RStudio  
- Libraries: `ggplot2`, `dplyr`, `MASS`, `stats`, `FactoMineR`, `factoextra`


 
