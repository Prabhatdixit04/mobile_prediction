# Dataset:-
Battery_power - Total energy a battery can store in one time measured in mAh
Blue - Has bluetooth or not
Clock_speed - speed at which microprocessor executes instructions
Dual_sim - Has dual sim support or not
Fc - Front Camera mega pixels
Four_g - Has 4G or not
Int_memory - Internal Memory in Gigabytes
M_dep - Mobile Depth in cm
Mobile_wt - Weight of mobile phone
N_cores - Number of cores of processor
Pc - Primary Camera mega pixels
Px_height - Pixel Resolution Height
Px_width - Pixel Resolution Width
Ram - Random Access Memory in Mega Bytes
Sc_h - Screen Height of mobile in cm
Sc_w - Screen Width of mobile in cm
Talk_time - longest time that a single battery charge will last when you are
Three_g - Has 3G or not
Touch_screen - Has touch screen or not
Wifi - Has wifi or not
Price_range - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost)

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
