#electrical-engineering #chip
# 555 Timer
`Pinout:`
```tikz 
\usepackage{circuitikz} 
\begin{document} 
\begin{circuitikz}
\draw (0,0) node[dipchip](T){555};
\draw (T.pin 1) node[left]{GND};
\draw (T.pin 2) node[left]{Trigger};
\draw (T.pin 3) node[left]{OUT};
\draw (T.pin 4) node[left]{Reset};
\draw (T.pin 5) node[right]{CV};
\draw (T.pin 6) node[right]{Threshol};
\draw (T.pin 7) node[right]{Discharge};
\draw (T.pin 8) node[right]{VCC};
\end{circuitikz} 
\end{document} 
```

`Internal block diagram:`
![[drawimg inside 555]]

555 timers consist of three 5k resistors. With two comparators and a JK flip-flop, 555 timers can be used in a precise timing application.