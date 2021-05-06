# ROCA


Receiver operating characteristic assistant (Roca) is a tool for drawing and analyzing ROC curve based on MATLAB platform. At present, ROC curve and PR curve can be drawn, and the confidence interval can be calculated. At the same time, confusion matrix, sensitivity, specificity, accuracy, precision, recall rate, positive predictive value, negative predictive value, Youden index and other indicators can be calculated. Its characteristic function is to compare and fit several ROC curves and PR curves.

Developer: Wang Luoyu, LV Yating, Ding Zhongxiang

![image](https://github.com/Luoyu-Wang/ROCA/blob/master/splash.png) ![image](https://github.com/Luoyu-Wang/ROCA/blob/master/splash.png)

![image](https://github.com/Luoyu-Wang/ROCA/blob/master/introduction/introduction1.png)
 
Main functions:

1. Draw a single ROC and PR curve

2. Draw several ROC curves and compare and fit pr

3. 16 related indexes including confusion matrix, sensitivity, specificity, accuracy, precision, recall rate, positive predictive value, negative predictive value, Youden index and F1 score can be calculated

4. Delong test

5. Calculate the confidence interval of AUC and other indicators


Installation:

If the runtime of MATLAB 2018b is not installed, you can run MyAppInstaller_mcr.exe, ROCA will be installed independently.

If the computer has the runtime of MATLAB 2018b installed, you can click ROCA.exe to run it directly.


Input:

The first column is classified label, and the second column is decision value or probability value.


Basic output:

*ROC.TIF: vector diagram of ROC curve.

*PRC.TIF: PR curve vector diagram.

CSV file: contains 16 related indicators.


Advanced analysis:

*ROC.Fig: ROC curve, can be further processed in MATLAB.

*PRC.Fig: PR curve can be further processed in MATLAB.

*.mat: contains other indicators, which can be further processed in MATLAB.

Examples：

![image](https://github.com/Luoyu-Wang/ROCA/blob/master/introduction/introduction2.png)

![image](https://github.com/Luoyu-Wang/ROCA/blob/master/introduction/introduction3.png)
  
