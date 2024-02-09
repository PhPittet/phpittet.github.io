(chap:StrategieRes)=
# Stratégie de résolution
## Comment résoudre les problèmes avec les lois du mouvement de Newton
### Étape 1
Comme d'habitude, il faut d'abord identifier les principes physiques impliqués. Une fois qu'il est déterminé que les lois du mouvement de Newton sont impliquées (si le problème implique des forces), il est particulièrement important de dessiner une esquisse minutieuse de la situation . Une telle esquisse est représentée sur la {numref}`StratForce`(a). Ensuite, comme dans la {numref}`StratForce``(b), utilisez les flèches pour représenter toutes les forces, étiquetez-les soigneusement et faites correspondre leurs longueurs et directions aux forces qu'elles représentent (chaque fois que des informations suffisantes existent).
```{figure} figures/StratForce.jpg
:name: StratForce
:align: center
:width: 50%
*(a) Un croquis de Tarzan suspendu à une liane. (b) Les flèches sont utilisées pour représenter toutes les forces. $\vec{T}$ est la tension dans la liane au-dessus de Tarzan, $\vec{F}_{T}$ est la force qu'il exerce sur la liane, et $\vec{P}$ son poids. Toutes les autres forces, telles que le coup de coude d'une brise, sont supposées négligeables. (c) Supposons qu'on nous donne la masse de l'homme-singe et qu'on nous demande de trouver la tension dans la liane. Nous définissons ensuite le système d'intérêt comme indiqué et dessinons un diagramme des forces. $\vec{F}_{T}$ n'est plus montrée, car ce n'est pas une force agissant sur le système; plutôt, $\vec{F}_{T}$ agit sur le monde extérieur. (d) En ne montrant que les flèches, la méthode d'addition géométrique des vecteurs est utilisée. Il est évident que $\vec{T}=-\vec{P}$, si Tarzan est stationnaire. (crédit : openstax.org)*
```

### Étape 2
Identifiez ce qui doit être déterminé et ce qui est connu ou peut être déduit du problème tel qu'énoncé. Autrement dit, faites une liste des connus et des inconnus. Ensuite, déterminez soigneusement le système. Cette décision est une étape cruciale, car la deuxième loi de Newton n'implique que des forces extérieures. Une fois que le système a été identifié, il devient possible de déterminer quelles forces sont externes et lesquelles sont internes, une étape nécessaire pour employer la deuxième loi de Newton. (Voir la {numref}`StratForce`(c).) La troisième loi de Newton peut être utilisée pour identifier si des forces sont exercées entre les composants d'un système (interne) ou entre le système et quelque chose d'extérieur (externe). Comme illustré précédemment dans ce chapitre, le système dépend de la question à laquelle nous devons répondre. Ce choix devient plus facile avec la pratique. La compétence pour définir clairement les systèmes sera également bénéfique dans les chapitres suivants. Un diagramme montrant le système et toutes les forces externes est appelé un diagramme des forces. Seules les forces sont affichées sur les diagrammes des force, pas l'accélération ni la vitesse. Nous en avons dessiné plusieurs dans des exemples travaillés. La {numref}`StratForce`(c) montre un diagramme des forces pour le système. Notez qu'aucune force interne n'est représentée dans un diagramme des forces.

### Étape 3
Une fois qu'un diagramme des forces est dessiné, la deuxième loi de Newton peut être appliquée pour résoudre le problème. Ceci est fait dans la {numref}`StratForce`(d) pour une situation particulière. En général, une fois que les forces externes sont clairement identifiées dans les diagrammes des forces, il devrait être plus simple de les mettre sous forme d'équation et de résoudre l'inconnue, comme cela a été fait dans tous les exemples précédents. Si le problème est unidimensionnel, c'est-à-dire si toutes les forces sont parallèles, elles s'ajoutent comme des scalaires. Si le problème est bidimensionnel, il doit être décomposé en une paire de problèmes unidimensionnels. Cela se fait en projetant les vecteurs de force sur un ensemble d'axes choisis par commodité. Comme vu dans les exemples précédents, le choix des axes peut simplifier le problème. Par exemple, lorsqu'une pente est impliquée, un ensemble d'axes avec un axe parallèle à la pente et un perpendiculaire à celle-ci est le plus pratique. Il est presque toujours plus pratique de prendre un axe parallèle à la direction du mouvement, si cela est possible.

::::{admonition} Application de la deuxième loi de Newton
:class: astuce
Avant d'écrire des équations de la force résultante, il est essentiel de déterminer si le système accélère dans une direction particulière. Si l'accélération est nulle dans une direction particulière, alors la force résultante est nulle dans cette direction. De même, si l'accélération est différente de zéro dans une direction particulière, alors la force résultante est décrite par l'équation :
:::{math}
\vec{F}_{res}=m\cdot\vec{a}
:::

Par exemple, si le système accélère dans le sens horizontal, mais qu'il n'accélère pas dans le sens vertical, vous aurez les conclusions suivantes :
:::{math}
\begin{align*}
\vec{F}_{res\,x} & =m\cdot\vec{a}\\
\vec{F}_{res\,y} & =0
\end{align*}
:::
::::

### Étape 4
Comme toujours, vérifiez la solution pour voir si elle est raisonnable. Dans certains cas, cela est évident. Par exemple, il est raisonnable de constater que le frottement fait glisser un objet sur une pente plus lentement qu'en l'absence de frottement. Dans la pratique, l'intuition se développe progressivement à travers la résolution de problèmes, et avec l'expérience, il devient progressivement plus facile de juger si une réponse est raisonnable. Une autre façon de vérifier votre solution est de vérifier les unités. Si vous résolvez pour la force et que vous vous retrouvez avec des unités de $m/s$, vous avez fait une erreur.
