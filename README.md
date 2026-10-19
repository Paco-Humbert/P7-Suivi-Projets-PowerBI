# Pilotage de projets Sanitoral avec Power BI

**Projet 7 — Parcours Business Intelligence Analyst | OpenClassrooms**

## Présentation

Ce projet pédagogique consiste à construire un tableau de bord de suivi des projets IT et Marketing de Sanitoral. Le rapport compare les coûts, les durées et les livrables prévus et réels pour aider les responsables à repérer les dérives et à prioriser les actions correctives.

## Objectifs métier

- Donner à la direction générale une vue globale du portefeuille de projets.
- Permettre aux directeurs régionaux et de pays de suivre leur périmètre.
- Identifier les projets présentant des écarts défavorables sur les coûts, les délais ou les livrables.
- Analyser les alertes par projet, phase, type de projet, pays et région.
- Faciliter les arbitrages et le suivi budgétaire.

Le rapport documente un seuil d'alerte de **15 %** pour les dérives défavorables. Les indicateurs de coût, durée et livrables restent distincts, avec une synthèse des projets en alerte globale.

## Technologies et compétences

- Power BI Desktop pour le modèle et les pages du rapport.
- Power Query pour préparer les données.
- DAX pour les indicateurs de suivi et d'alerte.
- Excel comme source de données.
- Cadrage des besoins avec un Product Strategy Canvas.

## Fichiers du dépôt

| Fichier | Rôle |
|---|---|
| [Rapport Power BI](Humbert_Paco_1_Sanitoral_062026.pbix) | Tableau de bord interactif au format PBIX |
| [Données sources Excel](Donne%CC%81es%2BSanitoral%2B-%2BTest%2BMentor.xlsx) | Fichier Sanitoral fourni avec le projet |
| [Product Strategy Canvas](Mod%C3%A8le_product_strategie.docx) | Cadrage des objectifs et besoins utilisateurs |
| [Vue du modèle de données](vue_mod%C3%A8le.jpg) | Image des tables et relations du modèle |

Les quatre fichiers d'origine sont conservés à l'identique, sans modification du rapport, du document Word, de l'image ou des données. Seuls ce README et le `.gitignore` sont ajoutés pour préparer le dépôt.

## Pages du rapport

| Page présente dans le PBIX | Contenu |
|---|---|
| Vue globale V2 | Indicateurs de portefeuille, coûts prévus et réels, alertes et filtres géographiques |
| Détails des projets | Tableau de détail des projets et phases |
| Planning Gantt | Visualisation du calendrier des projets |
| Analyse des alertes | Répartition des alertes, nature des dérives et analyse des écarts |
| Méthodologie | Préparation, modèle de données et procédure d'actualisation |
| Mise à jour | Repères visuels relatifs à l'actualisation |
| Proposition axe stratégique | Proposition de priorisation du pilotage budgétaire |
| Q&A | Questions métier et indications des pages permettant d'y répondre |

La page Q&A est une page de questions rédigées et de repères de navigation.

## Indicateurs suivis

- Nombre total de projets.
- Nombre et taux de projets en alerte globale.
- Nombre de projets en alerte coût, durée ou livrables.
- Coûts prévus et réels et écarts de coût en pourcentage.
- Écarts de durée et détail des projets et phases.

Les filtres par région, pays et type de projet permettent de préciser le périmètre d'analyse.

## Modèle de données

Le modèle relie les prévisions et les réalisations autour des projets et de leurs phases. La clé `Project_Phase_ID` permet d'associer les données de chaque phase. Les tables de coûts, durées et livrables sont complétées par des informations sur les pays, les régions et les types de projets.

![Vue du modèle de données fournie avec le projet](vue_mod%C3%A8le.jpg)

## Ouvrir le projet

1. Télécharger le dépôt complet et extraire les fichiers.
2. Ouvrir `Humbert_Paco_1_Sanitoral_062026.pbix` avec Power BI Desktop sous Windows.
3. Parcourir les pages et utiliser les filtres pour explorer les indicateurs.
4. Pour une actualisation, adapter si nécessaire le chemin de la source Excel à son emplacement local, puis actualiser les données.
5. Vérifier les indicateurs et les alertes après actualisation.

Le PBIX nécessite Power BI Desktop pour être exploré. GitHub permet de télécharger le fichier et de consulter l'image du modèle, mais n'affiche pas le tableau de bord interactif.

Le fichier d'origine contient le composant Gantt utilisé dans le rapport. Il est conservé tel quel dans cette livraison.

## Portée de cette publication

Cette préparation concerne l'organisation du dépôt et sa documentation. Le contenu du PBIX a été inspecté pour identifier les pages et les indicateurs à décrire. Le rapport n'a pas été ouvert ni actualisé dans Power BI Desktop lors de cette préparation ; cette publication ne constitue donc pas une nouvelle validation des calculs ou du fonctionnement des visuels.

## Auteur

Paco Humbert — Projet pédagogique réalisé dans le cadre de la formation Business Intelligence Analyst d'OpenClassrooms.
