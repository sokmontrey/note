#polymer #Chemistry #OrganicChemistry 

>[!example] Content
>- [[#Simple Polymers]]
>- [[#Copolymers]]
>- [[#Forming polymers]]

## Polymers
Naming Simple Polymers: `Poly-` + monomer name

> Monomers: simple organic compound (no repeating)
> Name monomers by following [[IUPAC]] rules.

## Simple Polymers
_Same type of monomers repeating to create simple polymers_
`example1:`

![[drawing simple polymer]]
drawing of **poly ethylene**

`example2:`

```tikz 
\usepackage{chemfig} 
\begin{document} 
\chemname{ \chemfig{[:0]-[@{op,-3.5}]C([:90]-F)([:-90]-F)-C([:90]-F)([:-90]-F)-[@{cl, -3.5}]} }
{poly tetra fluoro ethyl ene}
\polymerdelim[height = 20pt, depth = 10pt, open xshift = -4pt, indice = \!n]{op}{cl}
\end{document} 
```
## Copolymers
_**Two or more** different type of monomers combined_

![[drawing copolymer]]

## Forming polymers
_**Addition polymerization** and **Condensation polymerization** are two possible way to form polymers_ 

### Addiction Polymerization

There are three different way to kick-start the addition polymerization reaction: using **Radicals** or **Cations** or **Anions**.

#### Radicals
_Free radical reaction:_ using molecules with an unpaired electron to kick off the reaction.

This kick off step is **Initiation**.
Radical is the **Initiator**.
The reaction stop when two radicals collide, called **Termination.**

#### Cations
_using positive ion as initiator_
Growing chain cannot cause termination, but they undergo _chain transfer reactions_

>[!NOTE]
>- Addition: no side product
> - Condensation: there are side product
> - Kevlar polymer: 1,4-benzene dioic acid + 1,4-diamino benzene
> - Chiral carbon: are center carbon that connect to four different substituent.
> - Enantiomers: molecule that is mirror of one another.

 