# Notre-Fonds-ESG

Bienvenue dans l'application "Notre Fonds ESG" ! Ce projet a été conçu pour permettre aux utilisateurs de composer leur propre portefeuille d’investissement en fonction de critères sectoriels tout en optimisant les performances ESG (Environnement, Social, Gouvernance).

## 📁 Comment utiliser l’application
1) Charger le fichier Excel du fonds (format .xlsm) via l’interface Streamlit.
2) Nous procédons tout d'abord à une nalyse complète de notre fond
3) Nous réalisions ensuite une analyse plus poussée sur le pire secteur (pire score ESG) et sur le meilleure secteur de notre fonds.
4) Ensuite on demande à l'utilisateur de personnaliser son fond en utilisant les données du fonds initial pour qu'il soit plus adapté aux critères extra financiers
5) L’application calcule automatiquement les scores ESG moyens du portefeuille personnalisé (on peut meme personnalisé les deux pires secteurs si on le veut dans ce portefeuille en choisissant les entreprises)
6) Comparaison visuelle avec les scores du portefeuille initial.

## Technologies utilisées
- Python (Pandas, NumPy)

- Streamlit

- Yahoo Finance API (yahooquery, yfinance)

- Visualisation : Plotly, Seaborn, Matplotlib

- Git & GitHub pour le versioning

Projet réalisé par Agathe Plouvier, Anna Bennaim, Arwen Scharr

Lien pour accéder Streamlit Community Cloud: https://analyse-fonds-esg-m1eif-finance-durable.streamlit.app/
