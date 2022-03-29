# euler_method
Programne : chute libre
Auteur : Yassine .T <yass.tyme@gmail.com>
Ce programme utilise la methode d'Euler pour le calcul des vitesses
d'une bille lors d'une chute libre dans un fluide
voir programme 2BACSPF

La methode d'Euler permet de calculer la vitesse en utilisant
une approche iterative. D'apres la deuxieme loi de Newton l'equation
differentielle verifiee par la bille lors d'une chute libre est
donnee par la formule : (I) dV/dt + Beta * V = Alpha (Alpha et Beta sont des constantes)
Pour une bille de masse m = 0.02kg et un coefficient de frottement 
k = x, l'equation (I) s'ecrit sous la forme : (II) dV/dt = 9.26 - 18.52 * V
La relation (II) permet de calculer les accelerations a1, a2,...,an (n point) 
les vitesses v1, v2,...,vn sont calculees par la relation a = dV/dt
En choisissant une valeur dt suffisamment petite on peut calculer une valeur approchee
de la vitesse v(i+1) de la bille a un instant t(i+1) par la formule :
v(i+1) =  a(i) * delta_t + v(i) et a(i) = Alpha -  Beta * v(i)
