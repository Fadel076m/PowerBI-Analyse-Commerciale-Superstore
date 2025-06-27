# PowerBI-Analyse-Commerciale-Superstore
🎯 Objectif général Créer un tableau de bord de gestion commerciale pour une entreprise de distribution fictive, permettant d’analyser les performances de vente, les produits les plus rentables, les clients stratégiques et les régions à fort potentiel.


🛠️ Étapes et Questions Progressives
🧩 Étape 1 – Préparation des données
1- Importer le fichier train.csv dans Power BI
Question : Que remarques-tu sur les types de données (dates, numériques, textes) ?
2- Convertir les colonnes Order Date et Ship Date en format "Date"
Pourquoi est-ce important pour l’analyse temporelle ?
3- Créer une nouvelle colonne : "Délai de livraison (jours)"
Question : Quels produits ou régions ont les délais les plus longs ?

📊 Étape 2 – Visualisations de base
1- Créer une carte des ventes par région et par État
Utiliser les champs : State, Region, Sales
2- Créer un graphique à barres empilées : Ventes par Catégorie et Sous-Catégorie
Astuce : utiliser Category en axe, Sub-Category en légende et Sales en valeur.
3- Créer un graphique temporel : évolution des ventes par mois
Ajouter une table de dates ou extraire le mois/année de Order Date.

📈 Étape 3 – Indicateurs clés (KPIs)
1- Créer des mesures DAX personnalisées :
- Chiffre d’affaires total
- Moyenne des ventes
- Nombre de commandes
- Croissance par rapport au mois précédent
2- Créer des cartes d’indicateurs (cards) pour afficher ces KPIs en haut du tableau de bord

🎯 Étape 4 – Analyse clients et produits
1- Créer un graphique des 10 clients les plus rentables
Utiliser Customer Name et Sales
2- Créer une table interactive : Produits, ventes, délai de livraison
Objectif : identifier les produits performants malgré un long délai de livraison

🎛️ Étape 5 – Interactivité
1- Ajouter des slicers (filtres interactifs) :
- Segment (Corporate, Consumer, Home Office)
- Date (par année ou mois)
- Catégorie de produit
- Région
2- Créer des drill-downs (exploration par clics)
Exemple : De la catégorie → à la sous-catégorie → au produit

🧠 Étape 6 – Analyse approfondie
1- Créer une mesure de part de marché interne par région :
2- Créer une alerte visuelle sur les régions à faible performance (en rouge si en dessous d’un seuil)

🖼️ Étape 7 – Finalisation du dashboard
1- Créer une page de rapport propre, bien structurée : Titre, sous-titres, couleurs harmonisées
2- Boutons de navigation ou filtres bien visibles
3- Publier ton rapport sur le service Power BI (si tu es connecté à un compte Microsoft)
