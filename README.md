# Privileged Scaffold Analysis of Natural Products with Deep Learning-based Indication Prediction Model
In this study, we propose a privileged scaffold identification strategy for natural products. The term ‘privileged scaffold’ or ‘privileged structure’ was first used by Evans in the 1980s to describe scaffolds that could serve as ligands for multiple targets. And the notion was later expanded to that a scaffold is privileged if multiple molecules of the same scaffold have bioactivity. Here we use the term and make some restrictions, that is, multiple molecules of the same scaffold have bioactivity for the same indication. 
To identify privileged scaffolds, a multi-task deep learning model was first trained on the MDDR dataset for indication prediction. By using larger training data than approved drugs, the model could learn how to predict the indication of compounds better. The trained model was applied to the natural product dataset, which was composed of six public datasets to provide more diverse scaffolds. Cross-validation showed that the model had good discrimination ability. The identification strategy made use of entropy-based information metrics to obtain privileged scaffolds for each indication. A Privileged Scaffold Dataset (PSD) for one hundred indications was obtained, which could be used as a novel source for lead discovery and optimization.  

![image](https://github.com/wllllg/Privileged_Scaffold/raw/master/img/privileged_scaffolds_Shannon_Entropy.jpg)
**Figure 1. Privileged Scaffolds Identified using Shannon Entropy.**
![image](https://github.com/wllllg/Privileged_Scaffold/raw/master/img/privileged_scaffolds_p_value_antihypertensive.jpg)
**Figure 2. Privileged Scaffolds for Antihypertensitve Identified using p-value.**


![](http://latex.codecogs.com/gif.latex?\I =\left\{I_{1}, I_{2}, \ldots, I_{m}\right\})
