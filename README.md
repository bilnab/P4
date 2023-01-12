# P4  
 <img src="https://github.com/bilnab/P4/blob/main/img/kag.png" width="150"> <img src="https://github.com/bilnab/P4/blob/main/img/lime.jpg" width="150"> <img src="https://github.com/bilnab/P4/blob/main/img/shap.png" width="150">  
 <img src="https://github.com/bilnab/P4/blob/main/img/pandas.png" width="150"> <img src="https://github.com/bilnab/P4/blob/main/img/seaborn.png" width="150"> <img src="https://github.com/bilnab/P4/blob/main/img/sk.png" width="150"> <img src="https://github.com/bilnab/P4/blob/main/img/scipy.png" width="150"> <img src="https://github.com/bilnab/P4/blob/main/img/statsmodel.png" width="150">  
 
 
**Projet de modélisation supervisée - SCORING**  
  
**Bon ou mauvais Payeur?** :    
Ce projet provient à l'origine d'une compétion Kaggle dont le but était de sélectionner le meilleur modèle de scoring pour sa clientèle

L'enjeu est de developper un modèle de scoring:   
* pour aider à décider si un prêt peut être accordé à un client ou non  
* qui doit etre facilement interprétable

## Ressources:
Jeu de données:  
[lien](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Impl%C3%A9menter+un+mod%C3%A8le+de+scoring/Projet+Mise+en+prod+-+home-credit-default-risk.zip)  
  
Ressources utiles sur l'interprétabilité en python:  
[lien 1](https://towardsdatascience.com/interpretability-in-machine-learning-70c30694a05f)  
[lien 2](https://christophm.github.io/interpretable-ml-book/)  
[lien 3](https://coderzcolumn.com/tutorials/machine-learning/how-to-use-lime-to-understand-sklearn-models-predictions)  
[lien 4](https://coderzcolumn.com/tutorials/machine-learning/how-to-use-lime-to-understand-sklearn-models-predictions)  
[lien 5](https://coderzcolumn.com/tutorials/machine-learning/how-to-use-lime-to-understand-sklearn-models-predictions)  

## Script   
[un notebook commenté d'analyse descriptive](https://github.com/bilnab/P4/blob/main/P4%20analyse%20descriptive.ipynb)  
[un notebook commenté de modélisation](https://github.com/bilnab/P4/blob/main/P4%20modelisation.ipynb):  
* qui transforme et construit de nouvelles variables  
* qui met en oeuvre un certains nombre de taches de preprocessing comme:  
  * l'undersampling  
  * le split train/test  
  * la transformation one hot encoder de variables categorielles  
  * le scaling  
  * l'imputation  
* qui met en oeuvre une fonction de scoring bespoke adaptée  
* qui entraine différents modèles supervisés répondant aux attentes du metier:  
  * regression logistique, linear SVM classifier, SVM classifier  
  * random forest  
  * bagging, adaboost, gradient boosting  
* qui adapte des hyperparamètres d'un modèle  
* qui évalue et interprète les performances d'un modèle supervisé classique  
 
## Présentation PDF:  
[pdf complet](https://github.com/bilnab/P4/blob/main/P4.pdf)  
<img src="https://github.com/bilnab/P4/blob/main/img/P4%20pres.png" height="300">
