#Carbonyl #Chemistry #IUPAC #OrganicChemistry

>[!example] Content
>- [[#Aldehydes]]
>- [[#Ketones]]
>- [[#Carboxylic Acids]]
>- [[#Esters]]

---

# Aldehydes 
`Suffix: -al` 
`Prefix: formyl-`

```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemfig{[:30]R-[:30]C([:90]=O)([:-30]-H)}
\end{document} 
```

# Ketones 
`Suffix: -one` 
`Prefix: oxo-`

```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemfig{[:30]R_1-[:30]C([:90]=O)([:-30]-R_2)}
\end{document} 
```

# Carboxylic Acids 
`Suffix: -oic acid` 
`Preffix: carboxy-`

```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemfig{[:30]R_1-[:30]C([:90]=O)([:-30]-OH)}
\end{document} 
```

# Esters 
`Suffix: -oate` 
`Preffix: Alkoxycarbonyl-`
_Name Alkyl group that connected with O then name the long chain of Carbons_

```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemfig{[:30]R_1-[:30]C([:90]=O)([:-30]-O-[:30]R_2)}
\end{document} 
```

## Reactions
### Substitution (Esterification)
_Forming Ester using acid_

```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemname{\chemfig{[:30]R_1-[:30]C([:90]=O)([:-30]-OH)}}{Carboxylic Acid}
+
\chemname{\chemfig{HO-R_2}}{Alcohol}
\schemestart
\arrow{->}
\schemestop
\chemname{\chemfig{[:30]R_1-[:30]C([:90]=O)([:-30]-O-[:30]R_2)}}{Ester}
+
\chemname{\chemfig{HOH}}{Water}
\end{document} 
```

### Acidic hydrolysis
_Reverse esterification_

```tikz 
\usepackage{chemfig} 
\begin{document} 

\chemname{\chemfig{[:30]R-[:30]C(=[:90]O)([:-30]-O-[:30]R')}}
{carboxylatester }
+
\chemname{\chemfig{NaOH}}
{ sodiumhydroxide}

\schemestart 
\arrow{->[hydrolysis]}
\schemestop

\chemname{\chemfig{R-[:30]C(=[:90]O)(-[:-30]O^{-}Na^{+})}}
{sodiumcarboxylate}
+
\chemname{\chemfig{HO-R'}}
{Alcohol}

\end{document} 
```
