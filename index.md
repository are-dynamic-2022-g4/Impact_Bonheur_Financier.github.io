# L'impact d'un événement financier sur le bonheur d'une population
## Introduction
Nous avons décidé de nous pencher sur l’impact qu’un événement financier a sur un groupe d’individu et comment il influe sur le bonheur de l’ensemble de la population. Pour cela nous allons créer un système dynamique qui nous permettra d’observer cet impact.

### Problématique
Comment un événement financier influencera-t-il le bonheur général d’une population ?

### Hypothèse
Un événement financier sur un groupe d’individu aura un impact faible sur le bonheur général de la population si le groupe n’est pas assez conséquent, mais un impact fort sur ledit groupe.

## Objectifs
Créer une population d’individus avec des caractéristiques prédéfinies Créer des événements aléatoires, dont financiers, qui ont une influence plus ou moins importante sur le bonheur Calculer le bonheur avant et après ces événements pour étudier leur impact sur le bonheur de la population globale Créer des liens entre les individus de la population

### Critère de calculs du bonheur
La consommation moyenne Le taux de pauvreté Les inégalités salariales Le taux de chômage

## Déroulement

1ere semaine :	
Durant la première semaine nous avons voulu commencer à coder notre système avec des boucle for,if,else,… Cependant nous avons du 
changer l’orientation de notre programmation suite a la demande de notre enseignante et nous orienter plus sur de la Programmation 
Orientée Objet. Malheureusement nous ne connaissions pas bien ce type de programmation ce qui a compliqué l’adaptation du code. 
Nous avons donc fini la première semaine avec un code comportant un début de système (famille,revenu,…) mais n’étant pas fait 
grâce a des Class.

2e semaine :	
Durant la deuxième semaine,nous nous somme concentrer sur l’adaptation complète de notre code grâce aux Class. Pendant cette semaine
nous avons aussi      placé certains paramètre de notre Class comme l’âge, le salaire, le genre et le statut familial. Nous avons 
donc pris des valeurs fournis par l’INSEE pour la population française en 2017. Pour inclure lesdites données nous avons créer des
dictionnaire rassemblant les informations nécessaire.

3e semaine :	
Durant la troisième semaine nous avons commencer à appliquer le calcul du Bonheur Intérieur Net(BIN) à notre système. Pour cela nous
avons due ajouter 2 paramètres a notre Class : la consommation d’un individu et la situation professionnel de l’individu(Travail ou 
Chômage). Nous avons donc commencer a calculer le bonheur par individu et a appliquer le début de ladite formule pour calculer le 
bonheur. C’est d’ailleurs durant cette semaine que nous avons décider de laisser de côté les situations familiales pour l’instant car
cela rendait le système très compliqué a faire. Nous avons donc ajouter 2 dictionnaires pour la consommation et la situation 
professionnel.

4e semaine :	
Durant la quatrième semaine, nous avons clarifier notre code en changeant certains calculs qui se répéter et en changeant la façon de
faire des dictionnaires pour limiter l’écriture de code. De plus nous avons régler certains bogues qui empêcher le bon fonctionnement
du système. Nous avons aussi rajouter un principe de licenciement qui permet aux individus de changer de situation professionnel et 
en incluant une période d’immunité ou ils ne peuvent pas être renvoyer.

5e semaine :	
Durant la cinquième semaine nous avons effectuer la finition de la base du code et nous avons commencer a faire le visuel de notre
système en créant des graphique pour permettre la visualisation du système. Nous avons aussi remis en ordre le code pour la création
de plusieurs simulations et pour permettre leurs comparaisons.De plus nous avons aussi commencé la mise en place de groupe d'individu
(Famille,Connaissance,Amis) pour permettre la propagation du bonheur.



#### Graphique du bonheur moyen de la population en fonction du nombre de jours:
![Bonheur moyen de la population](https://cdn.discordapp.com/attachments/489890771668041738/965671340004749352/IMG-20220418-WA0002.jpg)

#### Graphique du bonheur en fonction du revenu:
![Bonheur en fonction du revenu](https://cdn.discordapp.com/attachments/489890771668041738/965671339761467422/IMG-20220418-WA0003.jpg)
*0:1500€/mois    1:2000€/mois   2:2500€/mois     3:3000€/mois    4:3500€/mois     5:4000+€/mois    6:1170€/mois(Chômage)



## Bibliographie
Nous avons utiliser pour la plupart de nos recherches les études publiés par l'INSEE car nous considérions ses résultats comme vérifiés et de plus il nous permettait d'avoir des valeurs précise pour la population Française.

#### Femmes et Hommes
https://www.insee.fr/fr/statistiques/4238375?sommaire=4238781 
#### Chômage
https://www.insee.fr/fr/statistiques/4238387?sommaire=4238781 
#### Revenu salarial
https://www.insee.fr/fr/statistiques/4238391?sommaire=4238781 
#### Niveau de vie
https://www.insee.fr/fr/statistiques/4238393?sommaire=4238781 
#### Revenu moyen de la population française
![Revenu salarial moyen](https://cdn.discordapp.com/attachments/489890771668041738/965890919276625961/25111.jpeg)
