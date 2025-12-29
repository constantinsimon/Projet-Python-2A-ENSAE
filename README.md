# Analyse des transactions immobilières en France

## Description du projet
Ce projet s'inscrit dans le cadre du cours de Python de 2ème année à l'ENSAE. Il propose une analyse des valeurs foncières en France, en mettant en relation les caractéristiques intrinsèques des biens (surface, type) avec leur contexte géographique, notamment la proximité aux gares SNCF.

L'objectif est d'expliquer et de prédire la valeur au mètre carré des logements à l'aide de techniques de visualisation de données (dataviz), de cartographie et de modélisation statistique (régressions linéaires, Random Forest).

## Structure du dépôt
- **Main notebook.ipynb** : Le notebook principal contenant l'ensemble de l'analyse, du nettoyage des données à la modélisation.
- **_Old/** : Dossier contenant les brouillons et scripts exploratoires (Scraping, tests géographiques).
- **gares-de-voyageurs.geojson** : Données géographiques des gares SNCF utilisées pour le calcul des distances.
- **requirements.txt** : Liste des dépendances Python nécessaires.

## Prérequis et Installation

### Environnement
Le projet nécessite Python 3.9 ou une version ultérieure. Il est recommandé d'utiliser un environnement virtuel.

### Installation des dépendances
Pour installer toutes les librairies nécessaires, exécutez la commande suivante dans votre terminal :

```bash
pip install -r requirements.txt
```

## Données
Pour que le projet fonctionne, vous devez ajouter le fichier de données DVF (Demandes de Valeurs Foncières) à la racine du projet.

1. **Fichier requis** : `ValeursFoncieres-2025-S1.csv`
2. **Source** : Données publiques DVF (Etalab).
3. **Instruction** : Placez ce fichier dans le même dossier que le `Main notebook.ipynb`.

## Auteurs
Projet réalisé par Yasser Mouaqqat & Constantin Simon dans le cadre de la scolarité en deuxième année à l'ENSAE Paris.