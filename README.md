# SVM-SFS-Classification
To perform one-on-one comparisons of quantitative features between different groups, we utilized the Mann-Whitney U test. In all comparisons, statistical significance was determined with a P value < 0.05. Subsequently, we conducted pairwise comparisons using the Mann-Whitney U test, denoting significant differences between groups as follows: *, **, and *** for P < 0.05, P < 0.005, and P < 0.0005, respectively. "ns" indicates non-significant differences in pairwise comparisons.
![PID](https://github.com/mansour2002/SVM-SFS-Classification/blob/main/Figures/PID%20(%25).png)
![PID Ratios](https://github.com/mansour2002/SVM-SFS-Classification/blob/main/Figures/PID%20Ratios.png)

 
Our classification model is built around a SVM classifier that utilizes radial basis function (RBF) kernels with hyperparameter values C = 1 and gamma = 'scale'. SVM classifiers were employed for binary and multiclass classification among different groups.Both binary and multiclass classifications underwent a 10-fold cross-validation process. In all classification tasks, we implemented sequential forward selection (SFS), a technique rooted in the greedy search algorithm, to identify the optimal subset of features that maximize classification accuracy. 
![AUC](https://github.com/mansour2002/SVM-SFS-Classification/blob/main/Figures/Fig4_2.png)
![AUC](https://github.com/mansour2002/SVM-SFS-Classification/blob/main/Figures/Fig4_4.png)

