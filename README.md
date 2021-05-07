# Receiver Operating Characteristic Assistant (ROCA)

# Warning: The compressed installation package has 900m+, and please make sure the downloaded file is complete. It is recommended to download the installation package separately instead of the compressed package if the network is poor.

Receiver operating characteristic assistant (ROCA) is a toolbox for drawing and analyzing ROC curve based on MATLAB platform. At present, ROC curve and PR curve could be drawn, and the confidence interval could be calculated. At the same time, confusion matrix, sensitivity, specificity, accuracy, precision, recall rate, positive predictive value, negative predictive value, Youden index and other indicators could be calculated. Its characteristic function is to compare and fit several ROC curves and PR curves.

Developer: Wang Luoyu, Lv Yating, Ding Zhongxiang

Department of Radiology, Affiliated Hangzhou First People’s Hospital, Zhejiang University School of Medicine, Hangzhou, Zhejiang, China.

Institute of Psychological Sciences, Hangzhou Normal University, Hangzhou, Zhejiang, China

![image](https://github.com/Luoyu-Wang/ROCA/blob/master/introduction/introduction1.png)
 
Main functions:

1. Draw a single ROC and PR curve

2. Draw several ROC curves and PR curves, and  compare and fit them

3. 16 related indexes including confusion matrix, sensitivity, specificity, accuracy, precision, recall rate, positive predictive value, negative predictive value, Youden index and F1 score could be calculated

4. Delong test

5. Calculate the confidence interval of AUC and other indicators


Installation:

If the runtime of MATLAB 2018b has not  been installed, you can run MyAppInstaller_mcr.exe, ROCA will be installed independently.

If the computer has the runtime of MATLAB 2018b installed, you can click ROCA.exe to run it directly.

Warning: it is recommended to download the installation package directly instead of the compressed package.

Input:

CSV file: The first column is classified label, and the second column is decision value or probability value.


Basic output:

*ROC.TIF: vector diagram of ROC curve.

*PRC.TIF: PR curve vector diagram.

CSV file: contains 16 related indicators.


Advanced analysis:

*ROC.Fig: ROC curve, could be further processed in MATLAB.

*PRC.Fig: PR curve ccould be further processed in MATLAB.

*.mat: contains other indicators, which could be further processed in MATLAB.

Examples：

![image](https://github.com/Luoyu-Wang/ROCA/blob/master/introduction/introduction2.png)

![image](https://github.com/Luoyu-Wang/ROCA/blob/master/introduction/introduction3.png)


If you have any questions, please contact us:

mr.luoyuwang@gmail.com

![image](https://github.com/Luoyu-Wang/ROCA/blob/master/splash.png) 

Αυτή η φωτογραφία δεν είναι για κοπέλα, φυσικά.
