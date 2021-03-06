## Mobile price range prediction:-
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices.
## Objective<br>
 The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

###  Dataset 📊
| Feature name  |  Feature description                                  |  Type   |
|---------------|-------------------------------------------------------|---------|
| battery_power | Total energy a battery can store in mAh               | Numeric |
| blue          | Has bluetooth or not                                  | Boolean |
| clock_speed   | Speed at which microprocessor executes instructions   | Numeric |
| dual_sim      | Has dual sim support or not                           | Boolean |
| fc            | Front Camera mega pixels                              | Numeric |
| four_g        | Has 4G or not                                         | Boolean |
| int_memory    | Internal Memory in Gigabytes                          | Numeric |
| m_dep         | Mobile Depth in cm                                    | Numeric |
| mobile_wt     | Weight of mobile phone                                | Numeric |
| n_cores       | Number of cores of processor                          | Numeric |
| pc            | Primary Camera mega pixels                            | Numeric |
| px_height     | Pixel Resolution Height                               | Numeric |
| px_width      | Pixel Resolution Width                                | Numeric |
| ram           | Random Access Memory in Megabytes                     | Numeric |
| sc_h          | Screen Height of mobile in cm                         | Numeric |
| sc_w          | Screen Width of mobile in cm                          | Numeric |
| talk_time     | Longest time that battery will last by a call         | Numeric |
| three_g       | Has 3G or not                                         | Boolean |
| touch_screen  | Has touch screen or not                               | Boolean |
| wifi          | Has wifi or not                                       | Numeric |

### Methods Used
* Descriptive Statistics
* Data Visualization
* Machine Learning

### Technologies
* Python
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-learn

### Needs of this project
- data exploration
- data processing/cleaning
- predictive model for multiple classifier

### Project Description
* EDA - Performed exploratory data analysis on numerical and categorical data.
* Data Cleaning - Missing value imputation,Outlier Treatment
* Feature Selection - Used ram, battery_power and pixel dimensions for building the model.
* Model development - Tried classification models like XGboost, Decision Tree, Random Forest and KNN model to predict mobile price range.

### Model prediction with test dataset:-
| Model name                  | Accuracy test | 
|-----------------------------|---------------|
| Linear regression           | 91.75 %       |
| Random forest               | 96.86 %       |
| XgBoost                     | 92.00 %
| KNN classifier              | 94.33 %       | 
| Decision tree               | 82.83 %       | 

### Model prediction with train dataset:
| Model name                  | Accuracy test | 
|-----------------------------|---------------|
| Linear regression           | 91.75 %       |
| Random forest               | 94.85 %       |
| XgBoost                     | 100.0 %
| KNN classifier              | 94.50 %       | 
| Decision tree               | 89.21 %       | 

### Contributing AlmaBetter Team Members


|Name     |  Email Address   | 
|---------|-----------------|
|[Amit Padye]| @amitpadye237@gmail.com        |
|[Akhilesh Kumar]|     @akhilesh254@gmail.com   |
|[Bharadwaj Narayanam]| @nbhj897@gmail.com        |
|[Prabhat Dixit]|     @dixitprabhat.1-@gmail.com    |
|[Subhadip Sen]|     @h20190505p@alumni.bits-pilani.ac.in    |
