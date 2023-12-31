# Projet de Concaténation de Données et Affichage/Enregistrement de Graphiques
## Description
Ce projet a pour objectif de concaténer des données provenant de différentes sources (POC#1, POC#2, HW01), de les traiter et de les visualiser à l'aide de graphiques. Le script principal est écrit en Python pour assurer la flexibilité et la facilité d'utilisation.
Ce projet as été concu pour LTG-Tech

## Fonctionnalités
### Concaténation de Données 
Le script permet de fusionner des ensembles de données provenant de datalogger sous le nom (ex : TS_0003_02_2023_12_19_00144), facilitant ainsi l'analyse et la manipulation des données.

### Traitement de Données 
Des fonctions de traitement des données sont incluses pour nettoyer, transformer et préparer les données en vue de l'analyse.

### Visualisation de Graphiques 
Utilisation de bibliothèques graphiques telles que Matplotlib ou Seaborn pour générer des graphiques informatifs et visuellement attrayants.

### Enregistrement des Graphiques 
La possibilité d'enregistrer les graphiques générés dans des formats courants tels que PNG ou PDF.

## Prérequis
Python 3.x installé
Les dépendances peuvent être installées en utilisant pip install requirements

## Utilisation
Clonez le dépôt vers votre machine locale.

```bash
git clone [https://github.com/votre-utilisateur/votre-projet.git](https://github.com/jpthibault20/analyseHW1_universelle.git)
cd votre-projet
Installez les dépendances nécessaires.
```
pip install matplotlib

Arborescence à avoir pour l'utilisation ce script : 

```plaintext
Folder
  |  DATA
  |    |   TS_0003_02_2023_12_15_00050
  |    |   ...
  |    |   TS_0003_02_2023_12_15_00059
```

  
Suivez les instructions en commentaire du notebook pour fournir les chemins des fichiers de données et spécifier les options de visualisation.


## Exemples

Voici l'exemple d'un graphique généré :

![graph exemple output](img/output.png)

L'arborescence attendue : 
```plaintext
Folder
  |  DATA
  |    |   TS_0003_02_2023_12_15_00050
  |    |   ...
  |    |   TS_0003_02_2023_12_15_00059
  |  dataConcatenate
  |    |   concatene_02
  |    |   ...
  |    |   concatene_99
  |  graph
  |    |   Tension.png
  |    |   Tension moy.png
  |    |   ...
  |    |   Température.png
```



## Auteurs
JEANPIERRE Thibault

<img src="img/Logo.png" alt="Logo" width="100" height="100">


Licence
Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.
