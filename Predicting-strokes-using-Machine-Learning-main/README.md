# Predicting strokes using Machine Learning
Introduction 
Strokes occur when there is a significant reduction or obstruction in the blood flow to the brain. Fat build-up is typically the cause of obstruction symptoms can vary.
Mild symptoms are present in some people. Others display severe symptoms. Some individuals experience nausea—shortness of breath, dizziness, or sudden dizziness without 
exhibiting other symptoms. Older individuals are especially vulnerable.[1] Machine learning (ML) offers a quick and accurate prediction result, and it has developed into 
a potent tool in healthcare settings, providing stroke patients with individualized therapeutic care. Although there is a definite need for study, some research fields
are not receiving adequate attention for scientific exploration, despite the expanding use of ML and Deep Learning in healthcare. Therefore, the purpose of this work 
is to carefully review papers for each category after classifying state-of-the-art ML approaches for brain stroke into four groups based on their functionalities or 
similarities. Results from the ScienceDirect web scientific database on ML for brain stroke from 2007 to 2019 revealed 39 studies. SVM (Support Vector Machine), or 
Support Vector Machine, is determined to be ideal. Models for stroke issues in ten investigations. In addition, most studies are on stroke diagnosis, whereas the 
majority are on stroke treatment, indicating a research gap that needs to be filled. Similarly to this, CT pictures are a standard dataset for strokes. Finally, 
effective methods employed for each category include SVM and Random Forests. The current study highlights the value of various ML techniques used in brain stroke.
[2] In this work, we will investigate the use of Machine Learning to predict strokes before they occur using features such as age, blood pressure, ergonomics, etc.
We hope this helps physicians save more lives.

Objectives:
This research project aims to improve patient healthcare outcomes and lower healthcare spending on heart-stroke treatment. These objectives can be achieved by: 
•	detecting the disease before complications.
•	Identify risk factors and reduce the risk of heart strokes. 

Data Exploration
The data has 12 columns without the id and class 10.
Attribute Information
1) id: unique identifier
2) gender: "Male," "Female," or "Other."
3) age: age of the patient
4) Hypertension: 0 if the patient does not have hypertension. One of the patients has hypertension
5) Heart Disease: 0 if the patient does not have any heart diseases; 1 if the patient has a heart disease
6) ever married: "No" or "Yes."
7) work type: "children," "Govt job," "Never worked," "Private," or "Self-employed."
8) Residence type: "Rural" or "Urban."
9) avg_glucose_level: average glucose level in blood
10) BMI: body mass index
11) smoking status: "formerly smoked," "never smoked," "smokes," or "Unknown"*
12) Stroke: 1 if the patient had a stroke or 0 if not

From the visulaization it is clear that oversampling data is having better predictions scores than original data.

What can we do furthur?

May be explore gridsearch and stratified fold implementation could be give better results.
