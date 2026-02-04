# 🚀 Joël TERMONDJIAN

📍 Arles (13) | 📞 06 33 64 12 96 | ✉️ [joel.termondjian@hotmail.com](mailto:joel.termondjian@hotmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/joel-termondjian/) | 🐙 [GitHub](https://github.com/Djohell13)



## Data Analytics Engineer
Banque, Finance, Risque & Compliance

**20 ans d’expertise bancaire (Privée & Pro) mis au service de la Data.** 
Je conçois des pipelines automatisés et des predictive models pour transformer des flux de données brutes en leviers de décision stratégiques (Risque, KYC, Fraude).

**────────────────────────────────────────────────────────────────────────**

## 🛠 Compétences techniques

**Langages & Big Data :**
Python, SQL, Spark

**Data Analysis & Machine Learning :**
Pandas, NumPy, Scikit-learn, XGBoost
Exploratory Data Analysis (EDA), feature engineering, clustering,
Modèles supervisés et non supervisés,
Data visualization, analyse statistique.

**Data Engineering & MLOps :**
Conception de pipelines data, traitement de données à grande échelle,
MLflow (suivi d’expériences, versioning de modèles),
Streamlit (applications data interactives),
Docker (containerisation), Airflow (orchestration de pipelines),
Déploiement de modèles et services data.

**Infrastructure & Déploiement :**
API REST,
Hugging Face Spaces,
Cloud : AWS S3,
Environnements Big Data.

**Bases de données :**
MySQL (relationnel), MongoDB (NoSQL).

**Domaines métier :**
Finance, gestion du risque, conformité réglementaire, KYC.

**────────────────────────────────────────────────────────────────────────**

## 💼 Projets Data Phares

### 🧪 Modélisation de la durée de vie client & risque de défaut - R&D (en cours) FinTech

**Objectif métier :**  
Estimer le Time-to-Event (churn, défaut de paiement) afin d’améliorer le scoring de crédit et l’anticipation du risque client en environnement bancaire.

**Approche technique :**
* Survival Analysis avec XGBoost Cox Survival Model.
* Feature engineering orienté comportement client et historique financier.
* Évaluation des performances via métriques Time-to-Event.

**Résultat attendu :**  
* Déterminer un risque de défaillance avec un horizon temporel
* Projet de recherche et développement (Work in Progress) – résultats et déploiement en cours.

---

### 💵 Détection de fraude automatisée (FinTech)
🔗 [Voir le projet](https://huggingface.co/spaces/Djohell/Dashboard-fraud-detection)

**Objectif métier :** 
Mettre en place un système automatisé pour détecter les fraudes sur les paiements par carte bancaire et alerter les analystes.

**Approche technique :**
* **Ingénierie des données** : 
    * Analyse exploratoire (EDA) et nettoyage des flux transactionnels.
    * Feature engineering pour identifier des patterns comportementaux et la vélocité des transactions.
* **Machine Learning & MLOps** :
    * Modélisation prédictive avec **XGBoost**.
    * Suivi des expériences et des performances via **MLflow**.
* **Déploiement & Automatisation** :
    * Interface interactive via **Streamlit**.
    * **Pipeline d'alerte** : Envoi automatisé d'un mail quotidien via **Airflow** listant les fraudes détectées à J-1.
      
**Résultat** :
* Analyse complète des transactions frauduleuses à J-1 par envoi de mail
* Tableau de bord opérationnel pour les analystes avec données intégrées toutes les semaines


---

### 🔥 Prévision du risque incendie - Survival Analysis (SDIS)
🔗 [Voir le projet](https://projet-feux.streamlit.app/)

**Objectif métier :**  
Anticiper le risque incendie en temps réel. Une approche directement transposable en banque au **Scoring de Crédit** et au **Risque de Défaut**.

**Approche technique :**
   * **Data Engineering** : Pipeline automatisé d’intégration de données météo en temps réel via API REST.
   * **Modélisation avancée** : Utilisation du modèle XGBoost Cox Survival Model (Survival Analysis) pour prédire le Time-to-Event.
   * **Déploiement** : Application Streamlit et API REST orientée aide à la décision.

**Résultat :**
   * Modèle avec **C-index à 0.809**
   * Mise en place de 5 time to event
   * Dashboard de visualisation du risque de 7 à 180 jours

---

### 🚗 Étude d’impact & déploiement - Get Around
🔗 [Voir le projet](https://huggingface.co/spaces/Djohell/get_around_dashboard)


**Objectif métier :**  
Réduction des frictions opérationnelles et optimisation des revenus. Une approche de Yield Management et de Fiabilisation du Service (réduction des churns liés aux retards).

**Approche technique :**
   * **Analyse** : Simulation d'impact financier (Trade-off) entre l'instauration d'un délai de sécurité (Buffer) et la perte de revenus potentiels.
   * **Modélisation** : Régression pour la prédiction de prix (Pricing Engine) basée sur les caractéristiques des véhicules.
   * **Déploiement** : Architecture hybride avec une API REST (FastAPI) pour le service de prédiction et un Dashboard Streamlit pour le pilotage métier.

**Résultat :**
   * Modèle avec **R2 à 0.771**
   * Optimisation Ops : Identification du seuil de rentabilité optimal pour le délai de sécurité entre deux locations.
   * Performance ML : Modèle de pricing performant déployé via endpoint API.
   * Outil Décisionnel : Dashboard interactif permettant de visualiser le volume de réservations sauvées vs chiffre d'affaires impacté.
     
---

### 🚕 Clustering de trajets - UBER New York
🔗 [Voir le projet](https://huggingface.co/spaces/Djohell/Clustering_UBER)

**Objectif métier :** Optimisation de la disponibilité de la flotte par l'identification de zones de forte demande (Hotspots).

**Approche technique :** 
   * **Apprentissage non supervisé** : Algorithmes KMeans & DBSCAN pour le clustering spatial des coordonnées GPS.
   * **Data Viz** : Cartographie interactive pour visualiser les zones de tension à différentes heures de la journée.
   * **Déploiement** : Dashboard interactif permettant de visualiser les différents clusters.

**Résultat :** 
   * Identification de 8 segments d'usage critiques permettant une meilleure répartition prédictive des chauffeurs.

**────────────────────────────────────────────────────────────────────────**
##🌍 Engagement & Impact Social

### 🎗️ 180 Jours contre le Lymphome — Fondateur & Analyste Engagement  
🔗 [Voir le projet](https://www.facebook.com/180jourscontrelelymphome/)

**Objectif :** 
   * Sensibiliser au parcours de soin et soutenir la communauté des patients à travers une plateforme caritative créée en période de crise sanitaire (Covid).

**Approche technique & humaine :**

   * **Communication Data-Driven** : Analyse de l'engagement des publications pour optimiser la visibilité des messages de prévention.
   * **Gestion de communauté** : Modération et interaction avec une audience touchée par la pathologie.
   * **Storytelling** : Vulgarisation du parcours de soin complexe pour le rendre accessible au plus grand nombre.

**Impact & Résultats** : 
   * Création d'un espace d'échange actif pour les patients et leurs proches.

**Lien métier** : Développement d'une expertise terrain sur le parcours "Patient", complétant ma maîtrise technique des données de santé/banque par une vision éthique et humaine.

**────────────────────────────────────────────────────────────────────────**

## 💼 Expérience professionnelle (résumé)

### Data Analytics Engineer - Freelance | 2026

---

### La Banque Postale | 2006 - 2025
**Responsable Clientèle Professionnelle / Conseiller Financier**

* **Gestion du Risque & Data Analysis** : Analyse de données financières, suivi d’indicateurs chiffrés (KPI), aide à la prise de décision et conformité KYC.
* **Expertise Métier Banque / Finance** : Forte compréhension des enjeux réglementaires, risques clients et performance business.
* **Vulgarisation & Data Storytelling** : Capacité à traduire des données complexes et modèles analytiques en recommandations claires pour les clients et décideurs.


**────────────────────────────────────────────────────────────────────────**

## 🎓 Formation

**Master 2 Architecte en Intelligence Artificielle**  
Jedha Bootcamp · 2025

**Master 1 Concepteur Développeur Science des Données**  
Jedha Bootcamp · 2025

**BTS Banque**  
Formaposte · 2006

**DUT Techniques de Commercialisation**  
IUT Aix-en-Provence · 2004

**────────────────────────────────────────────────────────────────────────**

## 🎯 Infos complémentaires
* **Permis** : A et B
* **Langues** : Anglais (Niveau B2)
* **Passions** : Karaté, Jeux Vidéo, Lecture.
