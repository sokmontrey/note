#Chemistry #IUPAC #OrganicChemistry 

>[!example] Content
>- [[#Amines]]
>- [[#Amides]]
>- [[#Nitriles]]

---

# Amines 
_Single bonded Nitrogen_
`Suffix: -amine` 
`Prefix: amino-`

```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemfig{R-NH2}
\end{document} 
```

- Primary (1$^\circ$): default 
- Secondary ($2^\circ$): similar to ether, but `Alkoxy` $\ce{->}$ `N-Alkyl`
- Tertiary ($3^\circ$): same as Secondary, but add **one more** `N-Alkyl`

`example1:` N-methyl-N-EthylHexanamine

## Reactions
- weak bases in water
- Amines can undergo neutralization reactions with acid
### Forming amines
- forming primary ester
```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemname{\chemfig{R-Halo}} {Alkyl halide}
$\quad$ + $\quad$
\chemname{\chemfig{NH_3}}{Ammonia}
$\quad\rightarrow\quad$
\chemname{\chemfig{R-NH_2}}{Amines 1}
$\quad$ + $\quad$
\chemname{\chemfig{H-Halo}}{Hydrogen Halide}
\end{document} 
```

- forming secondary ester
```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemname{\chemfig{R_1-Halo}} {Alkyl halide}
$\quad$ + $\quad$
\chemname{\chemfig{R_2-NH_2}}{Amines 1}
$\quad\rightarrow\quad$
\chemname{\chemfig{R_1-NH-R_2}}{Amines 2}
$\quad$ + $\quad$
\chemname{\chemfig{H-Halo}}{Hydrogen Halide}
\end{document} 
```

>_the same type of reactions can undergo with amine 2 to form amine 3_

---
# Amides 
_Double bonded Nitrogen_
`Suffix: -amide` 
`Prefix: amido-`

```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemfig{[:30]R_1-[:30]C([:90]=O)([:-30]-NH_2)}
\end{document} 
```

## Reaction
- weak bases in water
- Amides can undergo Hydrolysis reaction to form amine

### Forming amides
- forming primary amide
```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemname{\chemfig{[:30]R-[:30]C([:90]=O)([:-30]-OH)}}{carboxylic acid}
$\quad$ + $\quad$
\chemname{\chemfig{NH_3}}{ammonia}
$\quad\rightarrow\quad$
\chemname{\chemfig{[:30]R-[:30]C([:90]=O)([:-30]-NH2)}}{Amide 1}
$\quad$ + $\quad$
\chemname{\chemfig{H_2O}}{water}
\end{document} 
```

- forming secondary amide
```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemname{\chemfig{[:30]R_1-[:30]C([:90]=O)([:-30]-OH)}}{carboxylic acid}
$\quad$ + $\quad$
\chemname{\chemfig{[:30]R_2-[:30]C([:90]=O)([:-30]-NH2)}}{Amide 1}
$\quad\rightarrow\quad$
\chemname{\chemfig{[:30]R_1-[:30]C([:90]=O)([:-30]-NH-[:30]R_2)}}{Amide 2}
$\quad$ + $\quad$
\chemname{\chemfig{H_2O}}{water}
\end{document} 
```
>second type of reaction can undergo with amide2 to form amide3

---

# Nitriles
`Prefix: cyano-`
`Suffix: -nitrile` (new)

```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemfig{R-C~N}
\end{document} 
```