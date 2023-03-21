# California Housing Prediction

## Tools used:
* Pandas
* Numpy
* Seaborn
* Matplotlib
* Scikit-Learn


This classic project explores the end-to-end process of a machine learning process using the Hands-On Machine Learning book by Aurélien Geron. We perform data analysis, feature engineering, create data pipelines and fit different models to select the best ones. From there we, use ensemble methods and perform evaluations improve accuracy. 

The dataset contains housing and demographic information on California districts. The features are a mixture of categorical and numeric values. 


<img width="462" alt="image" src="https://user-images.githubusercontent.com/40530704/226675118-9eeee663-c16c-46f8-852f-135ca400750a.png">


The columns are: 
* longitude
* latitude
* housing_median_age
* total_rooms
* total_bedrooms
* population
* households
* median_income
* median_house_value
* ocean_proximity

<img width="769" alt="image" src="https://user-images.githubusercontent.com/40530704/226673474-71bc2e08-482d-4048-90cd-d564c94c6030.png">


<img width="314" alt="image" src="https://user-images.githubusercontent.com/40530704/226676313-2fc21f03-0784-4288-abdd-82b99a6c51bb.png">


We experiment with Linear Regression, Random Forest, Support Vector Regression(kernel='linear'), and Linear Stochastic Gradient Descent. We fine tune the model using GridSearch and Randomized Search, to find the best combination of features and achieve a 95% accuracy using ensemble methods.
