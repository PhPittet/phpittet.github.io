# Questions conceptuelles

::::{admonition} Questions 1
:class: question
Quelle est l'accélération d'une pierre lancée tout droit vers le haut :
1. En montant ?
2. Au sommet de son envol ?
3. En descendant ?
:::{admonition} *réponse*
:class: dropdown questionsol
L'accélération de la pierre est $\vec{a}=\vec{g}$ pour les trois situations. Le signe de $\vec{g}$ dépendra de l'axe de référence. S'il est dirigé vers le haut, alors $a=-g=-9.81\,m/s^{2}$. S'il est dirigé vers le bas, $a=g=9.81\,m/s^{2}$
:::
::::

::::{admonition} Questions 2
:class: question
Un objet projeté vers le haut retombe sur Terre. C'est un mouvement unidimensionnel.
1. Quand sa vitesse est-elle nulle ?
2. Sa vitesse change-t-elle de direction ?
3. L'accélération due à la gravité a-t-elle le même signe à la montée qu'à la descente ?
:::{admonition} *réponse*
:class: dropdown questionsol
1. La vitesse est nulle au sommet de sa trajectoire, à $y_{max}$
2. Oui, dès que l'objet atteint sa hauteur maximale, il redescend, et sa vitesse change de signe.
3. Oui, l'accélération terrestre ne change jamais de signe une fis qu'on a fixé l'axe de référence.
:::
::::

::::{admonition} Questions 3
:class: question
Supposons que vous jetiez une pierre presque directement sur une noix de coco dans un palmier, et que la pierre manque en montant mais heurte la noix de coco en descendant. En négligeant la résistance de l'air, comment la vitesse de la roche, lorsqu'elle heurte la noix de coco en descendant, se compare-t-elle à ce qu'elle aurait été si elle avait heurté la noix de coco en montant ? La pierre a-t-elle plus de chance de faire tomber la noix de coco en montant ou en descendant ? Expliquez.
:::{admonition} *réponse*
:class: dropdown questionsol
La valeur absolue de la vitesse est la même, mais ces deux vitesses n'ont pas la même direction. Ce qui ralentit la pierre à la montée ($-g$) est équivalent à ce qui accélère la pierre à la descente ($+g$).\
En redescendant, le poids de la pierre va aider a faire lâcher la noix de coco (en plus du choc).
:::
::::

::::{admonition} Questions 4
:class: question
1. Si un objet est projeté vers le haut et que la résistance de l'air est négligeable, est-ce que sa vitesse, lorsqu'il revient au point de départ, est la même qu'au moment où il a été lancé ?
2. Si la résistance de l'air n'était pas négligeable, comment sa vitesse au retour se comparerait-elle à sa vitesse initiale ? Comment la hauteur maximale atteinte par l'objet serait-elle affectée ?
:::{admonition} *réponse*
:class: dropdown questionsol
1. Oui (voir la réponse à la question 3)
2. La vitesse serait plus petite, car l'objet est ralentit à la montée et à la descente par l'air. La hauteur maximale atteinte par l'objet est alors également plus petite.
:::
::::

:::::{admonition} Questions 5
:class: question
La sévérité d'une chute dépend de votre vitesse lorsque vous heurtez le sol. Tous les facteurs sauf l'accélération due à la gravité étant les mêmes, de combien de fois plus haut l'impacte d'une chute sur la Lune est-elle identique à celle sur la Terre (l'accélération gravitationnelle sur la Lune est environ $1/6$ de celle de la Terre) ?
::::{admonition} *réponse*
:class: dropdown questionsol
Comme la vitesse d'impact est importante, on cherche la hauteur de la chute $h_{L}$ sur la Lune qui donne la même vitesse finale à l'impact que sur la Terre. L'inconnue est le temps de chute des objets, qui varie entre la Terre et la Lune.\
On utilise donc l'équation $v^{2}-v_{0}^{2}=2g\cdot (h-h_{0})$ avec un axe de référence dirigé vers le bas ($g$ et $v$ sont positives).\
Comme on *lâche* l'objet, $v_{0}=0$ et avec $h_{0}=0$, $h-h_{0}=h$.\
Ce qui nous donne $v^{2}=2g\cdot h$ et donc :
- Sur la Terre : $v_{T}^{2}=2g\cdot h_{T}$
- Sur la Lune : $v_{L}^{2}=2g_{L}\cdot h_{L}=2(\dfrac{1}{6}g)\cdot h_{L}$

Comme on veut que $v_{T}=v_{L}$, et donc $v_{T}^{2}=v_{L}^{2}$ on obtient:
:::{math}
\begin{align*}
2gh_{T}  &=2\dfrac{1}{6}gh_{L}\\
h_{T}  &=\dfrac{1}{6}h_{L}
\end{align*}
:::
Ce qui nous donne finalement : $h_{L}=6\cdot h_{T}$\
Il faudrait tomber de $6$ fois plus haut sur la Lune pour avoir le même impact que sur la Terre.
::::
:::::

:::::{admonition} Questions 6
:class: question
Combien de fois plus haut un astronaute pourrait-il sauter sur la Lune que sur la Terre si sa vitesse de décollage est la même aux deux endroits (l'accélération gravitationnelle sur la Lune est d'environ $1/6$ de $g$ sur Terre) ?
::::{admonition} *réponse*
:class: dropdown questionsol
On cherche la hauteur du saut $h_{L}$ sur la Lune avec la même vitesse initiale que sur la Terre. L'inconnue est le temps du saut, qui varie entre la Terre et la Lune.\
On utilise donc l'équation $v^{2}-v_{0}^{2}=2g\cdot (h-h_{0})$ avec un axe de référence dirigé vers le haut ($g$ est négative et $v_{0}$ positive).\
Comme on *saute jusqu'à la hauteur maximale*, la vitesse au sommet est nulle $v=0$. Avec $h_{0}=0$, $h-h_{0}=h$.\
Ce qui nous donne $0-v_{0}^{2}=2(-g)\cdot h$ et donc :
- Sur la Terre : $0-v_{0,T}^{2}=2(-g)\cdot h_{T}$
- Sur la Lune : $0-v_{0,L}^{2}=2(-g_{L})\cdot h_{L}=2(-\dfrac{1}{6}g)\cdot h_{L}$

Comme on sait que $v_{0,T}=v_{0,L}$, et donc $v_{0,T}^{2}=v_{0,L}^{2}$, on obtient :
:::{math}
\begin{align*}
-2g\cdot h_{T}  &=-2\dfrac{1}{6}g\cdot h_{L}\\
h_{T}  &=\dfrac{1}{6}h_{L}
\end{align*}
:::
Ce qui nous donne finalement : $h_{L}=6\cdot h_{T}$\
L'astronaute peut sauter $6$ fois plus haut sur la Lune que sur la Terre.
::::
:::::
