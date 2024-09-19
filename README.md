# Urban Arterial Traffic Volume and Travel Time Estimation with Use of Data Driven Models

Chris Konstantinidis, Email: xrhstosk7@gmail.com, LinkedIn: www.linkedin.com/in/chris-konstantinidis-35431a305 

Committed and driven Civil Engineering MSc graduate specializing in Transportation Engineering with a keen interest in Data Science and Machine Learning. Equipped with a strong foundation in analytical problem-solving and quantitative computational methods, I am passionate about leveraging my skills to address a wide variety of complex challenges through innovative and evidence-based approaches.

This GitHub project serves as a comprehensive summary of my Masters Thesis which I completed as part of my MSc in Civil Engineering with a specialization in Transportation Engineering.  

Instructions:

1) Read the PDF: For a solid understanding of the project, begin by reading the provided PDF document.
2) Explore the Data: Upon reaching Section 3 (Implementation and results), a brief look at the Trafficdata2.csv file is recommended for familiarization with the project's data.
3) Deep Dive into Models: After reading about the development, evaluation, and results of the models in the text, their detailed implementation is provided in the uploaded Jupyter Notebooks.
4) Reproduce the Results: The included Binder link (https://mybinder.org/v2/gh/ChrisKonstantinidis/MScThesis.git/HEAD) provides an executable Jupyter Notebook environment where the project's results can be reproduced without the requieremetnt of any software installation.

Title: Urban Arterial Traffic Volume and Travel Time Estimation with Use of Data Driven Models

Abstract:

This work aims to develop traffic prediction models, with a specific focus on traffic volume and travel time 
of an urban arterial. These models are based on Machine Learning algorithms, which find frequent 
application in the literature for various forecasting tasks. The traffic data that were utilized in the 
development process were sourced from a road section of Alexandras Av. in Athens. Finally, a comparison 
is drawn between Machine Learning models, the BPR Volume-Delay function, and a BPR-ML hybrid 
approach. According to the results, the models are capable of accurate predictions with an acceptable fit 
to the data. The findings reveal that Machine Learning methods exhibit superior forecasting capabilities. 

Keywords: machine learning, traffic forecasting, traffic volume, travel time, decision trees, GBDT, BPR 
function

Objectives and use case:
The primary goal of my thesis was to develop Machine Learning models capable of 
accurately forecasting traffic volume and travel time within an urban road segment. This 
involved a comprehensive process including data collection, processing, visualization, statistical 
analysis and feature engineering. Furthermore, I employed an optimized version of the BPR 
function —a domain-specific traffic flow equation— as well as a hybrid BPR-ML model (Physics 
Informed Machine Learning) for the forecasting task. The rationale behind this study was to 
explore the prediction of traffic parameters using readily available data and simple models 
comprising a concise set of variables, while also comparing contemporary ML techniques with 
conventional approaches (BPR Function). 

In more detail, network wide travel time data are easily accessible so traffic volume prediction models that rely solely on travel time data and some easily constructed simple features can be a great tool to estimate traffic volumes where the necessary infrastructure is misding. Generally, simpler, less data intensive models models are more time and cost efficient.zoning Pricing strategies of roads , environmental metrics, urban planning investment decision , congestion detection and traffic signal and route optimizaiton, travel time estimate for drivers, future demand, it's smart city inyegration, supply chain efficiency, event tourism planning, impact of intervention assessment , road wear and tear and budget allocation, public transport demand planning, ETA, emergency optimization ....................

Data folder:

All the data used in the project is contained in this folder. Trafficdata2 is the final database used for the model developement, after merging travel time and traffic volume of the two inductive loops at the start and end of the road segment  data and handling of missing values and errors . Columns highlighted with blue pertain to travel time data, while columns highlighted with red represent traffic volume data from two inductive loops (MS407,Ms423). Green columns represent the features that were constructed for the machine learning models. The rest of the files are raw traffic volume data that were providedform National Technical University of Athens. Travel time data for the specific road segment were extracted from .... .......

PDFs folder:

In this folder there are two Pdf files. The one named ... Is a condensed and translated version of my thesis. The results from the all the models are presented in the last pages. 
The pdf named ... is a conference paper based on my thesis that I published at the IFAC..........

Jupyternotebooks folder:

This folder contains all the code that was utilized for the project. 
 
Correlation + Statistical Analysis: Correlation between thetarget traffic variables is examined in this notebook. Also, some statistical analysis of the data was carried out in order to understand better the relationship of the variables and detect anomalies. In the case of traffic volume prediction, outlier handling was deemed as an appropriate solution to enhance performance of the models. This process is  described in detail in the thesis text.

TrafficVolume_pred: A decision tree and a GBDT model were used to forecast traffic volume.

TravelTime_pred: A decision tree, a GBDT model, the BPR function and a hybrid BPR-ML model were used to forecast travel times. 

Supporting Plots: In this notebook there is code for several graphs that were constructed to provide clarity on the theoretical framework of the thesis.
