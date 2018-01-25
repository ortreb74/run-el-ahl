### Que fait le programme makeblocs_v2.bal ?

il y a deux possibilités :
1. soit le programme crée les textes référencés 
2. soit c'est à partir de la source

### Les données

#### Abstract

sources textes
        jurisprudence
		codes
		
conventions collectives		

#### ELSLIV

dans les "produits" il y a en plus :

* les études
* les formulaires
* les fiches pratiques

#### Hulk

côté hulk, côté front, on livre soit des produits soit des textes. Côté hulk, les sources sont une matière comme une autre  

`hulkliv -mat sources alltxt nojouve`

#### Analyse su script hulkliv

(les commentaires sont écartés)

il y a un premier bloc, jusqu'au premier mot clef "set"

puis il y a un deuxième bloc jusqu'au premier arg et qui se termine à end 