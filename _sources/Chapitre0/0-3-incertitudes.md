# Erreurs & incertitudes
La physique travaille continuellement avec des approximations. Une des raisons en est que toute mesure d'une grandeur quelconque est nécessairement entachée d'erreur. Il est impossible d'effectuer des mesures rigoureusement exactes.

Pour prendre conscience du degré d'approximation avec lequel on travaille, on fait l'estimation des erreurs qui peuvent avoir été commises dans les diverses mesures et on calcule leurs conséquences dans les résultats obtenus. Ceci constitue le calcul d'erreur, ou calcul d'incertitude.

## Erreurs
Selon le sens générale du mot, une erreur est toujours en relation avec quelque chose de juste ou de vrai, ou qui est considéré comme tel. Il en est de même en physique.E

### Erreur absolue
Par définition `l'erreur absolue` d'une grandeur mesurée est l'écart qui sépare la valeur expérimentale de la valeur que l'on a de bonne raison de considérer comme vraie. Prenons par exemple la vitesse de la lumière dans le vide. La valeur considérée actuellement comme vraie est :
:::{math}
c=299'792\,km/s
:::
Si un expérimentateur trouve, lors d'une mesure,
:::{math}
c_{exp}=305'000\,km/s
:::
on dit que l'erreur absolue de son résultat est :
:::{math}
\Delta c=\lvert c-c_{exp}\rvert=5'208\,km/s
:::

### Erreur relative
Par définition `l'erreur relative` est le quotient de l'erreur absolue à la valeur vraie :
:::{math}
\Delta c_{\,\%}=\dfrac{\Delta c}{c}=\dfrac{5208\,km/s}{305000\,km/s}=0.0174=1.7\,\%
:::

L'erreur relative n'a pas d'unité ; elle nous indique la qualité (l'exactitude) du résultat obtenu. Elle s'exprime généralement en $\%$ (pour cent).

On voit clairement qu'il n'est possible de parler d'erreur que si l'on a à disposition une valeur de référence que l'on peut considérer comme vraie.

## Incertitudes
Lors de la plupart des mesures physiques, on ne possède pas de valeur de référence, comme celle dont nous venons de parler. Lorsqu'on mesure la distance de deux points, ou l'intervalle de temps qui sépare deux événements, ou la masse d'un objet, on ne sait pas quelle est la valeur exacte de la grandeur mesurée. On ne dispose que de la valeur expérimentale. Néanmoins, par une critique objective des moyens utilisés pour faire la mesure, on peut se faire une idée de l'*erreur* maximale qu'on peut avoir commise, *erreur* que l'on appelle de façon plus appropriée incertitude.

### Incertitude absolue
L'indication complète du résultat d'une mesure physique comporte la valeur qu'on estime la plus probable et l'intervalle à l'intérieur duquel on est à peu près certain que se situe la vraie valeur. La valeur la plus probable est en général le centre de cet intervalle. La demi-longueur de celui-ci est appelée `incertitude absolue` de la mesure.

Ainsi, si l'on désigne par $x$ la valeur la plus probable de la grandeur mesurée $G$, par $x_{0}$ la vraie valeur (qui nous est inconnue) et par $\Delta x$ l'incertitude absolue, on a :
:::{math}
x-\Delta x\le x_{0}\le x+\Delta x
:::
Sous une forme condensée, le résultat de la mesure s'écrit :
:::{math}
G=x\pm \Delta x
:::

:::{admonition} Exemples
:class: exores
1. La longueur d'un objet est de $153\pm 1\,mm$. Cela signifie qu'avec une incertitude absolue $\Delta l=1\,mm$, la valeur exacte est comprise entre $152\,mm$ et $154\,mm$.
2. La température d'un local est de $22\pm 1°C$. Ici l'incertitude absolue $\Delta\Theta=1°C$, c'est-à-dire que l'on garantit que la température n'est pas inférieure à $21°C$ ni supérieure à $23°C$.
:::

> **Remarque :**\
> Lorsqu'on mesure une grandeur (longueur, temps, masse, température,...), on peut considérer *pour simplifier* que l'incertitude absolue correspond à *la plus petite graduation* de l'instrument de mesure utilisé.

### Incertitude relative
L'incertitude absolue, lorsqu'elle est considérée seule, n'indique rien sur la qualité de la mesure. Pour juger de cette qualité, il faut comparer l'incertitude absolue à la grandeur mesurée. Le rapport de ces grandeurs est appelé `incertitude relative`.
:::{math}
\Delta x_{\,\%}=\dfrac{\Delta x}{x}
:::
Comme pour l'erreur relative, l'incertitude relative est un nombre pur (sans unité), que l'on exprime en $\%$.

## Calcul d'incertitudes 
Les mesures effectuées en physique sont le plus souvent indirectes, c'est-à-dire que le résultat final d'une expérience ne consiste pas en la mesure (répétée ou non) d'un seul paramètre, mais de plusieurs grandeurs qui, liées par une loi physique, conduisent au résultat cherché. Chacune de ces grandeurs a une certaine incertitude; le résultat de l'expérience en comportera aussi une qui dépend de toutes les incertitudes individuelles. C'est le principe de la `propagation des incertitudes`. Il est alors intéressant de savoir de quelle manière les incertitudes des mesures se répercutent sur les incertitudes des résultats.

L'application de la propagation des incertitudes est particulièrement simple dans les cas particuliers suivants, souvent rencontrés en pratique :

### Addition et soustraction
Si la grandeur cherchée $R$ est la somme de $2$ mesures $A$ et $B$ :
:::{math}
R=A+B
:::
Dans ce cas l'incertitude sur le résultat est :
:::{math}
\Delta R=\Delta A+\Delta B
:::
Il en est de même pour : $R=A-B$

::::{admonition} A retenir !
:class: formule
**L'incertitude absolue sur une somme ou une différence est la somme des incertitudes absolues de chaque terme.**
:::{math}
\Delta R=\Delta A+\Delta B
:::
::::

::::{admonition} Exemples
:class: exores
Un récipient a une masse $m=50\pm 1\,g$. Rempli d'eau, sa masse vaut : $M=200\pm 1\,g$.\
La masse d'eau qu'il contient est donc :
:::{math}
m_{eau}=M-m
:::
En appliquant la règle ci-dessus : $\Delta m_{eau}=\Delta  M +\Delta m=1+1=2\,g$\
il s'ensuit que : $m_{eau}=150\pm 2\,g$
::::

### Multiplication, division et puissances
Si la grandeur cherchée $R$ est le résultat d'un calcul de produit ou de quotient de mesures :
:::{math}
R=\dfrac{A\cdot B}{C}
:::
où $A$, $B$ et $C$ sont des grandeurs que l'on mesure.

Dans ce cas l'incertitude relative sur le résultat est :
:::{math}
\dfrac{\Delta R}{R}=\dfrac{\Delta A}{A}+\dfrac{\Delta B}{B}+\dfrac{\Delta C}{C}
:::

::::{admonition} A retenir !
:class: formule
**L'incertitude relative sur un produit ou un quotient est la somme des incertitude relatives de chaque terme.**
:::{math}
\dfrac{\Delta R}{R}=\dfrac{\Delta A}{A}+\dfrac{\Delta B}{B}+\dfrac{\Delta C}{C}
:::
::::

Si la grandeur cherchée $R$ est le résultat d'un calcul de produit de puissance comme :
:::{math}
R=\dfrac{A^{\alpha}\cdot B^{\beta}}{C^{\gamma}}
:::
où $A$, $B$ et $C$ sont des grandeurs que l'on mesure.

Dans ce cas l'incertitude relative sur le résultat est :
:::{math}
\dfrac{\Delta R}{R}=\lvert\alpha\rvert\cdot\dfrac{\Delta A}{A}+\lvert\beta\rvert\cdot\dfrac{\Delta B}{B}+\lvert\gamma\rvert\cdot\dfrac{\Delta C}{C}
:::

::::{admonition} A retenir !
:class: formule
**L'incertitude relative sur un produit ou un quotient de puissance est la somme des incertitude relatives de chaque terme multipliée par la valeur absolue de leur puissance.**
:::{math}
\dfrac{\Delta R}{R}=\lvert\alpha\rvert\cdot\dfrac{\Delta A}{A}+\lvert\beta\rvert\cdot\dfrac{\Delta B}{B}+\lvert\gamma\rvert\cdot\dfrac{\Delta C}{C}
:::
::::

::::{admonition} Exemple
:class: exores
La période d'oscillation $T$ d'un pendule simple dépend de la longueur $l$ du pendule :
:::{math}
T=\sqrt{2\pi\dfrac{l}{g}}
:::

En mesurant la longueur du pendule et sa période (donc ici deux mesures), on obtient de façon simple l'accélération de la pesanteur $g$ :
:::{math}
g=\dfrac{4\pi^{2}\cdot l}{T^{2}}
:::

L'incertitude sur $g$ est obtenue à partir des incertitudes sur $l$ et $T$ par :
:::{math}
\dfrac{\Delta g}{g}=\dfrac{\Delta l}{l}+2\dfrac{\Delta T}{T}
:::
donc : 
:::{math}
\Delta g=(\dfrac{\Delta l}{l}+2\dfrac{\Delta T}{T})\cdot g=(\dfrac{\Delta l}{l}+2\dfrac{\Delta T}{T})\cdot \dfrac{4\pi^{2}\cdot l}{T^{2}}
:::

Ce qui donne finalement :
:::{math}
\Delta g=4\pi^{2}(\dfrac{\Delta l}{T^{2}}+\dfrac{2\cdot l\cdot\Delta T}{T^{3}})
:::
::::

## Loi physique à vérifier expérimentalement
Dans de nombreuses expériences effectuées en physique, la détermination d'une grandeur se réalise en vérifiant une loi faisant intervenir la grandeur en question. La vérification expérimentale d'une loi théorique reliant plusieurs grandeurs physiques peut se faire simplement en s'efforçant de mettre la loi sous *une forme linéaire* par un changement de variable approprié.

> *Rappel:\
> la forme analytique d'une droite est $y = p\cdot x+h$\
> avec $p$ la pente de la droite et $h$ l'ordonnée à l'origine.*

::::{admonition} Exemple
:class: exores
Dans le pendule simple, la période d'oscillation $T$ dépend de la longueur du pendule $l$ de la manière suivante :
:::{math}
T=\sqrt{2\pi\dfrac{l}{g}}
:::
On peut décrire ce phénomène par une relation linéaire en représentant $T^{2}$ en fonction de $l$ :
:::{math}
T^{2}=4\pi^{2}\dfrac{l}{g}=\dfrac{4\pi^{2}}{g}\cdot l
:::
::::

Les points de mesures ($x_{i}, y_{i}$) sont alors reportés avec leurs barres d'incertitudes sur un système d'axes orthogonaux, ce qui permet de reconnaître immédiatement si la loi est vérifiée en examinant l'alignement des points expérimentaux (**FIGURE A METTRE**). Les barres d'erreur consistent en des segments horizontaux et verticaux de longueur $\Delta x_{i}$ et $\Delta y_{i}$ portés de part et d'autre de chaque point ($x_{i}, y_{i}$). On voit qu'il est de première importance de reporter les points de mesures avec leur domaine d'erreur préalablement à toute discussion concernant la validité de la loi à vérifier.

### Régression linéaire
Pour vérifier la linéarité d'une relation, on cherche à faire passer la **meilleure droite** (appelée aussi *droite de régression*) par tous les points de mesure (avec leurs barres d'erreur). Les coefficients de la droite de régression (pente $p$ et ordonnée à l'origine $h$) peuvent être obtenus par calcul avec un tableur ou autre logiciel dédié. Il faut toutefois noter que la régression linéaire ainsi obtenue (par exemple en utilisant une courbe de tendance standard du logiciel Excel) ne tient pas compte des incertitudes sur les points de mesures, ce qui fait qu'on point connu avec une grande précision a le même poids dans le calcul de la droite qu'un point entaché d'une grande imprécision. De plus, il serait plus correct de considérer les distances absolues entre les points et la droite plutôt que les distances verticales qui sont plus faciles à traiter. Pour ces raisons, les régressions linéaires seront effectuées aux TP de Physique avec le logiciel `LoggerPro` et non pas avec l'outil standard de courbe de tendance dans Excel.\
Cela permettra en particulier de déterminer les incertitudes $\Delta p$ et $\Delta h$ sur les paramètres de la droite.

Dans tous les cas, le résultat est indiqué sous la forme $p=p_{0}\pm\Delta p$