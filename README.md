# Exoplanet-radius Prediction
Using NASA's data on exoplanets in an attempt to predict the radius of each planet based only on features of their stars.

The decision to predict the radius of the planets was somewhat aribtrary. After looking at the data, the planet radius was one of the few features that contained a majority of non-null entries.

This is my first data/ml type of project that I have done. I mainly used this project to test different types of model building and data filtering. 

### Results
The results are not great, currently the model's accuracy is coming in at approximately 60%. This is terrible for any real world use. However, considering the type of data this is and my starting point, 60% is not too bad for me. When I initially started working with the data, I was getting results at about 6%. I plan to further improve upon this project in the future to test my knowledge and progress.

### Some Takeways
* When working in a domain that is beyond my knowledge, choosing features is best done using wrapper or embedded methods.
* Always check how many NaN or null entries are in each column, otherwise you'll waste time trying to predict something that only has 300/4000 valid entries.
* Visualizations are key to understanding.
* Ensemble methods appear to work well with this type of data.
* Use cross validation to tune hyperparameters INSTEAD of using the test set.
