# Équations du mouvement pour un M.R.U.A.
Nous savons que plus l'accélération d'une voiture est importante, plus le déplacement est important dans un temps donné. Mais nous n'avons pas développé d'équation spécifique reliant l'accélération au déplacement. Dans cette partie, nous développons quelques équations pratiques pour les relations cinématiques, à partir des définitions du déplacement, de la vitesse et de l'accélération.

## Notation: $t$, $x(t)$, $v(t)$, $a$
Commençons par faire quelques simplifications dans la notation. Prendre le temps initial $t_{0}$ à zéro, comme si le temps était mesuré avec un chronomètre, est une première grande simplification. Puisque le temps écoulé est $\Delta t=t_{f}-t_{0}$, en prenant $t_{0}=0$, $\Delta t$ s'écrira simplement $\Delta t=t_{f}$. Nous allons garder l'indice $0$ pour désigner les valeurs initiales de la position et de la vitesse. Ainsi, $x_{0}$ est la position initiale et $v_{0}$ est la vitesse initiale. Nous ne mettons par contre aucun indice $f$ sur les valeurs finales. $\Delta t=t_{f}=t$ sera la temps final et on notera $x(t)$ la position finale, et $v(t)$ la vitesse finale qu'il faut comprendre comme *la position $x$ au temps final $t$* pour $x(t)$ et *la vitesse $v$ au temps final $t$* pour $v(t)$. Certaines fois, la position et la vitesse finales seront simplement $x$ et $v$. Pour résumer, en utilisant la notation simplifiée, avec le temps initial mis à zéro, on peut écrire:
:::{math}
\begin{align*}
\Delta t	&=	t\\
\Delta x	&=	x(t)-x_{0}\\
\Delta v	&=	v(t)-v_{0}
\end{align*}
:::

où l'indice $0$ désigne une valeur initiale et l'absence d'indice dénote une valeur au temps $t$ final quel que soit le mouvement considéré.

Faisons maintenant l'hypothèse importante que `l'accélération est constante`. Cette hypothèse nous permet d'éviter d'utiliser le calcul pour trouver une accélération instantanée. Puisque l'accélération est constante, les accélérations moyenne et instantanée sont égales et on peut écrire:
:::{math}
a_{moy}=a=\text{constante}
:::
Nous utilisons le symbole $a$ pour l'accélération que nous supposerons constante à tout moment. Supposé que l'accélération est constante ne limite pas sérieusement les situations que nous pouvons étudier, ni ne dégrade la précision de notre traitement. D'une part, l'accélération est constante dans un grand nombre de situations. De plus, dans de nombreuses autres situations, nous pouvons décrire avec précision le mouvement en supposant une accélération constante égale à l'accélération moyenne pour ce mouvement. Enfin, dans les mouvements où l'accélération change radicalement, comme une voiture accélérant à sa vitesse de pointe puis freinant jusqu'à l'arrêt, le mouvement peut être décomposé en petites parties séparées, chacune ayant sa propre accélération constante.

Lorsqu'on connaît trois de ces cinq variables cinématiques - $\Delta x$, $t$, $v_{0}$, $v(t)$, $a$ - pour le mouvement à une dimension d'un objet soumis à une accélération constante, à un `Mouvement Rectiligne Uniformément Accéléré (M.R.U.A)`, on peut utiliser une des équations cinématiques ci-dessous pour exprimer une des variables inconnues.

