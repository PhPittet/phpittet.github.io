(chap:ecritute_sci)=
# Écriture scientifique
## Notations scientifique et d'ingénieur
La gamme d'objets et de phénomènes étudiés en physique est immense. De la durée de vie incroyablement courte d'un noyau à l'âge de la Terre, des petites tailles de particules sous-nucléaires aux grande distance jusqu'aux bords de l'univers connu, de la force exercée par une puce sauteuse à la force entre la Terre et le soleil, les scientifiques (physiciens, astronomes, microbiologistes,...) doivent souvent écrire des nombres trop grands ou trop petits pour être écrits sous forme décimale.
 
Afin d'alléger et de simplifier cette écriture des nombres, les scientifiques utilisent [l'écriture scientifique](https://fr.wikipedia.org/wiki/Notation_scientifique) qui représente un nombre avec une puissance de $10$.

:::{admonition} Exemples
:class: exores
1. $5'300'000'000.0\, m= 5.3\cdot 10^9\, m$
2. $0.000'000'000'000'987\, s= 9.87 \cdot 10^{-13}\, s$
:::

On définit deux notations particulières avec les puissances de $10$ :
1. La `Notation Scientifique` et
2. La `Notation d'Ingénieur`

:::{admonition} Notation scientifique
:class: formule
Écrire un nombre en ***notation scientifique***, c'est exprimer une valeur numérique sous la forme :

$$x\cdot 10^{n}$$

avec : $1\leq x< 10$ et $n$ un nombre entier
:::

:::{admonition} Notation d'Ingénieur
:class: formule
Écrire un nombre en ***notation d'ingénieur***, c'est exprimer une valeur numérique sous la forme :

$$x\cdot 10^{3n}$$

avec : $1\leq x< 1000$ et $n$ un nombre entier
:::

:::{admonition} Exemples de notations
:class: exores
1.  Pour écrire $47'800'000.0$ en notation scientifique, il faut mettre la virgule après le premier chiffre du nombre et donc la déplacer, vers la gauche, de 7 positions.\
    En notation scientifique il devient $4.78\cdot 10^{7}$

3.  Pour écrire $47'800'000.0$ en notation d'ingénieur, il faut déplacer la virgule de trois en trois, vers la gauche, jusqu'à obtenir un nombre enter 1 et 1000, donc la déplacer de 6 positions.\
    En notation d'ingénieur il devient $47.8\cdot 10^{6}$

5.  Pour écrire $0.000 032 050$ en notation scientifique, il faut mettre la virgule après le premier chiffre du nombre et donc la déplacer, vers la droite de 5 positions.\
    En notation scientifique il devient $3.205\cdot 10^{-5}$

7.  Pour écrire $0.000 032 050$ en notation d'ingénieur, il faut déplacer la virgule de trois en trois, vers la droite, jusqu'à obtenir un nombre enter 1 et 1000, donc la déplacer de 6 positions.\
    En notation d'ingénieur il devient $32.05\cdot 10^{-6}$

9.  $7.34\cdot 10^{4}$ est en notation scientifique mais pas en notation d'ingénieur.

10.  $73.4\cdot 10^{3}$ n'est pas en notation scientifique, mais en notation d'ingénieur.

11.  $0.734\cdot 10^{5}$ n'est ni en notation scientifique, ni en notation d'ingénieur.

12.  $3.205\cdot 10^{6}$ est en notation scientifique et en notation d'ingénieur.
:::

La notation d'ingénieur est largement utilisée par les scientifiques, en raison de l'utilisation du multiple de $3$ pour l'exposant, ce qui facilite les mesures et les changements d'unités dans le système métrique international. On représente ainsi les nombres en utilisant l'unité de base et ses sous-multiples de puissance de $3$. Si l'unité de base est le mètre, un ingénieur représentera le résultat de sa mesure selon les règles de la notation :

- soit en *mètres*

- soit, si la valeur est petite ou très petite, en utilisant soit $\cdot 10^{-3}$ pour les *millimètres*, soit $\cdot 10^{-6}$ pour les *micromètres* ou encore, si la valeur est grande, $\cdot 10^{3}$ pour les *kilomètres*.

:::{admonition} Exemple de calcul
:class: exores dropdown
$\dfrac{0,00072\cdot 8500}{0,012\cdot 300000}=\dfrac{7,2\cdot 10^{-4}\cdot 8,5\cdot 10^{3}}{1,2\cdot 10^{-2}\cdot 3,0\cdot 10^{5}}=\dfrac{7,2\cdot 8,5}{1,2\cdot 3,0}\cdot \dfrac{10^{-4}\cdot 10^{3}}{10^{-2}\cdot 10^{5}}=17\cdot 10^{-4}=1,7\cdot 10^{-3}$
:::

:::{admonition} Sur la calculatrice
:class: surcalculatrice
La touche `EE` de la calculatrice permet de taper facilement les puissances de $10$.

Pour écrire $8.23\cdot 10^{-7}$ avec la calculatrice, on tape dans l'ordre: `8` $\rightarrow$ `.` $\rightarrow$ `2` $\rightarrow$ `3` $\rightarrow$ `EE` $\rightarrow$ `+/-` $\rightarrow$ `7`. Il s'affiche alors $8.23\,-07$.

La fonction `SCI`, qui s'obtient en tapant `2nd` et `5`, permet de transformer n'importe quel nombre en notation scientifique (*avec une puissance de $10$*).\
La fonction `ENG`, qui s'obtient en tapant `2nd` et `6`, permet de transformer n'importe quel nombre en notation d'ingénieur.\
La fonction `FLO`, qui s'obtient en tapant `2nd` et `4`, permet de transformer n'importe quel nombre écrit avec une puissance de $10$ en un nombre à virgule.

Effectuer avec votre calculatrice: $1.5625\cdot 10^{-2} \times 1.024\cdot 10^{3}$ et vérifier que le résultat est bien $16$.
:::

## Ordres de grandeur

Lorsque l'on compare différents nombres, il est important, en sciences, de prendre en compte la taille de ces nombres. Ainsi, par exemple, à l'échelle humaine (c'est-à-dire le mètre) la vitesse de la lumière est tellement grande ($300'000'000.0$ mètres en 1 seconde !) que le temps mis par un rayon lumineux émis par un éclair est quasi-instantané. Par contre, la vitesse du son étant beaucoup plus petite ($340$ mètres en 1 seconde), qu'un décalage apparaît entre la foudre et le coup de tonnerre.

Ces deux vitesses ont des tailles, ou des `ordres de grandeurs`, différents :
- La vitesse de la lumière est le l'ordre des centaines de millions de mètres par seconde.
- La vitesse du son de l'ordre des centaines de mètres par secondes.

Le terme ordre de grandeur fait référence à la puissance de $10$ lorsque les nombres sont exprimés en notation scientifique. Les grandeurs qui ont la même puissance de $10$ lorsqu'elles sont exprimées en notation scientifique, ou qui s'en rapprochent, sont dites *du même ordre de grandeur*.

:::{admonition} Ordre de Grandeur
:class: formule
L'*ordre de grandeur* d'un nombre en écriture scientifique $x\cdot 10^{n}$ vaut :

$$\begin{array}{ccl}
10^{n} & \text{si} & 1\leq x<5 \\
10^{n+1} & \text{si} & 5\leq x<10
 \end{array}$$
:::

:::{admonition} Exemples d'ordre de grandeur
:class: dropdown exores
1.  L'ordre de grandeur de $4.96\cdot 10^{6}$ est $10^{6}$

2.  L'ordre de grandeur de $7.34\cdot 10^{4}$ est $10^{5}$

3.  L'ordre de grandeur de $7.34\cdot 10^{-4}$ est $10^{-3}$

4.  L'ordre de grandeur de $-2.3\cdot 10^{3}$ est $10^{3}$

5.  L'ordre de grandeur de la distance parcourue par le son en 1 seconde est la centaine de mètres, c'est-à-dire $10^{2}\, m$

6.  L'ordre de grandeur de la distance parcourue par la lumière en 1 seconde est la centaine de million de mètres, c'est-à-dire
    $10^{2}\times 10^{6}=10^{8}\, m$
:::

:::{admonition} YouTube
:class: dropdown admonition-youtube
Quelques liens de vidéo utiles sur le même sujet :
- **Écriture scientifique d'un nombre mathématiques**
%%HTML [--isolated]
<div align="center">
 <iframe width="600" height="400" src="https://www.youtube.com/embed/WvMgAdWhUf4" allowfullscreen></iframe>
</div>

- **Qu'est-ce que la notation scientifique ?**
%%HTML [--isolated]
<div align="center">
 <iframe width="600" height="400" src="https://www.youtube.com/embed/bslmbDIO704" allowfullscreen></iframe>
</div>
:::
