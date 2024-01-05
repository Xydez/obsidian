## Enheter
| Enhet | Var. | Storhet[^1] | Förklaring |
| ---- | :--: | ---- | ---- |
| $mol$ | $n$ | Substansmängd | Antal av något. En mol är *Avogadros tal* ($N_a$) av något.<br>$1mol=N_a=6.022 140 76\cdot 10^{23}$<br>**Definition**: Nästan(?) exakt antalet atomer för 12 gram $^{12}C$. |
| $u$ | $M_R$ | Relativ atommassa | Anger atomens massa relativt till $1/12$ av massan av en $^{12}C$-atom. *Dimensionslös.*<br>**Betydelse**: Genomsnittlig massa för fördelningen av ett grundämnes alla isotoper på jorden. |
| $g\cdot mol^{-1}$<br>$10^{-3}kg\cdot mol^{-1}$ | $M$ | Massa | Molmassa. Vikten av 1 mol av ett ämne. |
| $mol\cdot dm^{-3}$<br>$10^3\cdot mol\cdot m^{-3}$ | c | Molaritet | Mol av en upplöst substans per liter av en lösning (total volymen inkl. substansen och lösningsmedlet). Förväxlas ej med *molalitet*, substansmängd per viktenhet.|
## Ekvationer
### Relativ atommassa vs molmassa
$$M\approx M_R$$
Skillnaden mellan molmassa och relativ atommassa är att molmassa utgår från SI-enheten mol och ges i gram per mol, medans relativ atommassa är massa relativt till kol-12 och dimensionslös.

Dessa två var ekvivalenta fram tills 2019 då Avogadros tal omdefinerades till ett exakt värde[^2]. I praktiken är dessa två växlingsbara, e.g. man använder $M_R$ i ekvationer som vill ha $M$.
### Molmassa
$$n=\frac{m}{M}$$
- $n$ är substansmängd (mol)
- $m$ är massan (g)
- $M$ är molmassan (g/mol)
#### Exempel
**Fråga**: *Vad väger 1 mol av $\ce{H2O2}$?*

Eftersom $n=1$ enl. uppgiftsbeskrivningen vet vi med hjälp av formeln följande.
$m_\ce{H2O2}=M_\ce{H2O2}$

Vi vet att vikten av en molekyl är summan av vikten av dess delar.
$M_\ce{H2O2}=2M_\ce{H}+2M_\ce{O}$

Vi sätter in värden.
$M_\ce{H}=1.008g/mol$
$M_\ce{O}=15.999g/mol$

$M_\ce{H2O2}=2M_\ce{H}+2M_\ce{O}=2\cdot1.008+2\cdot 15.999=34.014g$
### Molaritet
$$c=\frac{n}{V}$$
$$c_1V_1=c_2V_2$$
#### Exempel
**Fråga**: *En lösning väteperoxid, $\ce{H2O2}$, är löst i vatten med en koncentration av $30g/l$. Vad har den för molaritet?*

Notera att enheterna $g$ och $l$ används för vikt respektive volym.

$$
\begin{aligned}
c&=\frac{n}{V}\\
&=\frac{\frac{m}{M}}{V}\\
&=\frac{m}{MV}\\
&=\frac{\rho}{M}\;mol\cdot dm^{-3}\\
\end{aligned}
$$

Vi sätter in $\rho=30g/l$ och $M_\ce{H2O2}=34.014g/mol$.
$$
c=\frac{30}{34.014}=0.882mol/l
$$

[^1]: Se avsnittet [Grundenheter](https://sv.wikipedia.org/wiki/SI-enhet#Grundenheter) i Wikipedia-artikeln om SI-enheter.
[^2]: Se [omdefineringen](https://en.wikipedia.org/wiki/2019_redefinition_of_the_SI_base_units#Defining_constants) av SI-basenheterna den 20:e maj 2019.