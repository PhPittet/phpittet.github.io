# Questions conceptuelles

::::{admonition} Question 1
:class: question
Un élève écrit : "Un oiseau qui plonge sur sa proie a une vitesse de $-10\,m/s$".\
Quel est le problème avec la déclaration de l'élève ? Qu'est-ce que l'élève a réellement décrit ?\
Expliquez.
:::{admonition} *réponse*
:class: dropdown questionsol
Si l'oiseau *plonge*, c'est que la direction de son mouvement est vertical dirigé vers le bas (l'axe de référence est dirigé vers le bas). Or si la vitesse de l'oiseau est négative, cela signifie que la direction du mouvement de l'oiseau est inverse de la direction positive de l'axe, donc l'oiseau *monte* !
:::
::::

::::{admonition} Question 2
:class: question
L'accélération est le changement de vitesse dans le temps. Compte tenu de ces informations, l'accélération est-elle un vecteur ou une quantité scalaire ?\
Expliquez.
:::{admonition} *réponse*
:class: dropdown questionsol
Le changement de vitesse est un vecteur et le temps un scalaire. Si on divise un vecteur par un scalaire, on obtient encore un vecteur, de même direction mais avec une plus petite amplitude (longueur).
:::
::::

::::{admonition} Question 3
:class: question
Une prévision météorologique indique que la température devrait être $-5°C$, le jour suivant. Cette température est-elle un vecteur ou une grandeur scalaire ?\
Expliquez.
:::{admonition} *réponse*
:class: dropdown questionsol
La température n'a pas besoin de direction pour être définie. C'est donc un scalaire
:::
::::

::::{admonition} Question 4
:class: question
Lequel des éléments suivants est un vecteur: la taille d'une personne, l'altitude du mont Everest, l'âge de la Terre, le point d'ébullition de l'eau, l'accélération de la gravité, le coût de ce livre, la population de la Terre  ?
:::{admonition} *réponse*
:class: dropdown questionsol
l'accélération de la gravité
:::
::::

::::{admonition} Question 5
:class: question
Quel est le point commun entre les vecteurs et les scalaires ? Comment diffèrent-ils ?
:::{admonition} *réponse*
:class: dropdown questionsol
Les deux possèdent une amplitude, mais le vecteur a besoin d'une direction en plus. A 2 (ou plus) dimensions, le vecteur possède plusieurs coordonnées, alors que le scalaire n'a qu'une valeur (identique dans toutes les dimensions)
:::
::::

:::::{admonition} Question 6
:class: question
Deux campeurs dans un parc national partent en randonnée de leur chalet au même endroit sur un lac, chacun empruntant un chemin différent, comme illustré ci-dessous. La distance totale parcourue le long du chemin $1$ est de $7.5\,km$ et celle le long du chemin $2$ est de $8.2\,km$.\
Quel est le déplacement final de chaque campeur ?
:::{figure} figures/ExQC2_6.jpg
:name: ExQC2_6
:align: center
:width: 30%
:::
::::{admonition} *réponse*
:class: dropdown questionsol
De $S=5\,km$ à $40°$ Nord-Est,\
ou :
:::{math}
\overrightarrow{S}=
    \begin{pmatrix} 
      S_{x}\\ 
      S_{y}
    \end{pmatrix}=
    \begin{pmatrix} 
      5\cdot\cos(40)\\ 
      5\cdot\sin(40)
    \end{pmatrix}
:::
::::
:::::

::::{admonition} Question 7
:class: question
Si on dit à un pilote d'avion de parcourir $123\,km$ en ligne droite pour se rendre de San Francisco à Sacramento, expliquez pourquoi il pourrait se retrouver n'importe où sur le cercle illustré à la figure ci-dessous. De quelles autres informations aurait-il besoin pour se rendre à Sacramento ?
:::{figure} figures/TrajAvion.jpg
:name: TrajAvion
:align: center
:width: 30%
:::
:::{admonition} *réponse*
:class: dropdown questionsol
Il lui manque la direction de $45°$ Nord-Est. Sans cette information, le pilote peut partir dans n'importe quelle direction.
:::
::::

::::{admonition} Question 8
:class: question
1. Est-il possible d'ajouter un scalaire à un vecteur ?
2. Est-il possible de multiplier un scalaire avec un vecteur ?
:::{admonition} *réponse*
:class: dropdown questionsol
1. Non
2. Oui; par exemple $5\cdot\overrightarrow{7}\,N=\overrightarrow{35}\,N$
:::
::::

::::{admonition} Question 9
:class: question
Supposons que vous fassiez deux pas $A$ et $B$ (c'est-à-dire deux déplacements non nuls).
1. Dans quelles circonstances pouvez-vous vous retrouver à votre point de départ ? Plus généralement, dans quelles circonstances deux vecteurs non nuls peuvent-ils s'additionner pour donner zéro ?
2.  Est-ce que la distance maximale que vous pouvez parcourir depuis le point de départ est la somme des longueurs des deux pas $A+B$ ?
:::{admonition} *réponse*
:class: dropdown questionsol
1. Lorsque les deux vecteurs ont la même intensité (même valeur absolue), mais des directions opposées $\overrightarrow{A}+\overrightarrow{B}=\overrightarrow{A}+(-\overrightarrow{A})=0.
2. La distance maximale sera de $\lVert \vec{A} \rVert +\lVert \vec{B} \rVert$
:::
::::

::::{admonition} Question 10
:class: question
Si vous faites deux pas de tailles différentes, pouvez-vous vous retrouver à votre point de départ? Plus généralement, deux vecteurs d'amplitudes différentes peuvent-ils s'additionner pour donner zéro ? Est-ce que trois vecteur (ou plus) le peuvent ?
:::{admonition} *réponse*
:class: dropdown questionsol
Non pour 2, Oui pour 3.
:::
::::

:::::{admonition} Question 11
:class: question
Donner un exemple de vecteur non nul dont une composante est nulle.
::::{admonition} *réponse*
:class: dropdown questionsol
Le vecteur accélération terrestre $\vec{g}$ qui est uniquement vertical. Sa composante horizontale est toujours nulle :
:::{math}
\overrightarrow{g}=
    \begin{pmatrix} 
      g_{x}\\ 
      g_{y}
    \end{pmatrix}=
    \begin{pmatrix} 
      0\\ 
      9.81
    \end{pmatrix} m/s^{2}
:::
::::
:::::

:::::{admonition} Question 12
:class: question
Expliquez pourquoi un vecteur ne peut pas avoir une composante supérieure à sa propre amplitude.
::::{admonition} *réponse*
:class: dropdown questionsol
Car l'amplitude d'un vecteur se calcul avec Pythagore.\
Si
:::{math}
\overrightarrow{A}=
    \begin{pmatrix} 
      A_{x}\\ 
      A_{y}
    \end{pmatrix}
:::
alors son amplitude vaut : $\Vert\overrightarrow{A}\Vert=\sqrt{A_{x}^{2}+A_{y}^{2}}\geqslant A_{x}$ (ou $A_{y}$)
::::
:::::