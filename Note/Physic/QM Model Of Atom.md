#Quantum-mechanic
# Modern model of atom(QM model)
_Quantum mechanic model of atoms stated that atoms are consisted of nucleus (Protons & Neutrons) surrounded by a cloud probability represent the existence of the electrons._
## Four Quantum numbers of Electron
### 1. Principal quantum number (shell, $n$)
_Represent shells (energy level of electrons)._ 
$$n \in \mathbb{N} \; \; , \;\; n\geq 1$$
>[!NOTE]
>$n$ does not represent how many shells are there. Instead, it represents the shell itself.

### 2. Secondary quantum number (subshell, $l$)
_Tell how many subshells (orbitals) are there in a given shell (n). $l$ are all natural number from $0$ to $n-1$._
$$\{l: 0 \leq l \leq n-1 \;\;,l \in \mathbb{N} \}$$
Each subshell has their own shape of orbital (cloud of probability).
- $l=0:$ s orbital (like a sphere)
- $l=1:$ p orbital (like a dumbbell)
- $l=2:$ d orbital (like a leaf clover)
- $l=3:$ f orbital (complicated, combination of the above shape)

`For example:` At $n=2$ (second shell) there are $l=\{0,1\}$ (subshell 0 and 1). This mean there are $s$ and $p$ orbital in this shell.

>[!IMPORTANT]
>There are a certain type of shell that overlap with other by their subshells. This can be easily figured out by using the diagonal crossing technique. 

![Crossing diagram|400](http://antranik.org/wp-content/uploads/2011/10/shells-orbital-electron-configuration.jpg)

`Correct order: 1s 2s 2p 3s 3p 4s 3d 4p 5s 4d 5p 4f 5d 5f...`

![Order of orbital diagram|400](https://revisionscience.com/sites/revisionscience.com/files/imce/RS_Sub-Shell-Energy-Levels.gif)

### 3. Magnetic quantum number (orientation, $m_l$)
_Represent, how many orientations are there given a certain type of orbital (subshell, $l$). $m_l$ are all integers from negative $l$ to positive $l$, including $0$._
$$\{m: m \in \mathbb{Z}\;\;,\;\;m=-l \rightarrow +l\}$$
For:
- s orbital: $l=0 \rightarrow m: 0$
- p orbital: $l=1 \rightarrow m: -1 ,\;0 ,\;1$
- d orbital: $l=2 \rightarrow m: -2,\; -1,\; 0,\; 1,\; 2$
- f orbital: $l=3 \rightarrow m: -3,\; -2,\; -1,\; 0,\; 1,\; 2,\; 3$

**S orbital:** $1$ orientation (center cloud).
**P orbital:** $3$ orientations along three axes $$P_x\;,\;P_y\;, \;P_z$$
**D orbital:** $5$ orientations $$D_{xy} \;,\; D_{yz} \;,\; D_{xz} \;,\; D_{x^2-y^2} \;,\; D_{z^2}$$
**F orbital:** $7$ orientations $$F_{z^3}, F_{xz^2}, F_{yz^2}, F_{x(x^2-3y^2)}, F_{y(y^2-3x^2)}, F_{xyz}, F_{z(x^2-3y^2)}$$
### 4. Spin quantum number ($m_s$)
_Each orbital orientation can hold up to 2 electrons. These two electrons must have opposite spin. Possible spin value for an electron, for now, are $m_s = +\frac{1}{2} \; and \; m_s=-\frac{1}{2}$. In quantum mechanic, the term spin isn't actually “spinning”. An elementary particle carrying spin means that it has angular momentum to affect the wave function, but nothing like a classical counterpart. But for a simplicity, High school textbook decided that $+\frac{1}{2}$ is a clockwise spin, and $-\frac{1}{2}$ is a counterclockwise spin. 

>[!NOTE]
>Due to the fact that each orbital orientation can hold 2 electrons, we can know that:
>- s orbital can have maximum electrons of 2
>- p can have 6
>- d can have 10
>- f can have 14
>
> We can now identify a certain electron using these for quantum number. 
> `For example:` $n = 2, l = 1, m_l = -1, m_s = +\frac{1}{2}$
> This is electron is in second shell, in the shape of p orbital, oriented along $P_x$ axis, and clockwise spin.
> 
> When an $s$ orbital in second shell filled with 1 electron, we can write: $2s^1$. 2 represent n (energy level), s is s orbital, and the exponent 1 mean that there are 1 electron in this certain orbit.

