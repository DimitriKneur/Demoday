# Demoday

# Projet Final

Projet final de la formation Data analyst à JEDHA BOOTCAMP

Présentation PPT : Vous pouvez accéder à la présentation (rajouter le lien)

Lien vers GitHub

## Titre du Projet

Préparer le monde de demain avec les tendences démographiques d'aujourd'hui.

### Introduction

Ce projet examine l'évolution démographique mondiale de 2000 à 2021, en mettant l'accent sur les variations des taux de natalité et de mortalité. L'importance de ces données réside dans leur capacité à éclairer les tendances sociétales et à guider la planification à long terme. L'objectif de l'analyse approfondie est d'identifier les facteurs clés sous-jacents à ces changements, fournissant ainsi des perspectives utiles pour les décideurs et les acteurs de la santé publique. En anticipant les défis liés à une population en mutation, l'étude vise à contribuer à des décisions stratégiques éclairées, favorisant un avenir plus équitable et durable sur le plan social, économique et environnemental.

### Données Utilisées

Les données utilisées proviennent de la World Bank Data, une source fiable de données socio-économiques mondiales. Dix-sept bases de données distinctes, couvrant divers aspects de la démographie mondiale, ont été collectées et soigneusement consolidées pour former une base exhaustive. Cette approche garantit une analyse robuste et de qualité de l'évolution de la population mondiale de 2000 à 2021.
Voici le lien vers la source des données: https://databank.worldbank.org/source/world-development-indicators#

Le tableau ci-dessous montre la significationde chaque colonne de notre dataset:

|     Colonnes                                  |     Significations                                                                                                                                                                                                                                                                                                                                                                                                              |
|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     Country Name                              |     Indique le   nom du pays auquel les données démographiques se rapportent. Chaque entrée   dans cette colonne identifie de manière unique le pays associé aux données de   population.                                                                                                                                                                                                                                       |
|     Country Code                              |     Codes géographiques alphabétiques ou numériques courts développés pour   représenter les pays et les zones dépendantes, utilisés dans le traitement   des données et les communications.                                                                                                                                                                                                                                    |
|     Year                                      |     Fait   référence à l'année correspondante pour laquelle les données démographiques   ont été enregistrées.                                                                                                                                                                                                                                                                                                                  |
|     Birth Rate                                |     Le taux brut   de natalité indique le nombre de naissances vivantes survenues au cours de   l'année, pour 1 000 habitants estimés à la mi-année.                                                                                                                                                                                                                                                                            |
|     Population_male                           |     La   population masculine est basée sur la définition de facto de la population,   qui compte tous les résidents masculins indépendamment de leur statut   juridique ou de leur citoyenneté.                                                                                                                                                                                                                                |
|     Population_female                         |     La   population féminine est basée sur la définition de facto de la population,   qui compte toutes les femmes résidentes indépendamment de leur statut   juridique ou de leur citoyenneté.                                                                                                                                                                                                                                 |
|     Population_total                          |     La   population totale est basée sur la définition de facto de la population, qui   compte tous les résidents indépendamment de leur statut juridique ou de leur   citoyenneté. Les valeurs indiquées sont des estimations en milieu d'année.                                                                                                                                                                               |
|     Median_age                                |     Correspond à   l'âge qui divise une population en deux groupes numériquement égaux,   c'est-à-dire que la moitié des personnes sont plus jeunes que cet âge et   l'autre moitié plus âgées. Il s'agit d'un indice unique qui résume la   répartition par âge d'une population.                                                                                                                                              |
|     Human   Development Index                 |     L'indice de   développement humain (IDH) est une mesure synthétique des dimensions clés du   développement humain : une vie longue et saine, une bonne éducation et un   niveau de vie décent. Des valeurs plus élevées indiquent un développement   humain plus important.                                                                                                                                                 |
|                                               |                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|     PM2.5_pollution                           |     Représente   le niveau moyen d'exposition de la population d'un pays aux particules en   suspension d'un diamètre aérodynamique inférieur à 2,5 microns. Ces   particules, capables de pénétrer profondément dans les voies respiratoires,   peuvent causer des dommages importants à la santé.                                                                                                                             |
|     Urban   population rate                   |     La   population urbaine se réfère aux personnes vivant dans les zones urbaines   telles que définies par les bureaux nationaux de statistiques. Les données   sont collectées et lissées par la Division de la population des Nations   unies.                                                                                                                                                                              |
|     Death_Rate                                |     Le taux de mortalité est le rapport entre le nombre annuel de décès et la   population totale moyenne sur une période et dans un territoire donné. Cette   mesure statistique est notamment utilisée en démographie humaine,                                                                                                                                                                                                |
|     Population_15_64_rate                     |     Population   âgée de 15 à 64 ans en pourcentage de la population totale.                                                                                                                                                                                                                                                                                                                                                    |
|     Population_65_above                       |     Population   âgée de 65 ans et plus en pourcentage de la population totale.                                                                                                                                                                                                                                                                                                                                                 |
|     Cotisation   sociale                      |     Souvent   appelées charges sociales, sont des prélèvements assis sur les salaires. Les   cotisations font partie de la répartition opérée sur la richesse nationale   marchande créée au cours de l'année, ou PIB. Elles sont calculées sur la base   des salaires super-brut.                                                                                                                                              |
|     Life_expectancy_in_years                  |     L'espérance   de vie à la naissance indique le nombre d'années que vivrait un nouveau-né si   les taux de mortalité prévalant au moment de sa naissance restaient les mêmes   tout au long de sa vie.                                                                                                                                                                                                                       |
|     gov_health_exp_as_perc_of_gdp             |     Niveau des   dépenses courantes de santé exprimé en pourcentage du PIB. Les estimations   des dépenses courantes de santé comprennent les biens et services de santé   consommés chaque année. Cet indicateur n'inclut pas les dépenses de santé en   capital telles que les bâtiments, les machines, les technologies de   l'information et les stocks de vaccins pour les urgences ou les épidémies.                      |
|     undernourished_population_rate            |     La   prévalence de la sous-alimentation est le pourcentage de la population dont   la consommation alimentaire habituelle est insuffisante pour fournir les   niveaux d'énergie alimentaire nécessaires au maintien d'une vie normale,   active et saine.                                                                                                                                                                   |
|     population_rate_with_water_access         |     Représente   le pourcentage de personnes utilisant des services d'eau de base, y compris   ceux gérés en toute sécurité. Les services d'eau potable de base incluent   l'accès à une source améliorée, avec une limite de temps de collecte de 30   minutes pour un aller-retour.                                                                                                                                           |
|     mortality_cvd_crd_cancer_diabete_30_70    |     Représente   le pourcentage de personnes âgées de 30 ans qui décéderaient avant leur 70e   anniversaire en raison de maladies cardiovasculaires, de cancer, de diabète   ou de maladies respiratoires chroniques. Cette estimation se base sur les   taux de mortalité actuels à tous les âges et suppose que ces personnes ne   décéderaient pas d'autres causes de décès telles que les traumatismes ou le   VIH/sida.    |
|     uhc_service_coverage                      |     Couverture   des services de santé essentiels (définie comme la couverture moyenne des   services essentiels sur la base d'interventions traceurs comprenant la santé   reproductive, maternelle, néonatale et infantile, les maladies infectieuses,   les maladies non transmissibles et la capacité et l'accès aux services, parmi   la population générale et la population la plus défavorisée).                        |
|     population_growth_rate                    |     Le taux de   croissance de la population compare la variation annuelle moyenne en   pourcentage des populations, résultant d'un excédent (ou d'un déficit) des   naissances par rapport aux décès et du solde des migrants entrant et sortant   d'un pays. Le taux peut être positif ou négatif.                                                                                                                            |
|     Female_employment_rate                    |     Le taux d'emploi des femmes est la proportion de femmes   disposant d'un emploi parmi   celles en âge de travailler (15 à 64 ans).                                                                                                                                                                                                                                                                                          |
|     GDP per   Capita                          |     Le PIB par   habitant est le produit intérieur brut divisé par la population en milieu   d'année. Le PIB est la somme de la valeur brute ajoutée par tous les   producteurs résidents de l'économie, augmentée des taxes sur les produits et   diminuée des subventions non incluses dans la valeur des produits.                                                                                                           |
|     female_population_rate_15to44             |     Population   féminine âgée de 15 à 44 ans en pourcentage de la population féminine totale.                                                                                                                                                                                                                                                                                                                                  |
|     Continent   Name                          |     Spécifie le   continent auquel chaque pays appartient. Elle permet de regrouper les données   par continent, facilitant ainsi des analyses régionales.                                                                                                                                                                                                                                                                      |

### Méthodologie

Les ensembles de données de la World Bank ont été importés dans Python via Pandas, puis traités individuellement pour uniformiser le format en vue d'une fusion. Le processus de fusion a créé une base de données complète pour notre analyse. Nous avons nettoyé la base en supprimant les colonnes superflues, remplaçant les valeurs manquantes par des données provenant d'Internet avec Pandas, et optimisé les types de données pour assurer une précision maximale. Cette approche méthodique garantit la qualité et la cohérence de notre ensemble de données final, formant une base solide pour une analyse approfondie de l'évolution de la population mondiale de 2000 à 2021.

### Analyse et Modélisation avec Dataiku

Pour approfondir notre compréhension des données, nous avons utilisé la plateforme d'analyse avancée Dataiku. Nous avons créé deux matrices de corrélation pour identifier les caractéristiques les plus influentes sur les taux de natalité et de mortalité. L'analyse de ces matrices a révélé des tendances significatives et des corrélations pertinentes entre les indicateurs. Ensuite, nous avons construit des modèles de régression linéaire pour le taux de natalité et de mortalité, fournissant des informations cruciales sur l'impact des caractéristiques. Cette approche a permis d'identifier les features les plus importantes, affinant notre compréhension des facteurs influençant la démographie mondiale de 2000 à 2021. Cette méthodologie, combinant analyse exploratoire et modélisation, renforce notre capacité à extraire des informations pertinentes et à éclairer les dynamiques complexes liées à la natalité et à la mortalité à l'échelle mondiale.

![Alt text](image-1.png)

### Visualisations PowerBI

Un tableau de bord interactif construit dans PowerBI, visant à visualiser et analyser l'évolution de la population mondiale au fil des années, avec un focus particulier sur les données par continent. Le tableau de bord est conçu pour offrir une compréhension approfondie des tendances démographiques en relation avec différents indicateurs.
Lien vers le Deashbord : (rajouter le lien)

### Contenu du Tableau de Bord

### 1. Évolution de la Population par Année

La première page du tableau de bord présente une vue d'ensemble de l'évolution de la population mondiale au cours des années. Des graphiques temporels clairs permettent de suivre les variations démographiques et de repérer les tendances significatives.

### 2. Répartition de la Population par Continent

Les pages suivantes fournissent des analyses détaillées par continent, permettant aux utilisateurs d'explorer les différences et similitudes dans l'évolution démographique. Des filtres interactifs facilitent la sélection de plages temporelles spécifiques.

### 3. Analyse du Taux de Natalité et de Mortalité

Le tableau de bord propose des graphiques spécifiques mettant en évidence le lien entre le taux de natalité et de mortalité, en corrélation avec divers indicateurs. Ces visualisations permettent une compréhension approfondie des facteurs qui influent sur la dynamique démographique.

### 4. Recommandations et Insights

En plus des analyses des données, le tableau de bord inclut des graphiques interactifs visant à fournir des recommandations basées sur les tendances observées. Ces recommandations peuvent aider à orienter les prises de décision et les actions futures.

### Recommandations

A voir avec Dimitri

### Comment Exécuter le Code

Le script (merged_dataset_cleaning.ipynb) rassemble l'ensemble des transformations effectués sur les données.

### Auteurs

*  Nabil LALLAOUI
*  Célia XU
*  Dimitri KNEUR
*  Nigel ZANNOU
