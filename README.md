# Analyse de la Qualité des Soudures par Machine Learning

Ce projet a lieu dans le cadre du cours d'Apprentissage Automatique de 3ème année. 

Il s'agit d'employer une méthodologie rigoureuse pour manipuler un dataset hétérogène, et d'utiliser des techniques d'apprentissage non supervisé et semi-supervisé pour analyser et prédire une qualité de soudures. 
La base de données `MAP_DATA_WELD` provient de la *Phase Transformations Group*, de l’Université de Cambridge, et a été compilée à partir de publications scientifiques. 
Elle fournit des informations sur la composition chimique et les propriétés mécaniques des métaux de soudure, ainsi que sur des mesures de résitance des matériaux.

Le langage de programmation utilisé sera `Python` à travers des notebooks `Jupyter` et la majorité du Machine Learning s'appuira sur la bibliothèque `sklearn`.

Dans ce répertoire Github, vous trouverez :
- 5 notebooks interactifs `Jupyter`
- une copie de la base de données `MAP_DATA_WELD`
- une version `pdf` du rapport de projet
- une version `pdf` des diapositives de soutenance

## Objectifs du Projet

L'objectif principal de ce projet est de déterminer la qualité des soudures à partir de données industrielles en appliquant diverses techniques de Machine Learning :

- **Apprentissage supervisé** pour des tâches de classification et de régression.
- **Apprentissage semi-supervisé** pour combiner étiquettes partiellement disponibles et apprentissage non supervisé.

## Structure du Projet

Le projet est structuré en 5 notebooks distincts :

1. **Exploration et compréhension de la base de données**  
   Ce notebook explore la base de données, effectue des analyses statistiques, des visualisations pour comprendre la structure et les corrélations entre les variables.

2. **Préprocessing des données et constitution d'une variable de score pour la qualité de soudure**  
   Ce notebook applique des techniques de preprocessing pour nettoyer et préparer les données. Une variable de score est construite pour évaluer la qualité des soudures.

3. **Application de techniques d'apprentissage supervisé pour la régression**  
   Des algorithmes de régression supervisée sont appliquées pour prédire la qualité des soudures en fonction des variables explicatives.

4. **Application de techniques d'apprentissage supervisé pour la classification**  
   Des algorithmes de classification supervisée sont utilisés pour classifier la qualité des soudures selon des catégories définies.

5. **Application de techniques d'apprentissage semi-supervisé**  
   Utilisation de modèles semi-supervisés pour apprendre à partir de données partiellement étiquetées, combinant apprentissage non supervisé et supervisé.

## Base de Données

La base de données utilisée pour ce projet provient de la source suivante :

**[MAP_DATA_WELD](https://www.phase-trans.msm.cam.ac.uk/map/data/materials/welddb-b.html)**

### Installation et utilisation

1. Clonez ce dépôt sur votre machine locale :

   ```bash
   git clone https://github.com/votre-repo/soudures-ml.git
   cd soudures-ml
   ```

2. Le projet utilise plusieurs bibliothèques Python, notamment `scikit-learn`, `pandas`, `numpy`, et `matplotlib` à installer :

   ```bash
   pip install -r requirements.txt
   ```

3. Utilisez les notebooks `Jupyter` dans l'odre indiqué par leur préfixe.

### Auteurs

- Marius NADALIN
- Aymane LOTFI
- Paul-Ambroise LEROY
- Élian MANGIN
