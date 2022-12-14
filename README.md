Smart weather station

Problem statement:

The goal of the project is to create a low-cost, low-power, reliable, accurate, easy to install and maintain weather station, with no mechanical moving parts for measuring all weather conditions with a focus on rain and wind, based on ultra-low power machine learning at the edge, that can be deployed locally.
This weather station can be deployed in a farm, for example, to provide local conditions and assist farmers in deciding when to plant crops.

TEAM : AI4AFRICA(Nigeria)

Team Members: 

•	Isaiah Terhide Barnabas isaiahterhide@gmail.com

•	Aaron Emmanuel  aaronemmanuel054@gmail.com

•	Michael Selnan Meshach  michaelmeshach4545@gmail.com

•	Guda Blessed (Mentor)	gudablessed@gmail.com

Description :

This Ripo contain a dataset, Report, code, PPT and Demo  on activities of team “AI 4 Africa” towards the TinyML Challenge 2022 on building a Smart Weather Station. The team collected a total 7,800 secs of audio recordings from Kogi state in Nigeria over a two month period. These recordings were collected using an android smartphone. MFCC was extracted from the audio recordings which was used to train three ML models, a Support Vector Regression, a Deep Neural Network (DNN) and a CNN model. The models were tested on different splits. Two minute chunks were shown to be most accurate, with the DNN model showing the lowest MAPE of  44.47%. The model was pruned and quantized for onward deployment on an ESP32 board. The model did not show a loss in performance due to theTFLite conversion. The size of the final model is just about 3.82kB which is suitable for deployment on most common microcontrollers. This validates the approach proposed for prediction of rainfall in low resource settings.

Repository Description:

The Ripo contain the following ;

•	Code and description

•	Slide to be used for presentation 

•	Report 

•	Dataset (https://drive.google.com/drive/folders/11aBRhAbnx7qNujvhpkLcuiRkpScLde7u?usp=share_link)

•	Implementations and real-word tests 

•	Demo
