## Contexte et problématique
Une entreprise e-commerce souhaite améliorer l'efficacité de ses campagnes publicitaires pour augmenter ses ventes en ligne. Pour cela, elle a décidé de tester deux approches marketing différentes : une version Contrôle correspondant à la campagne publicitaire actuelle, et une version Test proposant un nouveau message, visuel ou ciblage.
L'entreprise a divisé son audience en deux groupes aléatoires et a diffusé chaque version pendant 30 jours en août 2019. L'objectif de cette analyse est de déterminer quelle version de campagne doit être déployée à grande échelle pour maximiser les ventes tout en optimisant les coûts d'acquisition.

## Les données analysées
L'analyse porte sur 30 jours de campagnes publicitaires collectées pour chaque groupe. Les données permettent de suivre le parcours complet d'un utilisateur, depuis l'exposition à la publicité jusqu'à l'achat final. Pour chaque jour et chaque groupe, nous disposons du nombre d'impressions (affichages de la publicité), des clics générés, des vues de contenu produit sur le site, des ajouts au panier, des achats finalisés, ainsi que du budget publicitaire investi.
Ces données couvrent l'intégralité du tunnel de conversion et permettent d'identifier précisément à quelle étape du parcours client chaque version performe le mieux, tout en mesurant l'efficacité économique de chaque approche.

- Date : Date de la campagne (août 2019)
- Spend [USD] : Budget dépensé
- #of Impressions : Nombre d'impressions publicitaires
- Reach : Nombre de personnes uniques atteintes
- #of Website Clicks : Clics vers le site web
- #of Searches : Recherches générées
- #of View Content : Vues de contenu produit
- #of Add to Cart : Ajouts au panier
- #of Purchase : Achats finalisés (conversions)

#### [Télécharger les données du groupe de contrôle](https://github.com/Hines98/Analyse-donnees-RH/blob/4ccd054ddd2f42c1ac39d33b73e2062ebae3942c/HRData.csv)
#### [Télécharger les données du groupe de Test](https://github.com/Hines98/Analyse-donnees-RH/blob/3db3861efafe8bb2ca8977296b1bbec956441594/Report_HR_Data.pbix)
#### [Télécharger le notebook](https://github.com/Hines98/Analyse-donnees-RH/blob/3147568b18126d3accba436bbd87a719f309ccc8/Report_HR_Data.pdf)

## Résultats clés

### Performance d'attraction et d'engagement
L'analyse révèle d'abord une différence majeure dans la capacité des deux campagnes publicitaires à capter l'attention. La version Test affiche un taux de clic (CTR) de 8.2% contre 4.8% pour le Contrôle, soit une amélioration de 70%. Concrètement, pour 1000 personnes exposées à la publicité, la version Test génère 82 clics alors que le Contrôle n'en obtient que 48. Cette différence prouve que le message, le visuel ou le positionnement de la version Test résonne nettement mieux avec l'audience cible et suscite un engagement initial significativement supérieur.

### Efficacité de conversion globale
Au-delà de l'attraction, la version Test démontre également une meilleure capacité à transformer les visiteurs en clients. Le taux de conversion global s'élève à 0.70% pour le Test contre 0.48% pour le Contrôle, représentant une amélioration de 46%. Sur 1000 personnes exposées à la publicité, le Test génère 7 ventes tandis que le Contrôle en produit 5. Cette supériorité de conversion se maintient tout au long du parcours client et n'est pas due au hasard, comme l'ont confirmé les tests statistiques réalisés.

### Structure du volume et projection
Un élément de contexte à préciser : les deux groupes n'ont pas bénéficié du même volume d'exposition. Le groupe Contrôle a reçu 3.2 millions d'impressions contre 2.1 millions pour le Test, soit 33% de volume en plus. Malgré ce désavantage structurel, la version Test a généré presque autant d'achats en valeur absolue : 14 869 ventes contre 15 161 pour le Contrôle, soit une différence de seulement 2%. Cette observation renforce la conclusion sur l'efficacité supérieure du Test. Si nous projetions les performances du Test avec son taux de conversion de 0.070% et le même volume d'impressions que le Contrôle, nous obtiendrions environ 22 000 achats au lieu de 15 000, soit une augmentation potentielle de 47%.

### Coût d'acquisition et rentabilité
L'analyse économique révèle toutefois une nuance importante. Le coût par acquisition s'élève à 6$ pour le Test contre 5.05$ pour le Contrôle, soit un surcoût de 19% par client acquis. Cette différence s'explique en partie par le volume d'exposition plus faible du groupe Test, qui limite les économies d'échelle, et par des dépenses publicitaires totales légèrement supérieures. Le coût par client légèrement plus élevé est largement compensé par la capacité du Test à générer davantage de ventes pour un même niveau d'investissement publicitaire.

### Analyse du parcours client
L'examen détaillé du tunnel de conversion permet d'identifier une friction spécifique dans le parcours du groupe Test. Après avoir cliqué sur la publicité et consulté les produits, seulement 49% des visiteurs du Test ajoutent un article au panier, contre 78% pour le Contrôle. Cette différence marquée suggère une déconnexion entre la promesse véhiculée par la publicité Test et l'expérience vécue sur le site web, ou une inadéquation entre les attentes créées et les produits réellement présentés. En revanche, une fois le produit ajouté au panier, le Test se rattrape avec un excellent taux de transformation : 61% des paniers se convertissent en achats contre 46% pour le Contrôle. Cela indique que les utilisateurs qui franchissent l'étape du panier dans le groupe Test sont particulièrement engagés et déterminés à acheter.


## Recommandations
- La version Test doit être déployée comme nouvelle campagne principale en raison de son efficacité de conversion supérieure de 47%. Dans un premier temps, le budget publicitaire alloué au Test sera progressivement augmenté pour atteindre le même volume que le Contrôle, permettant de confirmer que les performances se maintiennent à plus grande échelle. Cette montée en charge progressive, réalisée sur deux semaines avec un monitoring quotidien, permettra de générer environ 7 000 clients supplémentaires par mois.
- Parallèlement au déploiement, un chantier d'optimisation du parcours utilisateur doit être lancé pour adresser le point faible identifié qui est le faible taux d'ajout au panier. Les pages d'atterrissage seront analysées en profondeur pour identifier les sources de friction. L'objectif est de ramener le taux d'ajout au panier au-dessus de 65%, ce qui réduirait le coût par acquisition d'environ un dollar et rendrait la version Test supérieure sur l'ensemble des métriques.
- Une fois le parcours optimisé et le coût par client réduit, le budget de la version Test sera massivement augmenté pour exploiter pleinement son potentiel.
