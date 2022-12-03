**Qu'est-ce que CRISP DM ?**

![CRISP DM](Aspose.Words.34f6f985-d5de-45a3-9384-0f63dee8f9af.001.png)Diagramme CRISP-DM. Inspiré de [Wikipédia](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining)

Le  **CR** oss  **I** ndustry  **S** tandard  **P** rocess for Data Mining  **(** CRISP  **-** DM *)* est un modèle de processus qui sert de base à un [processus de science des données](https://www.datascience-pm.com/data-science-process/) . Il comporte six phases séquentielles :

1. Compréhension de l'entreprise - De quoi l'entreprise a-t-elle besoin ?
1. Compréhension des données – De quelles données disposons-nous / avons-nous besoin ? Est-ce propre ?
1. Préparation des données – Comment organisons-nous les données pour la modélisation ?
1. Modélisation – Quelles techniques de modélisation devrions-nous appliquer ?
1. Évaluation – Quel modèle répond le mieux aux objectifs commerciaux ?
1. Déploiement – ​​Comment les parties prenantes accèdent-elles aux résultats ?

Publiée en 1999 pour normaliser les processus d'exploration de données dans tous les secteurs, elle est depuis devenue la [méthodologie la plus courante](https://www.datascience-pm.com/crisp-dm-still-most-popular/) pour les projets d'exploration de données, d'analyse et de science des données.

Les équipes de science des données qui combinent une mise en œuvre lâche de CRISP-DM avec des approches globales de gestion de projet [agile en équipe obtiendront probablement les meilleurs résultats.](https://www.datascience-pm.com/agile-data-science/) 

**Quelles sont les 6 phases CRISP-DM ?**

**I. Compréhension commerciale**

**Tout bon projet commence par une compréhension approfondie des besoins du client.** Les projets d'exploration de données ne font pas exception et CRISP-DM le reconnaît. 

La phase de *compréhension de l'entreprise* se concentre sur la compréhension des objectifs et des exigences du projet. Outre la troisième tâche, les trois autres tâches de cette phase sont des activités de gestion de projet fondamentales qui sont universelles à la plupart des projets :

1. **Déterminer les objectifs commerciaux :** vous devez d'abord « bien comprendre, d'un point de vue commercial, ce que le client veut vraiment accomplir ». ( [Guide CRISP-DM](https://web.archive.org/web/20220401041957/https:/www.the-modeling-agency.com/crisp-dm.pdf) ) puis définir les critères de succès de l'entreprise.
1. **Évaluer la situation :** déterminer la disponibilité des ressources, les exigences du projet, évaluer les risques et les imprévus et effectuer une analyse coûts-avantages.
1. **Déterminer les objectifs d'exploration de données :** en plus de définir les objectifs commerciaux, vous devez également définir à quoi ressemble le succès du point de vue de l'exploration de données techniques.
1. **Produire un plan de projet :** sélectionnez les technologies et les outils et définissez des plans détaillés pour chaque phase du projet.

Alors que de nombreuses équipes se précipitent dans cette phase, établir une solide compréhension des affaires, c'est comme construire les fondations d'une maison - absolument essentiel.

**II. Compréhension des données**

Vient ensuite la phase *de compréhension des données.* Ajoutant à la base de *Business Understanding* , il met l'accent sur l'identification, la collecte et l'analyse des ensembles de données qui peuvent vous aider à atteindre les objectifs du projet. Cette phase comporte également quatre tâches :

1. **Collecter les données initiales :** Acquérir les données nécessaires et (si nécessaire) les charger dans votre outil d'analyse.
1. **Décrire les données :** examinez les données et documentez leurs propriétés de surface telles que le format des données, le nombre d'enregistrements ou les identités des champs.
1. **Explorez les données :** creusez plus profondément dans les données. Interrogez-le, visualisez-le et identifiez les relations entre les données.
1. **Vérifier la qualité des données :** dans quelle mesure les données sont-elles propres/sales ? Documentez tout problème de qualité.

**III. Préparation des données**

Une règle générale est que 80 % du projet est la préparation des données.

Cette phase, souvent appelée « data munging », prépare le ou les ensembles de données finaux pour la modélisation. Il a cinq tâches :

1. **Sélectionner les données :**  Déterminez quels ensembles de données seront utilisés et documentez les raisons de l'inclusion/exclusion.
1. **Nettoyer les données :**  il s'agit souvent de la tâche la plus longue. Sans cela, vous serez probablement victime de l'entrée et de la sortie des ordures. Une pratique courante au cours de cette tâche consiste à corriger, imputer ou supprimer des valeurs erronées.
1. **Construire des données :**  dérivez de nouveaux attributs qui seront utiles. Par exemple, dérivez l'indice de masse corporelle d'une personne à partir des champs de taille et de poids.
1. **Intégrer des données :**  créez de nouveaux ensembles de données en combinant des données provenant de plusieurs sources.
1. **Formater les données :**  reformatez les données si nécessaire. Par exemple, vous pouvez convertir des valeurs de chaîne qui stockent des nombres en valeurs numériques afin de pouvoir effectuer des opérations mathématiques.

**IV. La modélisation**

Ce qui est largement considéré comme le travail le plus passionnant de la science des données est aussi souvent la phase la plus courte du projet.

Ici, vous allez probablement créer et évaluer divers modèles basés sur plusieurs techniques de modélisation différentes. Cette phase comporte quatre tâches :

1. **Sélectionnez les techniques de modélisation :**  déterminez les algorithmes à essayer (par exemple, la régression, le réseau de neurones).
1. **Générer une conception de test : en** attendant votre approche de modélisation, vous devrez peut-être diviser les données en ensembles de formation, de test et de validation.
1. **Modèle de construction :**  Aussi glamour que cela puisse paraître, cela pourrait simplement exécuter quelques lignes de code comme « reg = LinearRegression().fit(X, y) ».
1. **Évaluer le modèle :**  généralement, plusieurs modèles sont en concurrence les uns avec les autres et le spécialiste des données doit interpréter les résultats du modèle en fonction de la connaissance du domaine, des critères de réussite prédéfinis et de la conception du test.

Bien que le  [guide CRISP-DM](https://web.archive.org/web/20220401041957/https:/www.the-modeling-agency.com/crisp-dm.pdf)  suggère de "réitérer la construction et l'évaluation du modèle jusqu'à ce que vous croyiez fermement que vous avez trouvé le(s) meilleur(s) modèle(s)", dans la pratique, les équipes doivent continuer à itérer jusqu'à ce qu'elles trouvent un modèle "assez bon", passez par le CRISP -Cycle de vie DM, puis améliorer encore le modèle dans les futures itérations. 

**V. Évaluation**

Alors que la tâche d’évaluation du *modèle de la phase de modélisation* se concentre sur l'évaluation du modèle technique, la phase *d'évaluation* examine plus largement quel modèle correspond le mieux à l'entreprise et ce qu'il faut faire ensuite. Cette phase comporte trois tâches :

1. **Évaluer les résultats :**  les modèles répondent-ils aux critères de réussite commerciale ? Le(s)quel(s) devrions-nous approuver pour l'entreprise ?
1. **Processus d'examen :** Passez en revue le travail accompli. Quelque chose a-t-il été oublié ? Toutes les étapes ont-elles été correctement exécutées ? Résumez les résultats et corrigez quoi que ce soit si nécessaire.
1. **Déterminez les étapes suivantes :**  sur la base des trois tâches précédentes, déterminez s'il faut procéder au déploiement, poursuivre l'itération ou lancer de nouveaux projets.

**VI. Déploiement**

*"Selon les exigences, la phase de déploiement peut être aussi simple que la génération d'un rapport ou aussi complexe que la mise en œuvre d'un processus d'exploration de données reproductible dans toute l'entreprise."*

– [Guide CRISP-DM](https://web.archive.org/web/20220401041957/https:/www.the-modeling-agency.com/crisp-dm.pdf)

**Un modèle n'est particulièrement utile que si le client peut accéder à ses résultats.** La complexité de cette phase est très variable. Cette phase finale comporte quatre tâches :

1. **Planifier le déploiement :**  développer et documenter un plan de déploiement du modèle.
1. **Planifier la surveillance et la maintenance :**  Élaborez un plan de surveillance et de maintenance approfondi pour éviter les problèmes pendant la phase opérationnelle (ou la phase post-projet) d'un modèle.
1. **Produire un rapport final :**  l'équipe de projet documente un résumé du projet qui peut inclure une présentation finale des résultats de l'exploration de données.
1. **Bilan du projet :**  Réalisez une rétrospective du projet sur ce qui s'est bien passé, ce qui aurait pu être mieux et comment s'améliorer à l'avenir.

Le travail de votre organisation pourrait ne pas s'arrêter là. En tant que cadre de projet, CRISP-DM ne décrit pas ce qu'il faut faire après le projet (également appelé « opérations »). Mais si le modèle va en production, assurez-vous de maintenir le modèle en production. Une surveillance constante et un réglage occasionnel du modèle sont souvent nécessaires.

**CRISP-DM est-il Agile ou Waterfall ?**

Certains affirment qu'il est flexible et agile, tandis que d'autres considèrent CRISP-DM comme rigide. Ce qui compte vraiment, c'est comment vous l'implémentez.

[**Cascade](https://www.datascience-pm.com/waterfall/) **:** d’une part, beaucoup considèrent CRISP-DM comme un processus en cascade rigide - en partie parce que ses exigences en matière de rapports sont excessives pour la plupart des projets. De plus, le guide indique dans la phase de compréhension de l'entreprise que "le plan de projet contient des plans détaillés pour chaque phase" - un aspect caractéristique des approches traditionnelles en cascade qui nécessitent une planification détaillée et initiale.

En effet, si vous suivez CRISP-DM avec précision (définissant des plans détaillés pour chaque phase au début du projet et incluez chaque rapport) et choisissez de ne pas itérer fréquemment, alors vous exploitez davantage un processus en cascade.

[**Agile](https://www.datascience-pm.com/agile-data-science/) **:** D'autre part, le CRISP-DM prône indirectement des principes et des pratiques agiles en déclarant : « L'enchaînement des phases n'est pas figé. Des allers-retours entre les différentes phases sont toujours nécessaires. Le résultat de chaque phase détermine quelle phase, ou quelle tâche particulière d'une phase, doit être effectuée ensuite. »

Ainsi, si vous suivez CRISP-DM de manière plus flexible, itérez rapidement et superposez d'autres processus agiles, vous vous retrouverez avec une approche agile.

**Exemple :** Pour illustrer comment CRISP-DM pourrait être mis en œuvre de manière Agile ou en cascade, imaginez un projet de désabonnement avec trois livrables : un modèle de désabonnement volontaire, un modèle de désabonnement sans déconnexion payante et une propension à accepter une offre axée sur la fidélisation. .

**Cascade CRISP-DM : découpage horizontal**

En savoir plus sur le découpage en tranches [verticales vs horizontales Science des données](https://www.datascience-pm.com/vertical-vs-horizontal-slicing-data-science-deliverables/)

Dans une implémentation en cascade, le travail de l'équipe s'étendrait de manière exhaustive et horizontale sur chaque livrable, comme indiqué ci-dessous. L'équipe peut rarement revenir à une couche horizontale inférieure uniquement en cas de besoin critique. Un livrable « big bang » est livré à la fin du projet.

![Cascade CRISP-DM](crisp-dm-horizontal-waterfall-600x.gif)

**CRISP-DM Agile : découpage vertical**

Alternativement, dans une mise en œuvre agile de CRISP-DM, l'équipe se concentrerait étroitement sur la livraison rapide d'une tranche verticale de la chaîne de valeur à la fois, comme indiqué ci-dessous. Ils fourniraient plusieurs versions verticales plus petites et solliciteraient fréquemment des commentaires en cours de route.

![CRISP-DM Agile](crisp-dm-vertical-agile-600px)

**Ce qui est mieux ?**

Lorsque cela est possible, adoptez une approche agile et découpez verticalement afin que :

- Les parties prenantes obtiennent de la valeur plus tôt
- Les parties prenantes peuvent fournir des commentaires significatifs
- Les scientifiques des données peuvent évaluer les performances du modèle plus tôt
- L'équipe de projet peut ajuster le plan en fonction des commentaires des parties prenantes

**Dois-je utiliser CRISP-DM pour la science des données ?**

**Avantages**

*Du point de vue de la science des données d'aujourd'hui, cela semble être du bon sens. C'est exactement le point. Le processus commun est si logique qu'il est devenu intégré dans toute notre éducation, notre formation et notre pratique.*

-William Vorheis, l'un des auteurs du CRISP-DM (de  [Data Science Central](https://www.datasciencecentral.com/profiles/blogs/crisp-dm-a-standard-methodology-to-ensure-a-good-outcome) )

- **Généralisable :**  bien que conçu pour l'exploration de données, William Vorhies, l'un des créateurs de CRISP-DM, affirme que, parce que tous les projets de science des données commencent par une compréhension commerciale, ont des données qui doivent être collectées et nettoyées, et appliquent des algorithmes de science des données, " CRISP-DM fournit des conseils solides, même pour les activités de science des données les plus avancées d'aujourd'hui » ( [Vorhies, 2016](https://www.datasciencecentral.com/profiles/blogs/crisp-dm-a-standard-methodology-to-ensure-a-good-outcome) ).
- **Bon sens :**  lorsqu'on a demandé aux étudiants de réaliser un projet de science des données sans direction de gestion de projet, ils "ont tendu vers une méthodologie de type CRISP et ont identifié les phases et effectué plusieurs itérations". De plus, les équipes formées et explicitement invitées à mettre en œuvre le CRISP-DM ont obtenu de meilleurs résultats que les équipes utilisant d'autres approches ( [Saltz, Shamshurin et Crowston, 2017](https://scholarspace.manoa.hawaii.edu/bitstream/10125/41273/1/paper0124.pdf) ).
- **Adoptable :**  comme  [Kanban](https://www.datascience-pm.com/kanban/) , CRISP-DM peut être mis en œuvre sans trop de formation, de changement de rôle organisationnel ou de controverse.
- **Bon départ :**  l'accent initial mis sur la *compréhension de l’entreprise est* utile pour aligner le travail technique sur les besoins de l'entreprise et pour éviter que les scientifiques des données ne se lancent dans un problème sans comprendre correctement les objectifs de l'entreprise.
- **Finition solide :**  sa dernière étape, le déploiement *,* aborde également des considérations importantes pour clôturer le projet et passer à la maintenance et aux opérations.
- **Flexible :** une implémentation lâche de CRISP-DM peut être flexible pour fournir de nombreux avantages des principes et pratiques [agiles . ](https://www.datascience-pm.com/agile-data-science/)En acceptant qu'un projet commence par des inconnues importantes, l'utilisateur peut parcourir les étapes, acquérant à chaque fois une compréhension plus approfondie des données et du problème. Les connaissances empiriques acquises lors des cycles précédents peuvent ensuite alimenter les cycles suivants.

