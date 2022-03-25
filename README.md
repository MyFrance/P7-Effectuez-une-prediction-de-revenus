# P7-Effectuez-une-prediction-de-revenus (70h)

# Compétences évaluées
#### Maîtriser les bases de la statistique inférentielle
#### Maîtriser les bases des probabilités
#### Modéliser des données

# Prérequis
Pour ce projet, il sera utile de savoir réaliser une analyse de statistique descriptive en langages Python (avec des représentations graphiques). Il faudra également appliquer des modélisations de type ANOVA ou régression linéaire.

# Scénario

Vous êtes employé dans une banque, présente dans de nombreux pays à travers le monde. Celle-ci souhaite cibler de nouveaux clients potentiels, plus particulièrement les jeunes en âge d'ouvrir leur tout premier compte bancaire.

Cependant, elle souhaite cibler les prospects les plus susceptibles d'avoir, plus tard dans leur vie, de hauts revenus.

L'équipe dans laquelle vous travaillez a donc reçu pour mission de créer un modèle permettant de déterminer le revenu potentiel d'une personne.

Très bien.

"Quelles informations avons-nous ?" demandez-vous à votre supérieur, qui vous répond : "À vrai dire... quasiment aucune : uniquement le revenu des parents, car nous allons cibler les enfants de nos clients actuels, ainsi que le pays où ils habitent. C'est tout ! Ah oui, une dernière chose : ce modèle doit être valable pour la plupart des pays du monde. Je vous laisse méditer là-dessus… Bon courage !"
Avec aussi peu de données disponibles, cela semble être un sacré challenge !

Ainsi, vous proposez une régression linéaire avec 3 variables :

le revenu des parents ;
le revenu moyen du pays dans lequel habite le prospect ;
l'indice de Gini calculé sur les revenus des habitants du pays en question. 

# Données 
Un jeu de données initial contient :

World Income Distribution, datée de 2008,
Indices de Gini estimés par la Banque Mondiale.
