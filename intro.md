FISICA 3: Introducción a conceptos de electricidad y magnetismo.
===================================

Ariel Chernomoretz

(Spring 2025)

This is a collection of notebooks on computational (astro)physics.
Starting at the beginning, these notebooks introduce numerical methods
for derivatives, integration, rooting finding, ODEs, and linear algebra
and then move onto applications in astrophysics.


Course Outline
--------------

We'll start with an [An Overview of Python](https://zingale.github.io/computational_astrophysics/python/jupyter.html)
and [Version Control with Git](https://zingale.github.io/computational_astrophysics/git/version-control.html) and then
move on to core numerical methods.

You should follow the outline in the navigation panel to the left.

```{note}
This course assumes that you are already familiar with a programming language.
```


Astrophysical Applications
--------------------------

Throughout the course, we'll see some applications to interesting problems in astrophysics.  Here's a listing
to some of them:

::::{grid}
:gutter: 3

:::{grid-item-card} Reaction Rate $T$ Sensitivity
{bdg-info-line}`diff`
An example of using numerical differentiation to
[estimate the 3-$\alpha$ reaction $T$ sensitivity](https://zingale.github.io/computational_astrophysics/basics/diff-int/application-rate-temperature-sensitivity.html).
:::

:::{grid-item-card} Blackbody Radiation
{bdg-info-line}`int`
An example of integrating to infinity by
[integrating the Planck function over wavelength](https://zingale.github.io/computational_astrophysics/basics/diff-int/application-blackbody.html).
:::

:::{grid-item-card} Wien's Law
{bdg-info-line}`roots`
Demonstrating root finding by
[numerically deriving Wien's law](https://zingale.github.io/computational_astrophysics/basics/roots/application-wiens.html).
:::


::::



# Welcome to your Jupyter Book

This is a small sample book to give you a feel for how book content is
structured.
It shows off a few of the major file types, as well as some sample content.
It does not go in-depth into any particular topic - check out [the Jupyter Book documentation](https://jupyterbook.org) for more information.

Check out the content pages bundled with this sample book to see more.

```{tableofcontents}
```
