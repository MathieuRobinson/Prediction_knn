Ici j' integre dans un projet dans un projet pour predire le prix de vente des voitures en utilisant l'algorithme de machine learning k plus proches voisins (ou k-Nearest Neighbors en anglais)
J'ai diviser les donnees en 2 partie : une partie entrainement et une partie test. Vous constaterez que les resultats obtenus sur le modele d'entrainement sont presque similaire a ceux du test.
La valeur de k varie de 1 a 25 
Ensuite nous calculons le prix moyen des voitures en utilisant la formule generale 
Posons k=3, alors a+b+c/3=d, ou a,b,c sont les voisins ayanat des valeurs similaires et d est le prix moyen du voiture
Le graphe ci dessous montre que si k est dans l'intervalle [0,5], le prix de voiture est de 4400.
L'ALGORITHME DE K_NN est simple mais efficace ,cependant,il peut etre couteux en termes de calcul, surtout avec de grands ensembles de donnees,car il necessite de calculer les distance pour chaque point d'entrainement.
