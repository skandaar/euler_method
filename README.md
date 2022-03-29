# euler_method
## Programne : chute libre d'une bille dans un fluide
## Auteur : Yassine .T \<yass.tyme@gmail.com\>
Ce programme utilise la methode d'Euler pour le calcul des vitesses<br />
d'une bille lors d'une chute libre dans un fluide<br />
voir [programme 2BACSPF](https://www.alloschool.com/course/physique-et-chimie-2eme-bac-sciences-physiques-biof#!)

La methode d'Euler permet de calculer la vitesse en utilisant<br />
une approche iterative. D'apres la deuxieme loi de Newton l'equation<br />
differentielle verifiee par la bille lors d'une chute libre est donnee<br /> 
par la formule : (I) dV/dt + Beta * V = Alpha (Alpha et Beta sont des constantes).<br />

Pour une bille de masse m = 0.02kg et un coefficient de frottement<br />
k = x, l'equation (I) s'ecrit sous la forme : (II) dV/dt = 9.26 - 18.52 * V<br />
La relation (II) permet de calculer les accelerations a1, a2,...,an (n point)<br /> 
les vitesses v1, v2,...,vn sont calculees par la relation a = dV/dt<br />
En choisissant une valeur dt suffisamment petite on peut calculer une valeur approchee<br />
de la vitesse v(i+1) de la bille a un instant t(i+1) par la formule :<br />
v(i+1) =  a(i) * delta_t + v(i) et a(i) = Alpha -  Beta * v(i)<br />
