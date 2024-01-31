#biologi #biologi/genetik
## Modifiering
Några kända metoder för att modifiera DNA är:
- [[#Restriktionsenzymer|Restriktionsenzym]]
- [[#PCR-metoden|PCR-metoden]]
- asRNA
- RNAi

> [!todo] Uppgift
> Undersök även *asRNA* och *RNAi* (s. 59, Biologi 2)
### Restriktionsenzymer
Ett *restriktionsenzym* är ett [[Enzym|enzym]] som känner igen en specifik sekvens av baspar och klipper av [[Nukleinsyror#DNA|DNA]]-spiralen där. Efter att man har tillämpat enzymet får man flera sönderklippta *restriktionsfragment* (vars antal beror på hur vanlig sekvensen är) som går att skilja isär med [[Gelelektrofores|gelelektrofores]].

![[Restriktionsenzym.png]]

Restriktionsenzymer kan antingen klippa rakt (som Hpa I), eller diagonalt (som EcoR I), i vilket fall det sägs att strängen har *klistriga ändar*.
### PCR-metoden
PCR (Polymerase Chain Reaction) är en metod för att snabbt föröka en liten mängd DNA.

Metoden går ut på att tillhandahålla samma ämnen som cellen själv använder för att replikera DNA, det vill säga [[Polymeras|DNA-polymeras]], primers och kvävebaser fogade med socker och fosfat.
## Identifiering
Det finns flera metoder för att skilja på och identifiera DNA:
- [[Restriction Fragment Length Polymorphism|Restriction Fragment Length Polymorphism]]
- [[Gelelektrofores|Gelelektrofores]]
- [[Hybridiseringssond|Hybridiseringssond]]
## Ändring av genom
### Översikt
Om man med ett enzym klipper en sträng så att den får klistriga ändar kan man sedan sätta in en annan sträng som har *komplementära klistriga ändar*, och på så sätt modifiera genomet.

**Vektorer**
En *vektor* är inom genteknik någonting som kan föra DNA in i en levande cell. Detta kan exempelvis vara en plasmid vars DNA delvis har ändrats.
### Genmodifiering
#### Modifiering av bakterie med prokaryot DNA
För att genmodifiera en bakterie börjar man först med en plasmid modifierad med ett restriktionsenzym som får vara vektor. Plasmiden införlivas sedan med behandling i bakterier. Bakterielösningen späds ut, och sprids sedan ut på agarplattor. Man låter bakterierna bilda kolonier och undersöker sedan dem för att se om det önskade ämnet bildas.

För att säkerställa att enzymet fungerat brukar man förse plasmiden man utgår ifrån med en gen som bildar blå färg på just det ställe som planeras att byta ut. När man sedan studerar bakterierna kommer de med blå färg vara de som misslyckats att modifieras.

När man sedan har bekräftat att genen fungerar brukar man låta bakterien förökas och på så sätt klona genen.
#### Modifiering av bakterie med eukaryot DNA
Till skillnad från prokaryot DNA kan man inte direkt sätta in eukaryot DNA i en bakterie eftersom det innehåller [[Kromosom#Uttryck|introner]].

Istället brukar man med enzymet [[Transkription#Omvänd transkription|omvänt transkriptas]] omvandla eukaryot mRNA till så kallat *cDNA* (complementary DNA), och därefter sätta in det i en plasmid.

Det är dock värt att notera att alla eukaryota gener inte fungerar i prokaryota celler eftersom de nödvändiga ämnena inte finns. I dessa fall måste proteinet skapas i en eukaryot cell.
#### Modifiering av eukaryot cell
För att bilda protein brukar jästceller ofta användas i kombination med ett konstgjort jästkromosom (YAC, yeast artificial chromosome).

För att få in gener i växter modifieras i regel en jordbakterie som sedan infekterar växten och för vidare genen.

För att få in gener i djur finns det flera olika metoder. En metod är att använda [[Virus#Förökning|retrovirus]]. En annan metod är *mikroinjektion*, vilket är att man med en tunn pipett för in DNA i en nyss befruktad äggcell.
## Kartläggning och isolering
Att *isolera* en gen är att ta reda på dess sekvens, läge samt vilket protein den bildar och vilka egenskaper den påverkar.

**Om man känner till ett protein**
Om proteinet är känt går det att räkna ut vilken DNA-sekvens den motsvarar. Det blir dock lite svårare med eukaryoter på grund av intronerna, men datorer kan hitta vilka möjliga ställen det kan röra sig om.

**Om man känner till en egenskap**
Om egenskapen är känd är det ofta mycket svårt att härleda exakt vilka proteiner som orsakar egenskapen.

I fall av en monogen ärftlig sjukdom går det genom att jämföra friska och sjuka individer att hitta en sjukdomsframkallande [[Ärftliga sjukdomar#Alleler|allel]] (genvariant) av en gen. Denna jämförelse kan göras genom att behandla individernas respektive DNA med [[#Restriktionsenzymer|restriktionsenzymer]].
### Användning
- **Identifiering av individer**
	I \[intronerna / sträckorna som inte kodar för protein\] är vissa sträckor så kallade *hyperaktiva sekvenser*, vilket innebär att mutationer inträffar mycket ofta. På grund av detta kan dessa sekvenser användas för att unikt identifiera individer. De kan även användas för att identifiera släktskap då barnen ärver hälften av sekvenserna var.
- **Gensonder** - Bitar av sekvenserade gener kan användas som [[Hybridiseringssond|gensonder]].
- **DNA-vaccin** - Man kan få kroppen att tillverka virusprotein i syfte att få immunförsvaret att bilda [[Antikroppar|antikroppar]]. Metoden är fortfarande i experimentstadiet.
- **Genterapi** - Går ut på att ersätta defekta alleler. Har prövats men än så länge för farligt.