# ArrhythmiaResearch

Prediction of Arrhythmias using Support Vector Machines and Reduced Feature Subset of ECG Variability Metrics

Sudden cardiac arrest is the leading cause of death for adults in the United States, killing 325,000 each year. This condition, during which the heart suddenly stops beating, is caused by irregular heartbeat rhythms or arrhythmias. An implantable cardioverter defibrillator (ICD), a device that sends electrical pulses to the heart, may be used to counteract arrhythmia episodes. However, as many as 100,000 patients who require this treatment do not receive it each year. Many of those who receive ICDs will never activate them, but will risk the dangerous and costly surgery to implant them.
This study proposed the use of support vector machine (SVM) classifiers with measures derived from a patient’s electrocardiogram (ECG) signal to predict short-term risk of arrhythmia episodes. An ECG monitors the electrical activity of the heart, and this study used a variety of measures that evaluated the variability of the heartbeats derived from an ECG signal. A feature selection algorithm then chose the measures that improved the accuracy of the SVM classifiers the most. The SVM classifiers implemented a learning algorithm that maximized the distance between the decision function that categorized the patients into the two different classes and the data points that were closest to the decision function. They were used to classify the patients as either at-risk or healthy using the measures as data points for each patient. The SVM classifiers as well as the feature selection were implemented in MATLAB, a computing environment.
The strongest performing classifier had an overall classification accuracy of 92.12% for 165 patient ECG signal records. The proposed classification model could be used in ICD recommendation as well as short-term prediction of arrhythmia episodes in order to increase response time for patients at higher risk of experiencing arrhythmia episodes.