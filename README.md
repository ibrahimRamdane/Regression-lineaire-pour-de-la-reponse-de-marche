# Regression-lineaire-pour-de-la-reponse-de-marche

## Description
Le but de ce projet était d'obtenir le meilleur score pour une regression sur l'indice de réponse de marché.
J'ai essayé différents modèles et également plusieurs méthodes pour obtenir les features qui me permettent d'obtenir le meilleur score. J'ai notammeent tenté
de ne pas prendre en compte les valeurs les moins représentées. J'ai également essayé d'enlever les features les moins importantes (les moins corrélées avec 
l'indice de marché), néanmoins les résultats n'ont vraiment pas été bon. Que ce soit la regression linéaire avec Lasso ou avec Ridge, il n'était pas possible d'obtenir 
un score acceptable. Seul RandomForest offrait de bon résultat pour la regression linéaire. 
