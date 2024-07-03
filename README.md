# sturdy-barnacle
DS

Définition de la fonction chebyshev_distance(p1, p2) :

La fonction prend deux arguments p1 et p2, qui sont des tuples représentant des points dans un espace multidimensionnel.
Elle retourne la distance de Chebyshev entre ces deux points.
Calcul de la distance de Chebyshev :

La distance de Chebyshev entre deux points est définie comme le maximum des valeurs absolues des différences entre les coordonnées correspondantes des deux points.
Le code utilise une compréhension de liste pour itérer sur les paires de coordonnées correspondantes (x, y) des deux points p1 et p2 en utilisant la fonction zip.
Pour chaque paire (x, y), il calcule la valeur absolue de leur différence abs(x - y).
Ensuite, il retourne la valeur maximale de ces différences en utilisant la fonction max.
Bloc principal :

Le bloc if __name__ == "__main__": permet de s'assurer que le code dans ce bloc ne s'exécute que si le script est exécuté directement (et non importé comme un module).
Deux points point1 et point2 sont définis comme tuples (1, 2, 3) et (4, 5, 6) respectivement.
La distance de Chebyshev entre ces deux points est calculée en appelant la fonction chebyshev_distance avec point1 et point2 comme arguments.
La distance calculée est ensuite affichée à l'écran avec la fonction print.
