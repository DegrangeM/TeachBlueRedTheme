# TeachBlueRedTheme
Un thème pour le package [Teach](https://www.mathweb.fr/euclide/les-packages-personnels-latex-stephane-pasquet/) sur LaTeX.

Pour utiliser ce thème, rajouter :

```latex
\redefinecolor{thm}{title}{bgcolor}{red}
\redefinecolor{prop}{title}{bgcolor}{red}
\redefinecolor{lemme}{title}{txtcolor}{red}
\redefinecolor{cor}{title}{txtcolor}{red}
\redefinecolor{defn}{title}{bgcolor}{red!70!black}
\redefinecolor{exo}{title}{txtcolor}{blue!60!black}
\redefinecolor{exo}{rule}{color}{blue!60!black}
\redefinecolor{act}{title}{txtcolor}{blue!60!black}
\redefinecolor{act}{rule}{color}{blue!60!black}
```

juste après :

```
\usepackage[]{teach}
```

Une démonstration est disponible [en cliquant ici](https://github.com/DegrangeM/TeachBlueRedTheme/blob/master/demo.pdf).
