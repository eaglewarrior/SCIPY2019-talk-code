# SCIPY2019-talk-code
Codes for submission made for scipy2019 talk

 Anomaly detection at scale and its applications
 
 It contains codes demonstrating ML techniques used in industries for detecting anomalies (Supervised techniques)
 
 Also unsupervised deeplearning techniques for anomaly detection 
 
 We have also attached architecture both for Hadoop and cloud architecture which is complete design for data pipleine end - to -end streaming anomaly detection  at scale with big data.

## Abstract

Abstract:  

Streaming data analytics is one of the hottest topics in the AI analytics field. Its application is not only limited to commercial sectors like e-commerce (e.g real-time customer analytics), banking (e.g fraud detection ) but also in the health sector (e.g. real-time HBR tracking, blood sugar tracking, etc ). Streaming data analytics can also be embedded with IoT (Internet of things) for use cases like traffic sensors, health sensors, transaction logs, and activity logs are some of the use cases for embedding streaming analytics and IoT. In this talk, we will present firstly different anomalies detection techniques used in industries and how that can be scaled up in real-time using streaming data , and how health care industry can leverage its services and scale up its efficiency to serve people in using advanced technique ,will discuss how wearable devices can be a data source for that. Ubiquitous deployment of low-cost wearable healthcare devices and proactive monitoring of vital physiological data are widely seen as a solution for the high costs and risks associated with personal healthcare. The healthcare data generated from these sensors cannot be manually analyzed for anomalies by clinicians due to its scale and therefore automated techniques have to be developed.
Now describing our approach on how to detect anomalies at scale, by combining the power of big data and machine learning. We will describe two approaches firstly on everyone's favourite Hadoop stack and secondly on the cloud which will make the system more scalable. Will demonstrate architecture proposal and techniques on how to build a NER (Near real-time) system as when we deal with real-time data we need to plan out on handling the real-time incoming data and techniques on windowing and how to connect big data components to serve the purpose and handle the volume, variety, and velocity of the data generated. We will discuss how we can scale up the architecture or say increase flexibility by taking it to the cloud by using services like GCP, azure, aws etc. We will show techniques in machine learning using python which is used in industries to detect anomalies like different ML algorithms, deep learning techniques and ML techniques using python is currently in trend for detecting real-time anomalies at scale on cloud. We will discuss the metrics and data imbalance handling techniques used for detecting anomalies in data. .We will demonstrate the anomalies detection pipeline using python and ml libraries and also how unsupervised techniques can be beneficial for detecting anomalies :
1) Data Preprocessing and exploratory data analysis
2) Demonstration of techniques and metrics used in anomalies detection or unbalanced data handling
3) Using boosting algorithm and deep learning techniques and measure its performance by metrics decided
4) Predicting on test data
Real-time analytics is the trend of data industry that has large scale applications in not only in e-commerce industries but also in the health sector as streaming data is future data, and this architecture can be used as a common pipeline for collecting and identifying anomalies with bit changes in algorithms as per domain knowledge on different types of data at large scale in real-time.
