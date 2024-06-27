# Portofolio Data Science
Sélection de quelques projets dans le cadre de ma formation OpenClassrooms
---------
---------

&nbsp;
&nbsp;
&nbsp;
&nbsp;


## Implémentation d'un modèle de scoring
---------
Développement d’un modèle de détection du risque de faillite bancaire et déploiement d’une application de type dashboard interactif

*Classification binaire / Métrique custom / Light GBM / Dashboard / Streamlit*

![Dashboard](/assets/bank-loan-pic.png)

**Données** 
- 7 tables de données contenant des informations diverses sur plus de 300 000 clients ayant fait une ou plusieurs demandes de prêts  

**Démarche**
- Analyse exploratoire et sélection de variables pertinentes
- Définition d’une métrique d’évaluation spécifique aux coûts et pertes associés
- Optimisation et comparaison de modèles en utilisant des méthodes de blending et stacking
- Sélection du modéle Light GBM 
- Création et déploiement d’un dashboard interactif avec Streamlit

&nbsp;
&nbsp;
&nbsp;
&nbsp;
  
## Segmentation d'une base client
---------
Segmentation d’une base clients pour une entreprise de e-commerce et validation de la stabilité des clusters

*Clustering / Réduction de dimension / Interprétabilité / Sankey Diagram*

![clustering](/assets/clustering.png)

**Données**
- Base de données de plus de 90 000 clients. 8 fichiers de données concernant les achats, les paiements, les appréciations, etc.

**Démarche**
- Création de variables interprétables et actionnables en termes marketing
- Optimisation du nombre et de la taille des clusters avec les algorithmes k-Means et DB Scan
- Visualisation des clusters par réduction de dimensions (ACP, t-SNE)
- Interprétation des caractéristiques des clusters 
- Validation de la stabilité des clusters retenus sur une période de 6 mois

&nbsp;
&nbsp;
&nbsp;
&nbsp;

# Classification automatique d'articles
---------
Faisabilité du classement automatique des articles d’un site de vente en ligne sur la base de la description et de la photo d’un article
*NLP / Image processing / Transfer learning / Clustering*

![reconnaissance-articles-1](/assets/reconnaissance-articles-1.png)

**Données**
- Échantillon de 1050 articles répartis en 7 catégories avec nom, image et description

**Démarche**
- Extraction de features texte et images avec des modèles traditionnels
- Comparaison des performances avec celles de réseaux de neurones pré-entraînés
- Segmentation des articles en groupes aux caractéristiques similaires et comparaison avec les catégories réelles

![reconnaissance-articles-1](/assets/reconnaissance-articles-2.png)

**Résultats**
- Meilleurs résultats obtenus avec les algorithmes de Transfert Learning : 
  - Textes : ARI = 71% avec algorithme USE 
  - Images : ARI = 41% avec algorithme ResNet50

&nbsp;
&nbsp;
&nbsp;
&nbsp;

# Prédiction de consommation d'énergie
---------
Développement d'un modèle de prédictions des consommations d’énergie et d'émissions de gaz à effets de serre pour des bâtiments tertiaires
*Régression / Feature engineering / Hyper-paramètres / Métriques*

![energy-pred](/assets/energy-pred-1.png)

**Données**
- Caractéristiques, énergie et émissions de 3 400 bâtiments de la Ville de Seattle pour 2015 et 2016 (open data)

**Démarche**
- Analyse exploratoire
- Feature engineering : création de plusieurs variables pertinentes (catégorie de bâtiments, profil énergétique, ...)
- Comparaison et choix de métriques
- Comparaison de plusieurs modèles de régression (Lasso, ElasticNet, SVR RandomForrest, XGBoost)
- Optimisation des hyper-paramètres

**Résultats**
- Pertinence des variables crées, notamment le mix énergétique
- Sélection du modèle linéaire ElasticNet
  - R2 = 0,89 pour les consommations d’énergie
  - R2 = 0,81 pour les émissions de gaz à effet de serre
 
![energy-pred](/assets/energy-pred-2.png)

















