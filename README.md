Analyse des films Disney
Ce projet explore les recettes des films Disney à l’aide de Pandas, Seaborn et scikit‑learn, exécuté sur Google Colab.

 Données
Fichier utilisé : disney_movies_total_gross.csv

La colonne release_date est convertie en type date (parse_dates).

 Étapes principales
Chargement des données : lecture du CSV et conversion des dates.

Exploration : aperçu des colonnes et types.

Classement : top 10 des films les plus rémunérants.

Regroupement par genre et année : moyenne des recettes ajustées par genre/année.

Visualisation : courbes comparatives par genre.

Encodage des genres : transformation en variables binaires (dummy variables).

Régression linéaire : estimation de l’impact des genres sur les recettes ajustées.

 Résultats
L’intercept ≈ 103 M$ → revenu moyen du genre de référence.

Le coefficient du premier genre ≈ 87 M$ → effet du genre Adventure (ou premier encodé) par rapport au genre de base.

Exemple de sortie :

python
(102921757.36, 87475654.71)

 Technologies
Python : pandas, seaborn, scikit‑learn

Google Colab : exécution du notebook

▶️ Utilisation
Cloner le dépôt :

bash
git clone https://github.com/<karimcsss>/disney-analysis.git
Ouvrir le notebook dans Google Colab.

Exécuter les cellules pas à pas pour reproduire l’analyse.