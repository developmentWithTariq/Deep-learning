data set that i  used here i take from kaggle.com 
the data is the pictures of ladies having two classes one is average face (face of ladies without facial) and other is beautifull face (face of ladies with facial)
for more info about data click https://www.kaggle.com/gpiosenka/beauty-detection-data-set

**we will note the diffrences between the validation accuracy of Conv2d and Separableconv2D**



one layer of conv2d has generate 896 params and the other hand one layer of separableconv2d has generate just 155 param (you can see above)
val accuracy of both architecture are all most same on 20 epochs 
for confirm please see notebook 
