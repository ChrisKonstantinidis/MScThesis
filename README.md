# Urban Arterial Traffic Volume and Travel Time Estimation with Use of Data Driven Models

Chris Konstantinidis, Email: xrhstosk7@gmail.com, LinkedIn: www.linkedin.com/in/chris-konstantinidis-35431a305 

Committed and driven Civil Engineering MSc graduate specializing in Transportation Engineering with a keen interest in Data Science and Machine Learning. Equipped with a strong foundation in analytical problem-solving and quantitative computational methods, I am passionate about leveraging my skills to address a wide variety of complex challenges through innovative and evidence-based approaches.

This GitHub project serves as a comprehensive summary of my Masters Thesis which I completed as part of my MSc in Civil Engineering with a specialization in Transportation Engineering.  

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

In more detail, given the easy accessibility of network-wide travel time data, traffic volume prediction models that use solely travel time data along with a few basic features can be highly effective for estimating traffic volumes, particularly in areas where infrastructure is lacking. Generally, these simpler, less data-intensive models are not only cost-effective but also time-efficient. Accurate traffic prediction models offer a wide range of practical applications that greatly benefit urban and transportation planning. They are instrumental in zoning and land use planning, providing critical insights that guide development based on anticipated traffic patterns. These predictions support pricing strategies for roads, such as congestion pricing, which helps manage traffic demand and alleviate congestion. They also play a key role in assessing environmental metrics, evaluating the impact of traffic on air quality and emissions, and guiding efforts to minimize environmental harm. In urban planning and investment decisions, traffic forecasts are essential for directing infrastructure investments and anticipating future demand, helping stakeholders make informed decisions about upcoming projects. They enhance congestion detection and traffic signal optimization, improving real-time traffic management and flow. For drivers, these predictions assist in route optimization, offering efficient travel suggestions to reduce delays. Furthermore, predicting future traffic demands integrates with smart city technologies and enhances supply chain efficiency by optimizing logistics and route planning. They are valuable for event and tourism planning, managing increased traffic during major events, and evaluating the impact of interventions such as new infrastructure on traffic conditions. These forecasts also aid in managing road wear and tear and budget allocation for maintenance, ensuring resources are effectively used. Additionally, they support public transport demand planning, leading to optimized service schedules and improved travel experiences.

Instructions:

1) Read the PDF: For a solid understanding of the project, begin by reading the provided PDF document.
2) Explore the Data: Upon reaching Section 3 (Implementation and results), a brief look at the Trafficdata2.csv file is recommended for familiarization with the project's data.
3) Deep Dive into Models: After reading about the development, evaluation, and results of the models in the text, their detailed implementation is provided in the uploaded Jupyter Notebooks.
4) Reproduce the Results: The included Binder link (https://mybinder.org/v2/gh/ChrisKonstantinidis/MScThesis.git/HEAD) provides an executable Jupyter Notebook environment where the project's results can be reproduced without the requieremetnt of any software installation.

PDFs folder:

1. "Urban-Arterial-Traffic-Volume-and-Travel-Time-Estimation-with-Use-of-Data-Driven-Models": This PDF offers a translated and condensed overview of the original thesis, covering the rationale, literature analysis, theoretical framework, methodology, and development of the selected models. The concluding section presents a detailed summary of the key findings and results.
2. "Conference Paper": This PDF is the conference paper that was presented at the 17th IFAC Symposium on Control in Transportation Systems (CTS 2024), based on the original MSc thesis.

Data folder:

This folder contains all the data used in the project. 

The final database used for model development, Trafficdata2.csv, was generated by merging and aligning travel time and traffic volume data from two inductive loops (MS407 and MS423) located at the start and end of the road segment. The data was processed to handle missing values and correct errors. In Trafficdata2.csv, blue columns represent travel time data, red columns correspond to traffic volume data from the two loops (MS407, MS423), and green columns contain features specifically engineered for the machine learning models. The remaining files contain raw traffic volume data sourced from databases of National Technical University of Athens. Travel time data for the road segment was extracted from Google Maps via Outscraper (https://outscraper.com/).

Jupyternotebooks folder:

This folder contains all the code that was utilized for the project in Jupyter Notebooks format. 
 
1. Correlation + Statistical Analysis: This notebook explores the correlations between the target traffic variables and conducts a statistical analysis of the data to better understand the relationships between variables and identify anomalies in the data. The notebook delves into the outlier handling process, which was deemed effective for enhancing the performance of the traffic volume prediction models, as described in detail in the thesis text.

2. TrafficVolume_pred: A Decision Tree and a Gradient Boosting Decision Tree (GBDT) model were employed to forecast traffic volume.

3. TravelTime_pred: This notebook presents the code for forecasting travel times using a Decision Tree model, a GBDT model, the Bureau of Public Roads (BPR) function, and a hybrid BPR-ML model.
  
4. Supporting Plots: This notebook contains the code for various graphs that were constructed to illustrate the theoretical framework of the thesis.
