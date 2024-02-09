# MyST Cheat sheet

## Notes de base

:::{note}
Note
:::

:::{important}
Important
:::

:::{hint}
Hint 
:::

:::{seealso}
See Also
:::

:::{tip}
Tip
:::

:::{attention}
Attention
:::

:::{caution}
Caution
:::

:::{warning}
Warning
:::

:::{danger}
Danger
:::

:::{error}
Error
:::

## Dropdown 

:::{dropdown} Dropdown Title
:open:
Dropdown content
:::

### Note avec dropdown et 2e note incluse

::::{hint} Click Me! 
:class: dropdown
👋 This could be a solution to a problem or contain other detailed explanatios

> Avec un titre

Mon **titre** en gras
:::{danger}
Here is an admonition!
:::

::::

# Notes Personalisées (Admonitions)
## Pour le corps de texte

### Formule à connaître

::::{admonition} Titre_Formule
:class: formule
Formule
::::

### Sur la calculatrice

:::{admonition} Sur la calculatrice
:class: surcalculatrice
Info sur les calculatrices (class: surcalculatrice)
:::

### Astuce

:::{admonition} Astuce
:class: astuce
et_trucs
:::

### Objectifs d'apprentissage

:::{admonition} Objectifs d'apprentissage
:class: objped
À la fin de cette section, vous pourrez :

1. Objectif_1
2. 
:::

### Liens Internet

:::{admonition} Pour plus d'informations
:class: dropdown weblink
Quelques liens utiles sur le même sujet :
- [NomDuLiens](https://www.alloprof.qc.ca/fr/eleves/bv/physique/physique-l-incertitude-et-les-calculs-d-incertitude-p1049)
- 
:::

### Liens YouTube

:::{admonition} YouTube
:class: dropdown admonition-youtube
Quelques liens de vidéo utiles sur le même sujet :
1. **Titre_de_la_vidéo**
%%HTML [--isolated]
<div align="center">
 <iframe width="600" height="400" src="https://www.youtube.com/embed/1zAPfrZaAiA" allowfullscreen></iframe>
</div>

2. **Autre_vidéo**
3. **Et_une_autre**
:::

### Simulations PhET

:::{admonition} P*h*ET simulation
:class: dropdown simulation
**Titre_de_la_simulation**
%%HTML [--isolated]
<div align="center">
<iframe src="address_of_PhET_simulation_to_be_linked" width="600" height="450" scrolling="no" allowfullscreen></iframe>
</div>
:::


## Pour les exercices & questions
### A Faire à la maison

#### Exercices

::::{admonition} Exercice N
:class: exohome
Exercice
:::{admonition} *solution*
:class: dropdown exohomesol
Solution
:::
:::::

#### Questions

::::{admonition} Questions N
:class: question
Question
:::{admonition} *réponse*
:class: dropdown questionsol
Réponse
:::
::::

### Démo/exemple

::::{admonition} Exemple N
:class: exores
Exercice
:::{admonition} *solution*
:class: dropdown solution
Solution
:::
::::

:::::{admonition} Exemple_résolution
:class: exores
Exercice
::::{admonition} *stratégie*
:class: dropdown strategie
Stratégie
::::
::::{admonition} *solution*
:class: dropdown solution
Solution
::::
::::{admonition} *discussion*
:class: dropdown discussion
Discussion
::::
:::::


# Figures

```{figure} figures/TestPNG.png
:name: TestPNG
:align: center
:width: 50%
*Légende*
```

Avec la référence : {numref}`TestPNG` (attention donne Fig. en HTML) ou avec un nom personalisé {numref}`Image %s <TestPNG>` ou un titre personalisé {ref}`Image de l'avion <TestPNG>`

# Tables
:::{list-table} Les 7 unités fondamentales du Sytème International (SI)
:name: unitebasetest
:header-rows: 1
*    - Grandeur physique
     - Notation
     - Unité de base
     - Symbole
*    - Distance
     - $x$, $\Delta$$x$, $d$, $h$, $l$
     - **mètre**
     - $[m]$
*    - Temps
     - $t$, $\Delta$$t$
     - **seconde**
     - $[s]$
*    - Masse
     - $m$, $M$
     - **kilogramme**
     - $[kg]$
*    - Courant électrique
     - $i$, $I$
     - ampère
     - $[A]$
*    - Température
     - $T$
     - kelvin
     - $[K]$
*    - Quantité de matière
     - $n$
     - mole
     - $[mol]$
*    - Intensité lumineuse
     - $I$
     - candela
     - $[cd]$
:::

avec la référence : {numref}`unitebasetest` ou avec un nom pérsonalisé {numref}`Tableau %s <unitebasetest>` voir un titre personalisé {ref}`Tableau des 7 unités SI <unitebasetest>`

# Listes particulières

Term *with Markdown*
: Definition [with reference](https://myst-parser.readthedocs.io/en/latest/configuration.html)

  A second paragraph
: A second definition

Term 2
  ~ Definition 2a
  ~ Definition 2b

Term 3
:     A code block
: > A quote
: A final definition, that can even include images:

(chap:reference)=
# Référence à un chapitre
Voilà comment référencer cette partie :
- Avec un nom : [Cette partie](chap:reference) ou
- Directement avec le titre du chapitre {ref}`chap:reference`