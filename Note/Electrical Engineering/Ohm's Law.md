#electrical-engineering
# Ohm's law

![[drawing ohm law analogy]]
$$V = I \cdot R$$
**Resistor in series:** _Add all the resistances._

```tikz 
\usepackage{circuitikz} 
\begin{document} 
\begin{circuitikz}[american, voltage shift=0.5] 
\draw (0,0) 
to[R, l=$R_1$] (2,0)
to[R, l=$R_2$] (4,0)
to[R, l=$R_3$] (6,0)
to [open, l=$...$] (8,0)
to[R, l=$R_n$] (10,0);
\end{circuitikz} 
\end{document} 
```


Total Resistance for a series circuit ($R_{total}$)

$$R_1 + R_2 + R_3 + ... + R_n$$
**Resistor in parallel**

```tikz 
\usepackage{circuitikz} 
\begin{document} 
\begin{circuitikz}
\draw (0,0) to[short, *-] (8,0);
\draw (2,0) to [R, l=$R_1$] (2, 3);
\draw (4,0) to [R, l=$R_2$] (4, 3);
\draw (6,0) to [open, l=$...$] (6, 3);
\draw (8,0) to [R, l=$R_n$] (8, 3);
\draw (0,3) to[short, *-] (8,3);
\end{circuitikz} 
\end{document} 
```

Total Resistance for a parallel circuit ($R_{total}$)

$$\frac{1}{R_{total}} = \frac{1}{R_1} + \frac{1}{R_2} + ... +\frac{1}{R_n}$$