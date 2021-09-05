# Dataset:-
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

### Model prediction with test dataset:
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
