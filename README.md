# Support Vector Regression (SVR)

Ce référentiel contient le code source et les fichiers associés pour un projet de régression vectorielle de support (SVR) en utilisant Python et la bibliothèque scikit-learn.

## Contexte du projet

Une machine à vecteurs de support (SVM) effectue la classification en trouvant l'hyperplan qui maximise la marge entre les deux classes. Les vecteurs (cas) qui définissent l'hyperplan sont les vecteurs supports.

Support Vector Machine peut également être utilisé comme méthode de régression, en conservant toutes les principales caractéristiques qui caractérisent l'algorithme (marge maximale). La régression vectorielle de support (SVR) utilise les mêmes principes que la SVM pour la classification, avec seulement quelques différences mineures. Tout d'abord, parce que la sortie est un nombre réel, il devient très difficile de prédire l'information disponible, qui a des possibilités infinies. Dans le cas d'une régression, une marge de tolérance (epsilon) est fixée en approximation de la SVM qu'aurait déjà sollicitée le problème. Mais outre ce fait, il y a aussi une raison plus compliquée, l'algorithme est donc plus compliqué à prendre en considération. Cependant, l'idée principale est toujours la même : minimiser l'erreur, individualiser l'hyperplan qui maximise la marge, en gardant à l'esprit qu'une partie de l'erreur est tolérée.

## Installation

Pour exécuter le code de ce projet, vous devez avoir Python 3.x et les bibliothèques suivantes installées :

* NumPy
* Pandas
* Matplotlib
* scikit-learn

Vous pouvez installer ces bibliothèques en utilisant pip :
```
pip install numpy pandas matplotlib scikit-learn
```

## Fichiers du projet

* `SVR.ipynb` : Jupyter Notebook contenant le code source et les explications du projet.
* `Position_Salaries.csv` : Fichier CSV contenant les données utilisées dans le projet.
* `README.md` : Ce fichier.

## Utilisation

Ouvrez le fichier `SVR.ipynb` dans Jupyter Notebook et suivez les instructions fournies dans le notebook.

## Résultats

Le projet montre comment entraîner un modèle SVR sur un ensemble de données et comment prédire une nouvelle valeur en utilisant ce modèle. Les résultats sont visualisés à l'aide de Matplotlib.

## Contribution

Les contributions à ce projet sont les bienvenues. Si vous souhaitez contribuer, veuillez ouvrir une demande d'extraction (pull request) avec vos modifications.

## Licence

Ce projet est sous licence MIT. Consultez le fichier `LICENSE` pour plus de détails.

## Crédits

For workshop1 All crédits to [Agéron](https://github.com/ageron)

Ce projet a été créé par Philippe BONNIN.
