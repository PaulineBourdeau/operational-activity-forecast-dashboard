# operational-activity-forecast-dashboard
Decision-support dashboard for workload forecasting and workforce capacity planning developed in Excel.

<img width="1622" height="970" alt="6f7b97a3-cc0c-45f7-b4d0-35799c2c1417" src="https://github.com/user-attachments/assets/28f5fe5d-a12e-4a94-9354-fc83d25551f2" />



# PROJET

Ce projet a été développé afin de faciliter la prise de décision opérationnelle en prévisionnant les volumes d'activité et en estimant les besoins en personnel à partir de données historiques.
Au départ, l'objectif était simplement de calculer le nombre annuel moyen de dossiers traités.
Au cours de l'analyse, il est apparu clairement que cette information seule était insuffisante pour étayer la planification opérationnelle.
Le projet a donc évolué pour devenir un tableau de bord complet d'aide à la décision, capable de suivre l'activité, de prévoir la charge de travail et d'estimer les besoins en personnel.

# PROBLEMATIQUES

Les responsables opérationnels devaient répondre à plusieurs questions :
- Comment l'activité va-t-elle évoluer au cours des prochains mois ?
- Quand les pics de charge de travail sont-ils prévus ?
- Combien de collaborateurs sont nécessaires pour traiter la charge de travail prévue ?
- Quelles sont les périodes les plus propices pour prendre des congés annuels ?
- Quel est l'impact de l'augmentation des certifications électroniques sur la charge de travail ?

# SOLUTIONS PROPOSEES

- suivi historique de l'activité
- indicateurs clés de performance (KPI) mensuels et annuels
- prévisions de charge de travail
- modèle d'estimation des effectifs
- tableau de bord opérationnel
- indicateurs d'aide à la décision

# MODÈLE D’ESTIMATION DES BESOINS EN RESSOURCES

Les dossiers ont été regroupés en grandes catégories selon leur complexité. Pour chaque catégorie, un temps moyen de traitement a été défini collectivement par l’équipe afin de limiter les biais liés aux performances individuelles.

Le calcul de charge repose sur la formule :

Charge mensuelle (heures) =
Σ (Volume de dossiers × Temps moyen par catégorie)
La charge totale est ensuite convertie en besoin théorique en équivalents temps plein (ETP) :
ETP nécessaires =
Charge totale / Temps de travail mensuel disponible
Ce modèle permet d’anticiper les pics d’activité, d’estimer les besoins en effectifs et de faciliter la planification des congés et du télétravail.

# METHODOLOGIE

1. Collecte des données
2. Nettoyage des données
3. Consolidation des données
4. Calcul des indicateurs clés de performance (KPI)
5. Estimation de la charge de travail
6. Élaboration de prévisions
7. Création de tableaux de bord

# PRESPECTIVE 

Amélioration du Dashboard avec PowerBI
Automatisation via Python
Utilisation des bases SQL
