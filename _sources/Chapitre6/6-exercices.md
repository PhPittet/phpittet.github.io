# Exercices

::::{admonition} Exercice 1
:class: exohome
Un sprinter de classe olympique démarre une course avec une accélération de ($4.50\,m/s^{2}$)
1. Quelle est sa vitesse $2.40\,s$ plus tard ?
2. Tracez un graphique de sa position en fonction du temps pour cette période.
:::{admonition} *solution*
:class: dropdown exohomesol
begin{center}
includegraphics[scale=0.5]{CI-ExercicesAcceleration1.jpg} %---- ou .pdf .png
end{center}
1. $\vec{v}=\vec{a}\\cdot t+\vec{v_{0}}=4.50\,m/s^{2}\cdot 2.40,s+0\,m/s=10.8\,m/s$
2. begin{center}
includegraphics[scale=0.5]{CI-ExercicesAccelerationSol1.jpg} %---- ou .pdf .png
end{center}
:::
::::

::::{admonition} Exercice 2
:class: exohome
Une balle bien lancée est attrapée dans un gant bien rembourré. Si la décélération de la balle est de $a=2\cdot 10^{4}\,m/s^{2}$, et que $1.85,ms$ ($1,ms =10^{-3}\,s$) s'écoule entre le moment où la balle touche le gant pour la première fois jusqu'à ce qu'elle s'arrête, quelle était la vitesse initiale de la balle ?
:::{admonition} *solution*
:class: dropdown exohomesol
begin{center}
includegraphics[scale=0.5]{CI-ExercicesAcceleration2.jpg} %---- ou .pdf .png
end{center}
Comme $\vec{v}=\vec{a}\cdot t+\vec{v_{0}}$, alors $\vec{v_{0}}=\vec{v}-\vec{a}\cdot t=0-(-2\cdot 10^{4}\,m/s^{2})\cdot 1.85\cdot 10^{-3},s=37.0\,m/s$. 
:::
::::

::::{admonition} Exercice 3
:class: exohome
Une balle dans une arme à feu est accélérée de la chambre de tir à l'extrémité du canon à un taux moyen de $6.20\cdot 10^{5}\,m/s^{2}$ pour $8.10\cdot 10^{-4}\,s$. Quelle est sa vitesse à la sortie du canon (c'est-à-dire sa vitesse finale) ?
:::{admonition} *solution*
:class: dropdown exohomesol
begin{center}
includegraphics[scale=0.5]{CI-ExercicesAcceleration3.jpg} %---- ou .pdf .png
end{center}
$\vec{v}=\vec{a}\cdot t+\vec{v_{0}}=6.20\cdot 10^{5}\,m/s^{2}\cdot 8.10\cdot 10^{-4},s+0=502\,m/s=1'800\,km/h$
:::
::::

::::{admonition} Exercice 4
:class: exohome
1. Un train régional accélère à une vitesse de $1.35\,m/s^{2}$. Combien de temps faut-il pour atteindre sa vitesse maximale de $80.0\,km/h$, en partant du repos ?
2. Le même train décélère habituellement à une vitesse de $1.65\,m/s^{2}$. Combien de temps faut-il pour s'arrêter de sa vitesse maximale ?
3. En cas d'urgence, le train peut décélérer plus rapidement et s'arrêter de $80.0\,km/h$ en $8.30\,s$. Quelle est sa décélération d'urgence en $m/s^{2}$ ?
:::{admonition} *solution*
:class: dropdown exohomesol
begin{center}
includegraphics[scale=0.4]{CI-ExercicesAcceleration4.png} %---- ou .pdf .png
end{center}
1. Premièrement: $v_{2}=80\,km/h\div 3.6=22.2\,m/s$.
Ensuite, on sait que $\vec{a}=\dfrac{\vec{v}-\vec{v_{0}}}{t}$ et $\vec{v_{0}}=0\,m/s$, alors $t=\dfrac{\vec{v}}{\vec{a}}=\dfrac{22.2\,m/s}{1.35\,m/s^{2}}=16.5\,s$
2. Maintenant $v_{0}=22.2\,m/s$ et $v=0\,m/s$. Donc $t=\dfrac{\vec{-v_{0}}}{\vec{a}}=\dfrac{-22.2\,m/s}{-1.65\,m/s^{2}}=13.5\,s$
3. En cas d'urgence $\vec{a}=\dfrac{\vec{v}-\vec{v_{0}}}{t}=\dfrac{0\,m/s-22.2\,m/s}{8.30,s}=-2.68\,m/s^{2}$
:::
::::

::::{admonition} Exercice 5
:class: exohome
En entrant dans une autoroute, une voiture accélère depuis le repos à un taux de $2.40\,m/s^{2}$ pendant $12.0\,s$.
1. Faites un croquis de la situation.
2. Énumérez les éléments connus de ce problème.
3. Quelle est la distance parcourue par la voiture dans ces $12.0\,s$ ? Pour résoudre cette partie, identifiez d'abord l'inconnu, puis expliquez comment vous avez choisi l'équation appropriée à résoudre. Après avoir choisi l'équation, montrez vos étapes de résolution de l'inconnu, vérifiez vos unités et discutez si la réponse est raisonnable.
4. Quelle est la vitesse finale de la voiture ? Résolvez cette inconnue de la même manière que dans la partie 3., en montrant toutes les étapes explicitement.
:::{admonition} *solution*
:class: dropdown exohomesol
1.begin{center}
includegraphics[scale=0.5]{CI-ExercicesAcceleration5.jpg} %---- ou .pdf .png
end{center}
2. On connait: $v_{0}=0\,m/s$, $a=2.40\,m/s^{2}$ et $t=12.0\,s$
3. On cherche $\vec{Delta x}$. On utilise l'équation qui contient les valeurs connues en 2. et l'inconnue; on utilise $\vec{Delta x}=frac{1}{2}\vec{a}\cdot t^{2}+\vec{v_{0}}\cdot t$, ce qui donne:
begin{align*}
\vec{Delta x}	&=frac{1}{2}\vec{a}\cdot t^{2}+\vec{v_{0}}\cdot t
\vec{Delta x}	&=frac{1}{2}2.40\,m/s^{2}\cdot (12.0,s)^{2}+0\,m/s\cdot 12,s
\vec{Delta x}	&=frac{1}{2}2.4\cdot 144,m=172.8,m
end{align*}
L'ordre de grandeur de la réponse semble raisonnable.
4. On cherche $v$. On utilise l'équation qui contient les valeurs connues en 2. et l'inconnue; on utilise $\vec{v}=\vec{a}\cdot t+\vec{v_{0}}$, ce qui donne:
begin{align*}
\vec{v}	&=\vec{a}\cdot t+\vec{v_{0}}
\vec{v}	&=2.40\,m/s^{2}\cdot 12.0,s+0\,m/s
\vec{v}	&=2.4\cdot 12\,m/s=28.8\,m/s=104\,km/h
end{align*}
Ici aussi, l'ordre de grandeur de la réponse semble raisonnable.
:::
::::

::::{admonition} Exercice 6
:class: exohome
À la fin d'une course de vélo, un coureur décélère à partir d'une vitesse de $9.00\,m/s$ à un taux de $2.00\,m/s^{2}$.
1. Quelle distance parcourra-t-il dans les 5 prochaines $s$ ?
2. Quelle est sa vitesse à ce moment là ?
3. Évaluez le résultat. Est-ce que ça fait du sens ?
:::{admonition} *solution*
:class: dropdown exohomesol
begin{center}
includegraphics[scale=0.5]{CI-ExercicesAcceleration6.jpg} %---- ou .pdf .png
end{center}
1. $\vec{Delta x}=frac{1}{2}\vec{a}\cdot t^{2}+\vec{v_{0}}\cdot t=frac{1}{2}(-2.00\,m/s^{2})\cdot (5,s)^{2}+9.00\,m/s\cdot 5,s=20\,m$
2.  $\vec{v}=\vec{a}\cdot t+\vec{v_{0}}=(-2.00\,m/s^{2})\cdot 5,s+9.00\,m/s=-1\,m/s$ (!!!!!)
3. Le signe négatif indique que le coureur cycliste recule (!). Cela n'a pas de sens, car une fois arrêter, il ne bouge plus. Le problème vient des $5.0\,s$, car il suffit juste de $t=frac{Delta v}{a}=frac{9.00\,m/s}{2.00\,m/s^{2}}=4.5\,s$ au cycliste pour s'arrêter. De $t=4.5\,s$ à $t=5.0\,s$ le cycliste reste immobile (et n'a donc plus d'accélération). On doit donc reprendre et découper le problème jusqu'à un temps de $t=4.5\,s$. Ce qui nous donne pour 1. $\vec{Delta x}=20.25\,m$ et 2. $\vec{v}=0\,m/s$. On remarque que la déplacement $\vec{Delta x}$ est plus important, ce qui peut semble étrange. Cela vient du fais qu'on mesure $\vec{Delta x}$, le déplacement, et non la distance parcourue. Avec un temps erroné de $5.0\,s$, on a ajouter le moment où le cycliste og reculaitfg{} pendant $0.50\,s$ sur une distance de $0.25\,m$
:::
::::

::::{admonition} Exercice 7
:class: exohome
(Application réelle) Le sang est accéléré du repos à $30.0,cm/s$ sur une distance de $1.80,cm$ par le ventricule gauche du cœur.
1. Faites un croquis de la situation.
2. Énumérez les éléments connus de ce problème.
3. Combien de temps dure l'accélération ? Pour résoudre cette partie, identifiez d'abord l'inconnu, puis expliquez comment vous avez choisi l'équation appropriée à résoudre. Après avoir choisi l'équation, montrez vos étapes de résolution de l'inconnu, en vérifiant vos unités.
4. La réponse est-elle raisonnable par rapport à la durée d'un battement de cœur ?
newpage
:::{admonition} *solution*
:class: dropdown exohomesol
1.begin{center}
includegraphics[scale=0.5]{CI-ExercicesAcceleration7.jpg} %---- ou .pdf .png
end{center}
2. On connait: $v_{0}=0\,m/s$, $v=30,cm/s=0.30\,m/s$ et $Delta x=1.80,cm=1.8\cdot 10^{-2}\,m$
3. On cherche $t$. On utilise l'équation qui contient les valeurs connues en 2. et l'inconnue; on utilise $\vec{Delta x}=\dfrac{\vec{v}+\vec{v_{0}}}{2}\cdot t$, ce qui donne:
begin{align*}
\vec{Delta x}	&=\dfrac{\vec{v}+\vec{v_{0}}}{2}\cdot t
\\Rightarrowquad t	&=\dfrac{\vec{Delta x}}{\left(\dfrac{\vec{v}+\vec{v_{0}}}{2}\right)}
t	&=\dfrac{2\vec{Delta x}}{\vec{v}+\vec{v_{0}}}
t	&=\dfrac{2\cdot 1.8\cdot 10^{-2},m}{(0.30\,m/s+0.0\,m/s)}
t	&=0.12,s
end{align*}
L'ordre de grandeur de la réponse semble raisonnable. En moyenne, l'être humain est à 60 pulsations par minute, soit une pulsation par seconde. Chaque pulsation se compose de 4 phases (remplissage/vidage des ventricules gauche et droite), donc $0.12\,s$ semble raisonnable.
:::
::::

::::{admonition} Exercice 8
:class: exohome
Lors d'un tir, un joueur de hockey accélère la rondelle d'une vitesse de $8.00\,m/s$ à $40.0\,m/s$ dans la même direction. Si ce coup prend $3.33\cdot 10^{-2}\,s$, calculez la distance sur laquelle la rondelle accélère.
:::{admonition} *solution*
:class: dropdown exohomesol
begin{center}
includegraphics[scale=0.5]{CI-ExercicesAcceleration8.jpg} %---- ou .pdf .png
end{center}
On utilise $\vec{Delta x}=\dfrac{\vec{v}+\vec{v_{0}}}{2}\cdot t$, ce qui donne: $\vec{Delta x}=\dfrac{40.0\,m/s+8.00\,m/s}{2}\cdot 3.33\cdot 10^{-2},s=0.799,m=79.9,cm$
:::
::::

::::{admonition} Exercice 9
:class: exohome
Une moto puissante peut accélérer du repos à $26.8\,m/s$ ($100\,km/h$) en seulement $3.90\,s$.
1. Quelle est son accélération moyenne ?
2. Quelle est la distance parcourue pendant cette période ?
begin{solution}begin{center}
includegraphics[scale=0.5]{CI-ExercicesAcceleration9.jpg} %---- ou .pdf .png
end{center}
1. $\vec{a}=\dfrac{\vec{Delta v}}{t}=\dfrac{26.8\,m/s}{3.90,s}=6.8718\,m/s^{2}=6.87\,m/s^{2}$
2. $\vec{Delta x}=\dfrac{\vec{v}+\vec{v_{0}}}{2}\cdot t=\dfrac{26.8\,m/s+0\,m/s}{2}\cdot 3.90,s=52.3\,m$
On obtient le même résultat avec $\vec{Delta x}=frac{1}{2}\vec{a}t^{2}+\vec{v_{0}}t=frac{1}{2}\cdot (6.8718\,m/s^{2})\cdot (3.90\,m/s)^{2}=52.3\,m$
(on fera attention à ne pas prendre une valeur arrondie pour $a$)
:::
::::


::::{admonition} Exercice 10
:class: exohome
Les trains de marchandises ne peuvent produire que des accélérations et des décélérations relativement faibles.
1. Quelle est la vitesse finale d'un train de marchandises qui accélère à un taux de $0.0500\,m/s^{2}$ pendant $8.00,min$, en commençant par une vitesse initiale de $4.00\,m/s$ ?
2. Si le train peut ralentir avec un taux de $0.550\,m/s^{2}$, combien de temps faudra-t-il pour s'arrêter à cette vitesse ?
3. Quelle distance parcourra-t-il dans chaque cas ?
begin{solution}begin{center}
includegraphics[scale=0.5]{CI-ExercicesAcceleration10.png} %---- ou .pdf .png
end{center}
1. $\vec{v}=\vec{a}t+\vec{v_{0}}=0.0500\,m/s^{2}\cdot (8.00,min\cdot 60,s)+4.00\,m/s=28.0\,m/s$
2. $t=\dfrac{\vec{v}-\vec{v_{0}}}{\vec{a}}=\dfrac{0\,m/s-28.0\,m/s}{-0.550\,m/s^{2}}=50.909,s=50.9\,s$
3. pour 1.: $\vec{Delta x}=\dfrac{\vec{v}+\vec{v_{0}}}{2}\cdot t=\dfrac{28\,m/s+4\,m/s}{2}\cdot (8.00,min\cdot 60,s)=7'6808,m=7.68,km$
pour 2.: $\vec{Delta x}=\dfrac{\vec{v}+\vec{v_{0}}}{2}\cdot t=\dfrac{0\,m/s+28\,m/s}{2}\cdot 50.909,s=713\,m$
:::
::::

::::{admonition} Exercice 11
:class: exohome
Un obus de feu d'artifice est accéléré du repos à une vitesse de $65\,m/s$ sur une distance de $0.250\,m$.
1. Combien de temps l'accélération a-t-elle durée ?
2. Calculez l'accélération.
:::{admonition} *solution*
:class: dropdown exohomesol
1. $\vec{Delta x}=\dfrac{\vec{v}+\vec{v_{0}}}{2}\cdot t$ Donc $t=\dfrac{2\vec{Delta x}}{\vec{v}+\vec{v_{0}}}=\dfrac{2\cdot 0.250,m}{65\,m/s+0\,m/s}=0.0076923,s=7.69,ms$
2. $\vec{a}=\dfrac{\vec{Delta v}}{t}=\dfrac{65\,m/s}{0.0076923,s}=8'450\,m/s^{2}$ ou bien
$\vec{v}^2-\vec{v_{0}}^{2}=2\vec{a}\vec{Delta x}$ $\Rightarrow$ $\vec{a}=\dfrac{\vec{v}^2-\vec{v_{0}}^{2}}{2\vec{Delta x}}=\dfrac{(65\,m/s)^2}{2\cdot 0.250,m}=8'450\,m/s^{2}$
:::
::::

::::{admonition} Exercice 12
:class: exohome
Un cygne sur un lac s'envole en battant des ailes et en courant au-dessus de l'eau.
1. Si le cygne doit atteindre une vitesse de $6.00\,m/s$ pour décoller et qu'il accélère depuis le repos à un taux moyen de $0.350\,m/s^{2}$, quelle distance parcourra-t-il avant de prendre le vol ?
2. Combien de temps cela prend-il ?
:::{admonition} *solution*
:class: dropdown exohomesol
1. $\vec{v}^2-\vec{v_{0}}^{2}=2\vec{a}\vec{Delta x}$ $\Rightarrow$ $\vec{Delta x}=\dfrac{\vec{v}^2-\vec{v_{0}}^{2}}{2\vec{a}}=\dfrac{(6.00\,m/s)^2-(0\,m/s)^{2}}{2\cdot 0.350\,m/s^{2}}=51.4\,m$
2. $t=\dfrac{\vec{Delta v}}{\vec{a}}=\dfrac{6.00\,m/s}{0.350\,m/s^{2}}=17.1\,s$
:::
::::

::::{admonition} Exercice 13
:class: exohome
(Application réelle) Le cerveau d'un Pic vert est spécialement protégé contre les grandes décélérations par des attaches en forme de tendon à l'intérieur du crâne. En picorant sur un arbre, la tête du pic s'arrête depuis une vitesse initiale de $25.0\,km/h$ sur une distance de seulement $2.00,mm$.
1. Trouvez l'accélération en $m/s^{2}$ et en multiples de $g$ ($g=9.81\,m/s^{2}$).
2. Calculez le temps d'arrêt.
3. Les tendons berçant le cerveau s'étirent, ce qui rend sa distance d'arrêt de $4.50,mm$ (plus grande que la tête et, par conséquent, moins de décélération du cerveau). Quelle est la décélération du cerveau, exprimée en multiples de $g$ ?
:::{admonition} *solution*
:class: dropdown exohomesol
1. Premièrement: $25\,km/h\div 3.6=6.94\,m/s$ et on utilise $\vec{v}^2-\vec{v_{0}}^{2}=2\vec{a}\vec{Delta x}$
$\Rightarrow$ $\vec{a}=\dfrac{\vec{v}^2-\vec{v_{0}}^{2}}{2\vec{Delta x}}=\dfrac{(0\,m/s)^{2}-(6.94\,m/s)^2}{2\cdot 2.00\cdot 10^{-3},m}=\dfrac{-48.16}{4}\cdot 10^{3}\,m/s^{2}=-12'040\,m/s^{2}=-1'230\cdot g$
Le Pic vert est l'être vivant qui peut supporter la plus grand décélération.
2. $\vec{Delta x}=\dfrac{\vec{v}+\vec{v_{0}}}{2}\cdot t$ $\Rightarrow$ $t=\dfrac{2\vec{Delta x}}{\vec{v}+\vec{v_{0}}}=\dfrac{2\cdot 2.00\cdot 10^{-3},m}{0\,m/s+6.94\,m/s}=0.000576,s=576,mu s$
3. $\vec{a}=\dfrac{\vec{v}^2-\vec{v_{0}}^{2}}{2\vec{Delta x}}=\dfrac{(0\,m/s)^{2}-(6.94\,m/s)^2}{2\cdot 4.5\cdot 10^{-3},m}=\dfrac{-48.16}{9}\cdot 10^{3}\,m/s^{2}=-5'352\,m/s^{2}=-546\cdot g$
:::
::::

::::{admonition} Exercice 14
:class: exohome
Un footballeur imprudent entre en collision avec un poteau de but rembourré alors qu'il court à une vitesse de $7.50\,m/s$ et s'arrête complètement après avoir comprimé le rembourrage et son corps à $0.350\,m$.
1. Quelle est sa décélération ?
2. Combien de temps dure la collision ?
newpage
:::{admonition} *solution*
:class: dropdown exohomesol
1. $\vec{v}^2-\vec{v_{0}}^{2}=2\vec{a}\vec{Delta x}$ $\Rightarrow$ $\vec{a}=\dfrac{\vec{v}^2-\vec{v_{0}}^{2}}{2\vec{Delta x}}=\dfrac{(0\,m/s)^{2}-(7.50\,m/s)^2}{2\cdot 0.350,m}=\dfrac{-56.25}{0.7}\,m/s^{2}=-80.357\,m/s^{2}=-80.4\,m/s^{2}$
2. $t=\dfrac{\vec{Delta v}}{\vec{a}}=\dfrac{-7.50\,m/s}{-80.357\,m/s^{2}}=0.0933,s=93.3,ms$
:::
::::

::::{admonition} Exercice 15
:class: exohome
Au cours de la Seconde Guerre mondiale, il y a eu plusieurs cas signalés d'aviateurs qui ont sauté de leurs avions en flammes sans parachute pour échapper à une mort certaine. Certains sont tombés à environ $6'000$ mètres, et certains d'entre eux ont survécu, avec quelques blessures potentiellement mortelles. Pour ces pilotes chanceux, les branches d'arbres et les tas de neige au sol ont permis à leur décélération d'être relativement faible. Si nous supposons que la vitesse d'un pilote lors de l'impact était de $54\,m/s$, quelle a été sa décélération ? Supposons que les arbres et la neige l'ont arrêté sur une distance de $3.0\,m$.
:::{admonition} *solution*
:class: dropdown exohomesol
$\vec{a}=\dfrac{\vec{v}^2-\vec{v_{0}}^{2}}{2\vec{Delta x}}=\dfrac{(0\,m/s)^{2}-(54\,m/s)^2}{2\cdot 3.0,m}=\dfrac{-2916}{6}\,m/s^{2}=-486\,m/s^{2}$
:::
::::

::::{admonition} Exercice 16
:class: exohome
Prenons l'exemple d'un écureuil tombant d'un arbre au sol.
1. Si nous ignorons la résistance de l'air dans ce cas (uniquement pour le bien de ce problème), déterminez la vitesse d'un écureuil juste avant de toucher le sol, en supposant qu'il est tombé d'une hauteur de $3.0\,m$.
2. Si l'écureuil s'arrête à une distance de $2.0,cm$ en pliant ses membres, comparez sa décélération avec celle de l'aviateur dans le problème précédent.
:::{admonition} *solution*
:class: dropdown exohomesol
1. $\vec{a}=\vec{g}=9.81\,m/s^{2}$
$\vec{v}^2-\vec{v_{0}}^{2}=2\vec{g}\vec{Delta x}$ $\Rightarrow$ $v=\sqrt{2\vec{g}\vec{Delta x}-\vec{v_{0}}^{2}}=\sqrt{2\cdot 9.81\,m/s^{2}\cdot 3.0,m-(0\,m/s)^{2}}=\sqrt{58.86}=7.7\,m/s=28\,km/h$
2. $\vec{a}=\dfrac{\vec{v}^2-\vec{v_{0}}^{2}}{2\vec{Delta x}}=\dfrac{(0\,m/s)^{2}-(7.7\,m/s)^2}{2\cdot 2.0\cdot 10^{-2},m}=\dfrac{-58.86}{4.0\cdot 10^{-2}}\,m/s^{2}=-1471.5\,m/s^{2}=-1'470\,m/s^{2}$
La décélération de l'écureuil est 3 fois plus importante que celle de l'aviateur (!)
:::
::::

::::{admonition} Exercice 17
:class: exohome
Un train express passe par une gare. Il entre avec une vitesse initiale de $22.0\,m/s$ et décélère avec à un taux de $0.150\,m/s^{2}$ quand il passe. Le quai de la gare mesure $210\,m$ de long.
1. Combien de temps le bout du nez de la locomotive du train expresse passe-t-il dans la gare ?
2. Quelle est la vitesse du train lorsque le nez quitte la gare ?
3. Si le train mesure $130\,m$ de long, quand est-ce que l'extrémité du train quitte la gare ?
4. Quelle est la vitesse de l'extrémité du train à sa sortie ?
:::{admonition} *solution*
:class: dropdown exohomesol
1. $\vec{Delta x}=frac{1}{2}\vec{a}t^{2}+\vec{v_{0}}t=frac{1}{2}(-0.150\,m/s^{2})\cdot (t)^{2}+(22.0\,m/s)\cdot t=210\,m$
$\Rightarrow$ $-0.075\cdot t^{2}+22\cdot t-210=0$, qui a pour solutions:
$t=\dfrac{-22\Rightarrow\sqrt{22^2-[4\cdot (-0.075)\cdot (-210)]}}{-2\cdot 0.075}=\dfrac{-22\Rightarrow\sqrt{421}}{-0.15}=\dfrac{-22\Rightarrow 20.5}{-0.15}$
$\Rightarrow$ $t_{1}=10.0\,s$ et $t_{2}=283\,s$.
Le bout du nez du train met $10.0\,s$ pour traverser la gare.
2. $\vec{v}=\vec{a}t+\vec{v_{0}}=(-0.15\,m/s^{2}\cdot 10.0,s+22.0\,m/s=20.5\,m/s$
3. Quand le bout du nez du train entre en gare, l'extrémité du train se trouve à une distance de $210,m+130,m=330\,m$ de la fin du quai. Selon 1., on va obtenir: $-0.075\cdot t^{2}+22\cdot t-330=0$ qui a pour solution: $t_{1}=15.9\,s$ et $t_{2}=277\,s$.
L'extrémité du train sort de la gare $15.9\,s$ après l'entrée du train en gare.
4. à $t=15.9\,s$ le train a une vitesse de $\vec{v}=\vec{a}t+\vec{v_{0}}=-0.15\,m/s^{2}\cdot 15.9,s+22.0\,m/s=19.6\,m/s$
:::
::::

::::{admonition} Exercice 18
:class: exohome
Les dragsters peuvent atteindre une vitesse de pointe de $145\,m/s$ en seulement $4.45\,s$.
1. Calculez l'accélération moyenne pour un dragster.
2. Trouvez la vitesse finale d'un dragster en partant du repos et en accélérant avec la taux trouvé en 1. sur $402\,m$ (un quart de mille) sans utiliser aucune information sur le temps.
3. Pourquoi la vitesse finale est-elle supérieure à celle utilisée pour trouver l'accélération moyenne ? Astuce: vérifiez si l'hypothèse d'une accélération constante est valide pour un dragster. Sinon, discutez si l'accélération serait plus grande au début ou à la fin de la course et quel effet cela aurait sur la vitesse finale.
:::{admonition} *solution*
:class: dropdown exohomesol
1. $\vec{a}=\dfrac{\vec{Delta v}}{t}=\dfrac{145\,m/s}{4.45,s}=32.9\,m/s^{2}$
2. $\vec{v}^2-\vec{v_{0}}^{2}=2\vec{a}\vec{Delta x}$ $\Rightarrow$ $v=\sqrt{2\vec{a}\vec{Delta x}-\vec{v_{0}}^{2}}=\sqrt{2\cdot 32.9\,m/s^{2}\cdot 402,m-(0\,m/s)^{2}}=\sqrt{26'452}=163\,m/s=586\,km/h$
3. $145\,m/s$ en seulement $4.45\,s$ correspond à une distance de $322.6\,m$. L'accélération du dragster n'est certainement pas constante. L'accélération diminue; plus il va vite, moins il arrive à accélérer. En faisant l'hypothèse d'une accélération constante, on trouve forcement une vitesse plus grande que dans la réalité.
:::
::::

::::{admonition} Exercice 19
:class: exohome
Un coureur de vélo sprinte à la fin d'une course pour décrocher une victoire. Le coureur a une vitesse initiale de $11.5\,m/s$ et accélère avec un taux de $0.500\,m/s^{2}$ pendant $7.00\,s$.
1. Quelle est sa vitesse finale ?
2. Le coureur continue à cette vitesse jusqu'à la ligne d'arrivée. S'il était à $300\,m$ de la ligne d'arrivée lorsqu'il a commencé à accélérer, combien de temps a-t-il gagné ?
3. Un autre coureur avait $5.00\,m$ d'avance lorsque le vainqueur a commencé à accélérer, mais il n'a pas pu accélérer et a roulé à $11.8\,m/s$ jusqu'à la ligne d'arrivée. À quelle distance (en mètres et en secondes) de lui le vainqueur a-t-il terminé ?
:::{admonition} *solution*
:class: dropdown exohomesol
1. $\vec{v}=\vec{a}t+\vec{v_{0}}=0.500\,m/s^{2}\cdot 7.00,s+11.5\,m/s=15.0\,m/s$
2. Sans accélération: $t=\dfrac{\vec{Delta x}}{\vec{v_{moy}}}=\dfrac{300,m}{11.5\,m/s}=26.1\,s$
Avec accélération: $Delta \vec{x_{acc}}=frac{1}{2}\vec{a}\cdot t^{2}+\vec{v_{0}}\cdot t=frac{1}{2}\cdot (0.500\,m/s^{2})\cdot (7.00,s)^{2}+11.5\,m/s\cdot 7.00,s=92.75\,m$
Il lui reste donc $300,m-92.75,m=207.25\,m$ à faire à la vitesse de $15.0\,m/s$, c'est à dire:
$t_{15\,m/s}=\dfrac{\vec{Delta x}}{\vec{v_{moy}}}=\dfrac{207.25,m}{15.0\,m/s}=13.8\,s$
Il a donc gagné $26.1,s-(7.00,s+13.8,s)=26.1,s-20.8,s=5.30\,s$
3. $t_{2^{e},coureur}=\dfrac{\vec{Delta x}}{\vec{v_{moy}}}=\dfrac{300,m-5.00,m}{11.8\,m/s}=25.0\,s$
Le vainqueur finit donc $25.0-20.8=4.20\,s$ devant le 2$^{e}$
$4.20\,s$ à la vitesse de $11.8\,m/s$ correspond à une distance de $\vec{Delta x}=\vec{v_{moy}}\cdot t=11.8\,m/s\cdot 4.20,s=49.6\,m$
:::
::::

::::{admonition} Exercice 20
:class: exohome
En 1967, le Néo-Zélandais Burt Munro a établi le record du monde d'un moto, sur le désert de sel des Salt Flats de Bonneville dans l'Utah, avec une vitesse maximale de $295.45\,km/h$. Le parcours à sens unique était de $8.00,km$ de long. Les accélérations sont souvent décrits par le temps nécessaire pour atteindre $100\,km/h$ depuis le départ. Si ce temps était de $4.00\,s$ et que Burt accélérait à ce rythme jusqu'à ce qu'il atteigne sa vitesse maximale, combien de temps a-t-il fallu à Burt pour terminer le parcours ?
:::{admonition} *solution*
:class: dropdown exohomesol
$\vec{v_{max}}=295.45\,km/h\div 3.6=82.069\,m/s$, $\vec{v_{0}}=0\,m/s$ et $\vec{a}=frac{100\,km/h}{4.00,s}=frac{27.78\,m/s}{4.00,s}=6.94\,m/s^{2}$
$\vec{v_{max}}=\vec{a}\cdot t_{v_{max}}+\vec{v_{0}}$ $\Rightarrow$ $t_{v_{max}}=\dfrac{\vec{v_{max}}}{\vec{a}}=\dfrac{82.069\,m/s}{6.94\,m/s^{2}}=11.82\,s$ pour atteindre $v_{max}$.
Pendant ce temps, il a parcourut une distance de $\vec{Delta x}=frac{1}{2}\vec{a}t^{2}=frac{1}{2}(6.94\,m/s^{2})\cdot (11.82)^{2}=484.8\,m$
Il lui reste donc $8'000,m-484.4,m=7'515.2\,m$ à parcourir à la vitesse constante de $82.069\,m/s$, qu'il fait en $t=\dfrac{\vec{Delta x}}{\vec{v_{moy}}}=\dfrac{7'515.2,m}{82.069\,m/s}=91.57\,s$.
Le temps total du parcourt est donc de $11.82,s+91.57,s=103.4,s=1,min, 43.4\,s$
:::
::::

::::{admonition} Exercice 21
:class: exohome
1. Un record du monde a été établi pour le $100\,m$ masculin aux Jeux olympiques de 2008 à Beijing par Usain Bolt de la Jamaïque. Bolt a franchi la ligne d'arrivée avec un temps de $9.69\,s$. Si nous supposons que Bolt a accéléré pendant $3.00\,s$ pour atteindre sa vitesse maximale, et a maintenu cette vitesse pour le reste de la course, calculez sa vitesse maximale et son accélération.
2. Au cours des mêmes Jeux Olympiques, Bolt a également établi le record du monde du $200\,m$ avec un temps de $19.30\,s$. En utilisant les mêmes hypothèses que pour le $100\,m$, quelle était sa vitesse maximale pour cette course ?
:::{admonition} *solution*
:class: dropdown exohomesol
1.begin{center}
includegraphics[scale=0.5]{CI-ExercicesAccelerationBolt.jpg} %---- ou .pdf .png
end{center}
On écrit: $\vec{Delta x_{1}}=x_{1}-x_{0}$ et $\vec{Delta x_{2}}=x_{2}-x_{1}$, avec $\vec{Delta x_{1}}+\vec{Delta x_{2}}=100\,m$
1$^{ère}$ Partie:
$\vec{v_{max}}=\vec{a}t_{1}+\vec{v_{0}}=3\vec{a}$ $\Rightarrow$ $\vec{a}=frac{\vec{v_{max}}}{3}$ et
$\vec{Delta x_{1}}=\dfrac{\vec{v_{max}}+\vec{v_{0}}}{2}t=\dfrac{3}{2}\vec{v_{max}}=1.5\cdot\vec{v_{max}}$
2$^{e}$ Partie:
$\vec{Delta x_{2}}=\vec{v_{max}}\cdot Delta t_{2}=\vec{v_{max}}\cdot (t_{2}-t_{1})=6.69\cdot\vec{v_{max}}$
Au total:
$\vec{Delta x_{1}}+\vec{Delta x_{2}}=1.5\cdot\vec{v_{max}}+6.69\cdot\vec{v_{max}}=8.19\cdot\vec{v_{max}}=100\,m$
et donc: $\vec{v_{max}}=\dfrac{100,m}{8.19,s}=12.2\,m/s=44.0\,km/h$ et $\vec{a}=\dfrac{\vec{v_{max}}}{3}=4.07\,m/s^{2}$
2. Comme on a la même accélération pendant le même temps, on peut directement écrire:
$\vec{Delta x_{1}}+\vec{Delta x_{2}}=200\,m$
$\vec{a}=\dfrac{\vec{v_{max}}}{3}$
$\vec{Delta x_{1}}=1.5\cdot\vec{v_{max}}$
$\vec{Delta x_{2}}=\vec{v_{max}}\cdot (19.30,s-3.00,s)=16.30\cdot\vec{v_{max}}$
Ce qui nous donne: $\vec{Delta x_{1}}+\vec{Delta x_{2}}=1.5\cdot\vec{v_{max}}+16.30\cdot\vec{v_{max}}=17.80\cdot\vec{v_{max}}=200\,m$
et donc $\vec{v_{max}}=\dfrac{200,m}{17.80,s}=11.2\,m/s=40.4\,km/h$
:::
::::