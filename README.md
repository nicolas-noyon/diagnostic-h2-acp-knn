# Diagnostic de systèmes hydrogène PEM – indicateurs, ACP et KNN

Module **Diagnostic des systèmes hydrogène** du Master 2 Énergie (ENERGY-Lab, Université de La Réunion).

## Objectif
À partir de signaux bruts de systèmes PEM, construire une chaîne de diagnostic complète :
extraction d'indicateurs, réduction de dimension, puis classification de l'état de fonctionnement.

## Contenu
| Fichier | Description |
|---|---|
| [`Session_4_KNN.ipynb`](Session_4_KNN.ipynb) | Classer des états de fonctionnement : extraction des critères statistiques (RMS, facteur de crête, kurtosis…), apprentissage **KNN**, matrices de confusion et taux par classe |
| [`Session_7_ondelettes_ACP_KNN.ipynb`](Session_7_ondelettes_ACP_KNN.ipynb) | Chaîne complète : décomposition en **ondelettes** (PyWavelets), réduction de dimension par **ACP**, classification **KNN** |
| [`rapport_Session_7.pdf`](rapport_Session_7.pdf) | Rapport de la session 7 |

## Outils
Python · NumPy · pandas · SciPy · PyWavelets · scikit-learn · Matplotlib · Google Colab

## Lancer
```bash
pip install numpy pandas scipy PyWavelets scikit-learn matplotlib jupyter
jupyter notebook
```
Les données de signaux fournies en cours ne sont pas publiées.

## Auteur
Nicolas NOYON – nicolasnoyon.pro@gmail.com
