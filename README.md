#A quoi servent les sélecteurs CSS <strong>class</strong> et <strong>id</strong> ?

Tout simplement à définir des styles particuliers que l'on voudra reproduire de façon ponctuelle ou récurrente dans les pages HTML.
Une fois que la la feuille de style de base n'a plus de secrets, il est temps de passer à la vitesse supérieure.

Les sélecteurs class et id sont incontournables et indispensables.

##Sélecteurs CSS class et id

Fonctionne avec :

Tous les navigateurs.
Propriétés utilisés :

background-color
float
width
margin
text-align

##Le sélecteur class

Premier exemple : les pages web sont souvent ponctuées d'ancres permettant de remonter en haut de page, et celles-ci sont souvent placées à droite de la page. Il va donc falloir déclarer un style spécial pour cette mise en forme spécifique, et le sélecteur class va nous y aider. A noter que dans la feuille de style, le nom du sélecteur class est toujours précédé d'un point.

##Code css

.haut {
text-align:right;
}

##Sélecteur id

Le sélecteur id a presque la même fonction, à la différence importante qu'on ne peut l'utiliser qu'une seule fois dans la page, contrairement au sélecteur class. C'est pour cela qu'il est plutôt utilisé à la mise en page qu'à la mise en forme de caractères.

Deuxième exemple : construisons une section de page à deux colonnes. L'une des deux colonnes servira pour un menu de 100 pixels de large flottant à gauche, l'autre pour un contenu placé à 110 pixels du bord gauche (pour ne pas empièter sur le menu bien sûr). Cette fois, ce n'est pas d'un point qu'il faudra faire précéder le nom du sélecteur id, mais d'un #.
