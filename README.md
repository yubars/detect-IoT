# detect-IoT
Detect_IoT is a research work carried out by Yuba Siwakoti at the DoD Center of Excellence in AI &ML at Howard University to detect compromised IoT Infrastructures using public data available at https://data.europa.eu/data/datasets?keywords=variot&locale=en under the VARIoT project co-financed by the Connecting Europe Facility of the European Union.

This work detects compromised IoT devices using machine learning techniques such as Artificial Neural Network, Decision Tree, and Random Forest and Ensemble methods. Performances are compared for metrics Accuracy, Precision, Recall, and F1-Score. Additionally, the significance of features is evaluated for the performance of the models and an enhanced curated (preprocessed, class-balanced, feature-reduced) dataset is presented for further research on IoT network behavior data. 

Overall detection metrics are excellent in all models, however, the ensemble method outperforms others in SMOTE balanced dataset with 98 percent F1-Score with 99 percent Precision. 

The output of this study is presented as a paper and is accepted for publication at Mobihoc'23 (AIoT) that can be available for citation with DOI https://doi.org/10.1145/3565287.3616529.
The accepted paper and enhanced dataset are available for personal/research use only in this repo. Please look first page of the published paper regarding detailed permission. 

# Citation
Please cite this paper and two VARIoT (Original data taken from) as listed below if you are referencing this paper or using the enriched dataset available in this repo.
1. Yuba R. Siwakoti and Danda B. Rawat. 2023. Detect-IoT: A Comparative Analysis of Machine Learning Algorithms for Detecting Compromised IoT Devices. In Proceedings of the Twenty-fourth International Symposium on Theory, Algorithmic Foundations, and Protocol Design for Mobile Networks and Mobile Computing (MobiHoc '23). Association for Computing Machinery, New York, NY, USA, 370–375. https://doi.org/10.1145/3565287.3616529
2. 2021. Data extraction laboratory - VARIoT. Retrieved May 10, 2023 from https://www.variot.eu/2021/10/07/data-extraction-laboratory/
3. Universidad de Mondragón. 2021. IoT security - network traffic under normal and compromised conditions, Dataset. Retrieved May 10, 2023 from https://data.europa.eu/data/datasets?keywords=variot&locale=en

# Dataset
The original dataset is taken from VARIoT https://data.europa.eu/data/datasets?keywords=variot&locale=en. I have downloaded the following 40 files from the given link, and merged them into a single file containing both normal and compromised datasets of 13 devices for 7 categories with 113 features (I added two features later for device_type and Label: normal/compromised).
1.	AP-mikrotik-RB951Ui2HnD-compromised-1.tar.gz
2.	AP-mikrotik-RB951Ui2HnD-compromised-2.tar.gz
3.	AP-mikrotik-RB951Ui2HnD-compromised-3.tar.gz
4.	AP-mikrotik-RB951Ui2HnD-compromised-4.tar.gz
5.	AP-mikrotik-RB951Ui2HnD-normal-2.tar.gz
6.	AP-mikrotik-RB951Ui2HnD-normal.tar.gz
7.	camera-tplink-tapoC200-compromised.tar.gz
8.	camera-tplink-tapoC200-normal-2.tar.gz
9.	camera-tplink-tapoC200-normal.tar.gz
10.	camera-xiaomi-MiHomeSecurityBasicCamera1080p-compromised_check.tar.gz
11.	camera-xiaomi-MiHomeSecurityBasicCamera1080p-normal-2.tar.gz
12.	camera-xiaomi-MiHomeSecurityBasicCamera1080p-normal.tar.gz
13.	hub-google-Home-compromised.tar.gz
14.	hub-google-Home-normal-1.tar.gz
15.	hub-google-Home-normal-2.tar.gz
16.	hub-google-HomeMini-compromised.tar.gz
17.	hub-google-HomeMini-normal-1.tar.gz
18.	hub-google-HomeMini-normal-2.tar.gz
19.	hub-google-NestHub-compromised.tar.gz
20.	hub-google-NestHub-normal-2.tar.gz
21.	hub-google-NestHub-normal.tar.gz
22.	hub-google-NestMini-compromised.tar.gz
23.	hub-google-NestMini-normal-2.tar.gz
24.	hub-google-NestMini-normal.tar.gz
25.	smartbulb-tplink-tapoL510E-compromised.tar.gz
26.	smartbulb-tplink-tapoL510E-normal-2.tar.gz
27.	smartbulb-tplink-tapoL510E-normal.tar.gz
28.	smartbulb-xiaomi-MiLEDSmartBulb-compromised.tar.gz
29.	smartbulb-xiaomi-MiLEDSmartBulb-normal.tar.gz
30.	smartplug-tplink-hs110-compromised.tar.gz
31.	smartplug-tplink-hs110-normal-1.tar.gz
32.	smartplug-tplink-hs110-normal-2.tar.gz
33.	smartplug-xiaomi-MiSmartPlugWifi-compromised.tar.gz
34.	smartplug-xiaomi-MiSmartPlugWifi-normal-2.tar.gz
35.	smartplug-xiaomi-MiSmartPlugWifi-normal.tar.gz
36.	smartsensor-xiaomi-MiSmartSensorSet-compromised.tar.gz
37.	smartsensor-xiaomi-MiSmartSensorSet-normal.tar.gz
38.	smarttv-leotec-AndroidTvBoxGCX2432-compromised.tar.gz
39.	smarttv-leotec-AndroidTvBoxGCX2432-normal-2.tar.gz
40.	smarttv-leotec-AndroidTvBoxGCX2432-normal.tar.gz
Please contact yubaraj@gmail.com if you have any questions or need additional info/data/processing.
