# M.Sc.-Industrial-Project
This repository contains my  University project


*Groundwater Quality Assessment of Chhota Udaipur Taluka Using Artificial Neural Networks*

*Project Overview*

This project is part of my MSc in Applied Mathematics (Industrial Mathematics) at The Maharaja Sayajirao University of Baroda. The objective was to assess and predict groundwater quality in Chhota Udaipur taluka, Gujarat, using Artificial Neural Networks (ANN). The project aimed to ensure the safety and sustainability of groundwater resources by classifying the water quality based on various parameters.

*Objectives:*

•Evaluate groundwater quality using data collected from 28 wells over the period 2010-2021.
•Develop an ANN model to predict water quality suitability for drinking purposes.
•Classify groundwater samples into categories such as excellent, good, poor, very poor, and unfit for drinking.

*Data Collection:*

Groundwater samples were analyzed for the following parameters:

pH

Nitrate (NO3-)

Fluoride (F-)

Sulfate (SO4 2-)

Calcium (Ca2+)

Magnesium (Mg2+)

Hardness

Chloride (Cl-)

Total Dissolved Solids (TDS)

Alkalinity

Samples were collected from 28 wells in the villages of Chhota Udaipur taluka over a span of 11 years (2010-2021). The data was sourced from a government website, ensuring its accuracy and reliability.

*Methodology:*

Model Development
Data Preprocessing:

•Normalization of input data to improve model performance.
•Handling missing values and outliers to ensure data quality.

*Model Architecture:*

•Developed an ANN model with two hidden layers.
•The first hidden layer consisted of 10 neurons, and the second layer had 9 neurons.
•Used ReLU (Rectified Linear Unit) as the activation function for hidden layers.

*Training:*

•Optimized the model using Stochastic Gradient Descent (SGD).
•Trained the model over 447 iterations to achieve optimal performance.

*Validation:*

•Split data into training and testing sets to validate the model's accuracy.
•Calculated performance metrics such as Mean Square Error (MSE), Root Mean Square Error (RMSE), and R-squared (R2) score.

*Performance Metrics:*

Mean Square Error (MSE): 0.0244

Root Mean Square Error (RMSE): ~0.1562

R-squared (R2): ~0.9999

*Water Quality Classification:*

Classified the groundwater samples into:
•Excellent

•Good

•Poor

•Very Poor

•Unfit for Drinking

*Water Quality Index (WQI):*

Computed WQI using both traditional methods and ANN to validate the effectiveness of the ANN approach.

*Results:*

•Achieved high accuracy in predicting groundwater quality, evidenced by the low MSE and high R2 score.
•Provided actionable insights into the temporal changes in water quality across various villages in Chhota Udaipur.
•Highlighted critical areas requiring attention for effective water quality management.

*Key Takeaways:*

Innovation: Demonstrated the integration of advanced computational techniques with environmental science, highlighting the potential of ANNs in predictive analytics.

Impact: Findings helped shape strategies for effective groundwater quality management in the region.

Collaboration: Enhanced technical and teamwork skills by working as part of a dedicated group project.

*Skills and Tools Utilized:*

Programming Languages: Python

Libraries: NumPy, Pandas, Matplotlib, Scikit-learn

Technical Skills: Data analysis, machine learning algorithms, model validation

Analytical Skills: Statistical analysis, data preprocessing

*Repository Contents*

••Data: Contains the groundwater quality data collected from 28 wells over 2010-2021 (sourced from a government website).

••Thesis: Includes the comprehensive project report detailing the methodology, analysis, results, and conclusions of the study.
