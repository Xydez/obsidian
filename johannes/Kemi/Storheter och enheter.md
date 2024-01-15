## Enheter
| Enhet | Var. | Storhet[^1] | Förklaring |
| ---- | :--: | ---- | ---- |
| $\pu{mol}$ | $n$ | Substansmängd | Antal av något. En mol är *Avogadros tal* ($N_a$) av något.<br>$\pu{1mol}=N_a=\pu{6.02214076e23}$<br>**Definition**: Nästan(?) exakt antalet atomer för 12 gram $\ce{^{12}C}$. |
| $\pu{u}$ | $M_R$ | Relativ atommassa | Anger atomens massa relativt till $1/12$ av massan av en $\ce{^{12}C}$-atom. *Dimensionslös.*<br>**Betydelse**: Genomsnittlig massa för fördelningen av ett grundämnes alla isotoper på jorden. |
| $\pu{g*mol-1}$<br>$\pu{10^{-3}kg*mol-1}$ | $M$ | Massa | Molmassa. Vikten av $\pu{1mol}$ av ett ämne. |
| $\pu{mol*dm-3}$<br>$\pu{10^3*mol*m-3}$ | $c$ | Molaritet | Mol av en upplöst substans per liter av en lösning (total volymen inkl. substansen och lösningsmedlet). Förväxlas ej med *molalitet*, substansmängd per viktenhet.|
## Konstanter
| Konstant | Namn | Värde | Förkl. |
| ---------| ---- | ----- | ------ |
| $N_a$ | Avogadros tal | $\pu{6.02214076e23mol-1}$ | Tidigare antalet atomer för 12 gram $\ce{^{12}C}$; sedan 2019 exakt värde. |
## Ekvationer
### Relativ atommassa vs molmassa
$$M\approx M_R$$
Skillnaden mellan molmassa och relativ atommassa är att molmassa utgår från SI-enheten mol och ges i gram per mol, medans relativ atommassa är massa relativt till kol-12 och dimensionslös.

Dessa två var ekvivalenta fram tills 2019 då Avogadros tal omdefinierades till ett exakt värde[^2]. I praktiken är dessa två växlingsbara, e.g. man använder $M_R$ i ekvationer som vill ha $M$.
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
$M_\ce{H}=\pu{1.008g/mol}$
$M_\ce{O}=\pu{15.999g/mol}$

$M_\ce{H2O2}=2M_\ce{H}+2M_\ce{O}=2\cdot1.008+2\cdot 15.999=\pu{34.014g}$
### Molaritet
$$c=\frac{n}{V}$$
$$c_1V_1=c_2V_2$$
#### Exempel
**Fråga**: *En lösning väteperoxid, $\ce{H2O2}$, är löst i vatten med en koncentration av $\pu{30g/l}$. Vad har den för molaritet?*

Notera att enheterna $\pu{g}$ och $\pu{l}$ används för vikt respektive volym.

$$
\begin{aligned}
c&=\frac{n}{V}\\
&=\frac{\frac{m}{M}}{V}\\
&=\frac{m}{MV}\\
&=\frac{\rho}{M}\\
\end{aligned}
$$

Vi sätter in $\rho=\pu{30g/l}$ och $M_\ce{H2O2}=\pu{34.014g/mol}$.
$$
c=\frac{30}{34.014}=\pu{0.882mol/l}
$$

[^1]: Se avsnittet [Grundenheter](https://sv.wikipedia.org/wiki/SI-enhet#Grundenheter) i Wikipedia-artikeln om SI-enheter.
[^2]: Se [omdefineringen](https://en.wikipedia.org/wiki/2019_redefinition_of_the_SI_base_units#Defining_constants) av SI-basenheterna den 20:e maj 2019.