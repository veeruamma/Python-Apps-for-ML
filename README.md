# Python-Apps-for-ML

Python applications developed for Machine Learning algorithms for visulaization of data and other stuffs.

**Drawdata** : Python application used to create our dataset by drawing it on iframe provided by drawdata module. It's basically helps woth classification problem dataset.

Example :

![image](https://user-images.githubusercontent.com/30498799/116178360-03e8bb80-a748-11eb-9fb6-9561f197b453.png)


Once, the dataset created then we have options to download or just copy the data in several formats such as json, csv. 

In case of data copied, it's easy to use the library pandas to read the clipboard and use it for further analysis as shown below. this data is generated for four classes knows as **a, b, c, and d**


![image](https://user-images.githubusercontent.com/30498799/116178499-427e7600-a748-11eb-9ddb-7170eb5531af.png)




The disadvantage of this library is that can't create more than 2 dimensional dataset


**AutoViz :** It performs automatic visualization of any dataset with one line. Give any input file (CSV, txt or json) and AutoViz will visualize it.

Install using "pip install autoviz"
Import with "from autoviz.AutoViz_Class import AutoViz_Class"
Instantiate a class "AV = AutoViz_Class()"
Run an experiment in the following line with our data set:
