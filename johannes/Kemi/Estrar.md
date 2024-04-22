#kemi #kemi/organisk-kemi 
## Hur estrar bildas
En ester bildas genom en reaktion mellan en [[Alkohol|alkohol]] och en [[Organiska syror|syra]]. Den vanligaste sortens estrar är *karboxylsyreestrar*, som uppstår när en alkohol reagerar med en karboxylsyra.
### Exempel
Etanol reagerar med butansyra "smörsyra".

Vid denna sorts reaktion (?) avges vatten.

$$\ce{C2H6O + C4H8O2 <=> C8H12O2 + H2O}$$

**Etanol**
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]H)-O(-[:300]H)}
\end{document}
```

**Butansyra**
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{C(=[:120]O)(-[:240]OH)-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]H)-H}
\end{document}
```

När vattnet bildas reagerar det lösa $\ce{H+}$ vätet i etanolen med $\ce{OH-}$-gruppen i butansyran och kondenserar för att bilda vatten. Då binder karbidjonen till syrejonen och skapar en ny större molekyl.

**Etylbutanoat**
```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{H-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]H)-O-C(=[2]O)-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]H)-C(-[2]H)(-[6]H)-H}
\end{document}
```

Lägg särskilt märke till följande del, som kallas *esterbindning* och kännetecknar estrar.

```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{A-O-C(=[2]O)-B}
\end{document}
```

Syret binder alltså här till en *karbonylgrupp* $\ce{C\bond{=}O}$. OBS att det finns andra estrar och att den enda gemensamma nämnaren (?) är en enkelbunden och en dubbelbunden syreatom.

Molekylen namngivs "\<alkoholdel\> + -yl + \<syradel\> + -oat". Alkoholdelen etanol är en alkohol av etan som när den blivit till en radikal fått namnet etyl. Syrdelen butansyra är en karboxylsyra av butan varför den i estern blir "butanoat". Således är namnet "Etylbutanoat".[^1]

## Polyestrar
- Karboxylsyra + envärd alkohol = ester
- Dikarboxylsyra + envärd alkohol = diester (två esterbindningar, en alkohol på varje sida)
- Karboxylsyra + tvåvärd alkohol = diester (två esterbindningar, en karboxylsyra på varje sida)
- Dikarboxylsyra + tvåvärd alkohol = polyester (detta eftersom de kan köra varannan och bildar långa kedjor)

Polyesterkedjor binder bara till varandra med [[Bindningar|van der Waals-bindningar]].

[^1]: Se [[IUPAC-nomenklatur]].