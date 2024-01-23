<!--
AGH Document template. Created from https://github.com/gucio321/agh-sphinx-template

DISCLAIMER: This is NOT an official template!
-->
## This is an index file

<!-- use this to include other files
```{include} path/to/some/file
```
-->

<!-- tak się robi wykres
dyrektywa plot wywołuje wewnętrzny program (w tym przypadku gnuplot
https://pypi.org/project/sphinxcontrib-plot/

-->
```{plot} gnuplot
:caption: podpis

plot sin(x)
```

<!--
Use this to generate toctree
```{toctree}
:maxdepth: 3

path/to/some/file.md
```
-->
