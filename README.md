# Computer-Aided-Diagnosis-of-NAFLD-using-ML

### Objective: 
In this study we explore the role of machine learning and deep learning in improving
computer-aided diagnostic methods for Non-Alcoholic fatty liver disease. This study explores two
main non-invasive diagnostic methods, namely using predominantly laboratory bio-marker data
(NHANES 2017-18) and the b-mode ultrasound image dataset containing parasagittal liver-kidney
ultrasounds of 55 patients.

### Methods: 
For NHANES 2017-18 data we proposed a deep learning stacked ensemble model
containing 3-layer MLP, 5-layer MLP and Random Forest models. We individually compared the
models’ performances and also illustrated the advantage of ensemble. For Ultrasound images data, we
automated the process of liver region extraction using a fine-tuned version of a pretrained transformer
model U-net.Furthermore, our proposed method involved extracting texture features from image
sequences and stacking them to serve as an auxiliary input to a CNN+Bi-LSTM model.

### Results: 
The stacked ensemble achieved the performance of a Recall of 0.997 ,Precision of 0.998 ,
accuracy of 99.8, AUC score of 0.997. The proposed method
Achieved 87% accuracy, recall 0.84, precision of 0.9, f1-score of 0.88 and specificity of 0.7.
