#kemi #kemi/organisk-kemi 
## Alkaner, alkener och alkyner
### Alkaner
Den enklaste typen av kolväte är alkanerna, som är kolväten där det bara är enkelbindningar mellan kolatomerna. Den enklaste alkanen är i sin tur metan, som bara har en kolatom i kedjan. Därefter kommer metan (bilden nedan) och sedan propan. Resterande kolväten börjar med ett prefix, t.ex. prefixet "n-", som i n-butan (se *strukturisometri*). Från och med den femte alkanen nämns alla dessutom efter IUPAC-nomenklatur.

```tikz
\usepackage{chemfig}
\begin{document}
\chemfig{C(-C(-H)(-[2]H)(-[6]H))(-[2]H)(-[4]H)(-[6]H)}
\end{document}
```

Denna kolväteserie kallas den *homologa alkanserien*.

> [!info] Cykloalkanerna
> Om kolvätet går i en cirkel kallas motsvarande serie istället för **cykloalkanerna**. Jämför till exempel hexan och cyklohexan;
> ```smiles
> CCCCCC
> C1CCCCC1
> ```
### Alkener och alkyner
Medan alkanserien är kolväten med endast enkelbindningar är *alkenserien* kolväten med en eller flera dubbelbindningar. *Alkynserien* är likaså kolväten med en eller flera trippelbindningar.

```smiles
CCCC
CC=CC
CC#CC
```