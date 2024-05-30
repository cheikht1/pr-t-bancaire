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

bash
pip install pandas numpy matplotlib seaborn scikit-learn
Installation
Clonez le dépôt GitHub :
bash
Copy code
git clone https://github.com/votre-utilisateur/votre-depot.git
cd votre-depot
Assurez-vous d'avoir les fichiers de données nécessaires dans le même répertoire que le notebook Jupyter.
Utilisation
Ouvrez le fichier prets_bancaire.ipynb avec Jupyter Notebook :

bash
Copy code
jupyter notebook prets_bancaire.ipynb
Exécutez chaque cellule du notebook pour générer les analyses et les graphiques.

Tests
Pour vérifier que tout fonctionne correctement, exécutez les tests inclus dans le notebook. Les tests sont mis en évidence en gras pour faciliter leur identification.

Exemple de test :

python
Copy code
# Test de validation des données
assert len(df) > 0, "Le DataFrame est vide"
Test des fonctionnalités de transformation des données :

python
Copy code
# Test de transformation
df_transformed = transformer_donnees(df)
assert 'nouvelle_colonne' in df_transformed.columns, "La transformation n'a pas ajouté la colonne attendue"
Contribuer
Les contributions sont les bienvenues ! Veuillez soumettre un pull request pour les fonctionnalités ou les corrections de bugs.

Forkez le projet
Créez une branche pour votre fonctionnalité (git checkout -b fonctionnalite/AmazingFeature)
Commitez vos changements (git commit -m 'Ajout d'une fonctionnalité incroyable')
Poussez vers la branche (git push origin fonctionnalite/AmazingFeature)
Ouvrez un pull request
