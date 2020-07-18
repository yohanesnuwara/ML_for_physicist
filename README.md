![ML for physicist banner](https://user-images.githubusercontent.com/51282928/80908777-ee1b0300-8d4c-11ea-9c42-36378a4d811b.PNG)

## Machine Learning for Physicist 2020 Summer Course

> **Instructor**: Prof. Florian Marquardt<br>
> **Institution**: Max Planck Institute for the Science of Light, Erlangen, Germany

### Links

* [Course Website](https://pad.gwdg.de/s/HJtiTE__U)
* [Course GitHub](https://github.com/FlorianMarquardt/machine-learning-for-physicists)
* [Google Group](https://groups.google.com/forum/?utm_medium=email&utm_source=footer#!forum/machine-learning-for-physicists)
* [2019 course videos](https://podcasts.apple.com/us/podcast/id1490099216)
* [2019 Les Houches lecture handout](https://github.com/yohanesnuwara/ML_for_physicist/blob/master/materials/LesHouchesMachLearning_Complete2.pdf)

### My Mini Project

![neural network eor screening](https://user-images.githubusercontent.com/51282928/87856913-96079c00-c94c-11ea-981c-eee1d6b43744.jpg)

At the end of this summer training program, I made a mini-project. I name this mini-project: `Neural Network Application for Enhanced Oil Recovery (EOR) Screening`. EOR screening is part of important practices in the oil and gas industry. Main reference of this project is EOR screening metric proposed by Taber et al (1997) in their [SPE-35385-PA paper](https://www.onepetro.org/journal-paper/SPE-35385-PA). 

> The neural graph above is created in [NN SVG](https://alexlenail.me/NN-SVG/) website. Thanks to [@alexlenail](https://github.com/alexlenail).

Some key facts of this project are:

* I generated datasets using random technique, **245 dummy field observations**, each containing **6 reservoir fluid and rock parameters**. These datasets are the my **train datasets**.
* These 6 parameters are the **input features** for the NN.
* The datasets are **labeled** with each of **7 EOR methods**.
* I generated as well, another **50 dummy field observations**, without label. These datasets are the my **test datasets**, for prediction.
* In the first trial, without hyperparameter tuning, **1 hidden layer with 100 hidden neurons** is used. 

> Find the train CSV data [here]() and the test data [here]()

What can still be improved?

* To increase accuracy of prediction, the other **3 categorical parameters** that were not used before, could be included. The thing needed is to encode categorical parameters.
* **Real datasets** can be obtained. This [paper](https://github.com/yohanesnuwara/ML_for_physicist/blob/master/data/EOR%20Literature%20Search%23.pdf) by Lake & Walsh (UT Austin, 2008) listed all publications about EOR, and this [XLSX file](https://github.com/yohanesnuwara/ML_for_physicist/blob/master/data/EOR-database-WEO18.xlsx) by World Economic Outlook (2018) listed as much as **233 EOR fields**.
* This real dataset will be released soon. 
