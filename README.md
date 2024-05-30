# Analyse des Prêts Bancaires

Ce projet analyse les données de prêts bancaires pour identifier les tendances et les facteurs influençant l'octroi de prêts.

## Prérequis

Assurez-vous d'avoir les logiciels suivants installés :

- Python 3.x
- Jupyter Notebook
- Les bibliothèques Python suivantes :
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

Vous pouvez installer les bibliothèques requises avec la commande suivante :
pip install pandas numpy matplotlib seaborn scikit-learn

## Utilisation
Ouvrez le fichier prets_bancaire.ipynb avec Jupyter Notebook :
Exécutez chaque cellule du notebook pour générer les analyses et les graphiques.

## Tests
Pour vérifier que tout fonctionne correctement, exécutez les tests inclus dans le notebook. Les tests sont mis en évidence en gras pour faciliter leur identification.


### Test de validation des données
assert len(df) > 0, "Le DataFrame est vide"
Test des fonctionnalités de transformation des données :

### Test de transformation
df_transformed = transformer_donnees(df)
assert 'nouvelle_colonne' in df_transformed.columns, "La transformation n'a pas ajouté la colonne attendue"
## Contribuer
Les contributions sont les bienvenues ! Veuillez soumettre un pull request pour les fonctionnalités ou les corrections de bugs.

### Forkez le projet
Créez une branche pour votre fonctionnalité 
Commitez vos changements
Poussez vers la branche 
Ouvrez un pull request
