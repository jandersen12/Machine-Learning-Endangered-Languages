# Languages at Risk: A Machine Learning Approach to Predicting Endangered Languages

### Project Overview

This project leverages machine learning to predict the endangerment level of languages worldwide using demographic, technological, and legal status indicators. Drawing on five integrated datasets, it explores the relationship between factors such as speaker count, urbanization, internet use, and legal recognition, and their influence on language vitality. Multiple models, including ensemble methods, gradient boosting, and neural networks, were trained and evaluated, achieving high predictive performance. The results highlight the critical role of speaker population size while underscoring opportunities for improvement through the inclusion of additional socio-economic and historical features.

### Tools

Python | SKLearn | TensorFlow

### Process

**Data Cleaning**

1. Five datasets were merged, including language endangerment status, official languages by country, speaker counts, urbanization rates, and internet use rates. 
2. The target variable was endangerment level (categorical), and features included language, speaker count, urbanization rate, internet use rate, one-hot encoded legal status categories (official, national, regional, minority, widely spoken), and the number of countries where the language is spoken. 
3. Data preparation involved regex formatting, log-transforming speaker counts, and creating interaction features combining urbanization with speaker count and internet use with speaker count.

**Models**

A baseline model predicting the most common class was first established. More complex models including ensemble methods, gradient boosting, extra trees, and neural networks were trained and tuned to identify the best performing approach. Detailed experiment configurations and results are documented in the final report.

### Results

All advanced models achieved high predictive accuracy around 88%, with the number of speakers emerging as the most influential feature across approaches. Gradient Boosting and Ensemble models performed similarly and were the top performers. While results were strong, the models may not fully capture historical language trends. Expanding the feature set to include more socio-economic, geographic, or historical indicators could help surpass the 88% threshold for test accuracy.


### Key Learnings

The project strengthened my skills in feature engineering, model selection, and systematic hyperparameter tuning using Scikit-learn and TensorFlow. It reinforced best practices in feature transformation, as well as techniques for interpreting model outputs to identify key predictive drivers using precision, recall, and accuracy scores.


### Contributors 
Helin Yilmaz | Courtney Chen | Brian Woods

UC Berkeley MIDS | July 2025