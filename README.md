# Unsupervised Remaining Useful Life Prediction for Bearings with Virtual Health Index  
__Authors__: Gilbert Cheng, Sean Lau, Nicholas Tam, Ze Kai Wu, Adah Hu, Yan Nei Law, Edmond Lai, Ming Ge  
_Last Updated_ : 07 December 2022  

==========================================  

### Introduction  
This repository complements the paper "Unsupervised Remaining Useful Life 
Prediction for Bearings with Virtual Health Index" submitted to the 2023 
International Conference on Power, Energy and Electrical Engineering (CPEEE). 
The full results on the predicted RUL values of Bearing1_1, Bearing1_2, 
Bearing1_3, Bearing2_2, Bearing2_4, Bearing2_5 are shown.


### File Description
In this repository, you may find the following files :
* __Average EOL Spectrograms vs Actual under Condition I__ - Under Condition I (35 Hz, 12 kN of loading), 
taking the averages of the End-of-Life (EOL) Mel-Spectrograms of Bearings 1_1 and 1_3 yield an average 
Mel-Spectrogram shown on the left of the document. On the right is a comparison to the actual EOL 
Mel-Spectrogram of Bearing 1_2. Note the high degree of similarity between the two. This file complements _Fig. 5_ 
in the submitted paper.
* __Inflection Points for Condition I__ - Under Condition I, the proposed inflection point model 
has proposed the inflection points at the red line, where the bearing is supposed to have 
transitioned from their respective "healthy" state to a "degrading" state. The blue line 
indicates the first signal vibration at each respective sampling period. This file complements _Fig. 4_ 
in the submitted paper.
* __Performance evaluation for candidate bearings in comparison to other state-of-the-art approaches__ - This 
table displays the metric Cumulative Relative Accuracy (CRA) evaluated for this work, compared 
against state-of-the-art approaches, such as Relevance Vector Machine (RVM), Deep Belief Network (DBN), 
Particle Filtering (PF), and Extended Kalman Filtering (EKF). This table shows the complete results for 
both working conditions. The best performing is shown in __bold__. This file complements _Table V_ 
in the submitted paper.
* __Performance evaluation for candidate bearings__ - This file contains a table that compares the CRA metric 
attained by this work to the Hybrid Prognostics Approach for both working conditions. The best performing is 
shown in __bold__. In addition, the table shows other metrics to evaluate this work, including Root Mean Square 
Error (RMSE) and Mean Absolute Error (MAE). This file complements _Table IV_ 
in the submitted paper.
* __RUL Results__ - This file shows the RUL predictions of all bearings in scope proposed by this work. 
This file complements _Fig. 6_ in the submitted paper.
* __Unsupervised Remaining Useful Life Prediction for Bearings with Virtual Health Index.pdf__ - You may find the 
full text of the submitted paper here.


### Contact 
In case of any problems, please contact the corresponding authors:  
* Gilbert Cheng, gilbertcheng(at)hkflair.org  
* Sean Lau, seanlau(at)hkflair.org  
* Nicholas Tam, nicholastam(at)hkflair.org
