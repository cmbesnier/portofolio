# Claire-Marie BESNIER

Ingénieure avec 8 ans d’expérience dans l’énergie et l’aménagement urbain, j’ai ajouté une brique data science à mon profil en 2021. Curieuse, méthodique et organisée, j’aime me confronter à des problématiques métier variées, dans un contexte français ou international.

> [LinkedIn](https://www.linkedin.com/in/cmbesnier/)


# Projets Data Science
Sélection de quelques projets dans le cadre de ma formation OpenClassrooms

&nbsp;
&nbsp;
&nbsp;
&nbsp;


## Implémentation d'un modèle de scoring
---------
Développement d’un modèle de détection du risque de faillite bancaire et déploiement d’une application de type dashboard interactif

*Classification binaire / Métrique spécifique / Light GBM / Dashboard / Streamlit*

![Dashboard](/assets/bankloan-dashboard.png)

**Données** 
- 7 tables de données contenant des informations diverses sur plus de 300 000 clients ayant fait une ou plusieurs demandes de prêts  

**Démarche**
- Analyse exploratoire et sélection de variables pertinentes
- Définition d’une métrique d’évaluation spécifique aux coûts et pertes associés
- Test de plusieurs méthodes pour pallier aux deséquilibres des classes
- Optimisation et comparaison de modèles en utilisant des méthodes de blending et stacking

**Résultats**
- Sélection du modéle Light GBM
- Création et déploiement d’un [dashboard interactif](https://cmbesnier-credit-dashboard-main-wndjuj.streamlit.app/) avec prédiction live en utilisant Streamlit

[Note méthodologique](https://github.com/cmbesnier/credit-dashboard/blob/main/P7-03-note%20me%CC%81thodologique.pdf)

[Repo Github](https://github.com/cmbesnier/credit-dashboard/)

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
- Test de la stabilité des clusters avec différents indicateurs

**Résultats**
- Choix de retenir 5 clusters (algorithme k-Means)
- Interprétation des caractéristiques des clusters en termes marketing
- Validation de la stabilité des clusters retenus sur une période de 6 mois et visualisation avec diagramme de Sankey

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
- Meilleures performances obtenues avec le modèle linéaire ElasticNet
 
![energy-pred](/assets/energy-pred-2.png)

















