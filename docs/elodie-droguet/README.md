# Brew Beans — Prénom Nom
## Objectif
Corriger BB-041 : 40 à 45 EUR.
## Données
43 transactions · CA : 453.20 EUR.
## Exécution
Prérequis : activer l’environnement Python du J1 avec pandas installé.
Depuis la racine du dépôt :
```bash
python scripts/prenom-nom/preparer_ventes.py
```
## Vérifications
43 transactions et 453.20 EUR.
Contrôle BB-041 : montant corrigé à 45 EUR.
## Ressource
[pandas](https://pandas.pydata.org/docs/)