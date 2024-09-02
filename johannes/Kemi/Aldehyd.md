#kemi #kemi/organisk-kemi 

Aldehyder är en funktionell grupp som typiskt bildas vid oxidation av primära alkoholer. De kan sedan oxideras ytterligare för att bilda en [[Karboxylsyra|karboxylsyra]].

**Namn:** \<kolkedja\> + -al
**Exempel:** 1-propanol kan exempelvis bli propanal
## Reaktion
Vi börjar med en primär alkohol.

```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(-[2]H)(-[6]H)-OH}
\end{document}
```

De två väteatomerna oxideras med syre för att bilda en aldehyd och vatten.

$$\ce{R-CH2OH + 1/2O2-> R-CHO + H2O}$$

```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(=[1]O)(-[7]H)}
\end{document}
```

Aldehyden kan sedan oxideras med ytterligare en syre för att bilda en karboxylsyra.

$$\ce{R-CHO + 1/2O2 -> R-COOH}$$

```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{R-C(=[1]O)(-[7]OH)}
\end{document}
```
