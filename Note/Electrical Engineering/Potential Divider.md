#electrical-engineering 
# Potential divider
Derived from [[Ohm's Law#Ohm's law|Ohm's law]].

```tikz 
\usepackage{circuitikz} 
\begin{document} 
\begin{circuitikz}[american, voltage shift=0.5] 
\draw(0,4) to[short, *-] (0,4) node[above]{$V_{in}$};
\draw (0,0)
to [R, l=$R_2$] (0, 2)
to [short, *-] (0, 2)
to [R, l=$R_1$] (0, 4);
\draw (0,0)node[ground]{};
\draw (0, 2) to (2,2);
\draw (2,2) to[short, *-] (2,2) node[above]{$V_{out}$};
\end{circuitikz} 
\end{document} 
```
$$simple\;divider$$
In order to find the Voltage between two resistors in a series circuit, we first find the total current.

$$I_{total} = \frac{V_{in}}{R_{total}} = \frac{V_{in}}{R_1 + R_2}$$
Then, using Ohm's law, we find voltage with $R_2$
$$V_{out/R_2} = I_{total} \times R_2$$
This can be simply to an equation:
$$V_{out} = R_2 \cdot \frac{V_{in}}{R_1 + R_2}$$
To find a more general formula in an even more complicated circuit, all we have to do is combined all resistance before $V_{out}$ point as $R_1$ (first resistance) and all resistance after $V_{out}$ as $R_2$ (after resistance).

**General Formula:**
$$V_{out} = R_{after} \cdot \frac{V{in}}{Total \; current}$$
