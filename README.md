# Diagnostic de systèmes hydrogène PEM – indicateurs, ACP et KNN

Module **Diagnostic des systèmes hydrogène** du Master 2 Énergie (ENERGY-Lab, Université de La Réunion).

## Objectif
À partir de signaux bruts de systèmes PEM, construire une chaîne de diagnostic complète :
extraction d'indicateurs, réduction de dimension, puis classification de l'état de fonctionnement.

## Contenu
| Fichier | Description |
|---|---|
| `Session_2_indicateurs.ipynb` | Indicateurs statistiques sur `Fichier_Signal_Brut.mat` : écart-type (SD), RMS, facteur de crête (CF), skewness (SK), kurtosis (KU), facteur de forme (SF) |
| `Session_5_ACP_KNN.ipynb` | Réduction de dimension par **ACP** puis classification **KNN** |

## Outils
Python · NumPy · SciPy (lecture des fichiers `.mat`) · scikit-learn · Matplotlib · Google Colab

## Lancer
```bash
pip install numpy scipy scikit-learn matplotlib jupyter
jupyter notebook
```
Les données de signaux fournies en cours ne sont pas publiées.

## Auteur
Nicolas NOYON – nicolasnoyon.pro@gmail.com
