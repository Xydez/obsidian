Targeted approach: Sanger-sekvensering: man får en sekvens i cellen.

Systems approach: NGS man an ha ett heterogent sample och få alla möjliga sekvenser som finns i provet.

Targeted är alltså att man vet *en* grej medan systems är att man vet *alla* grejer i en cell.


Man kanske har flera olika celler med olika mutationer; NGS analyserar alla och ger en helhetsbild.

Genomics: WGS
Epigenomics: CHIPseq, ATACseq
Transcriptomics: RNAseq
Proteomics: MS
Metabolomics: MS, NMRS


I transcriptomics måste man skilja mRNA från annat RNA. Alla mRNA har en egenskap: poly(A). Alltså kan man kan designa en komplementärsekvens.


1. Dissect region of interest
2. Extract RNA content
3. Capture mRNA using poly-dT oligomers/primers
4. Prepare NGS library (??)
5. Sequence


Tre för single-cell transcriptomics:
- plate-based Smartseq2
- microfluidics
- combinatorial barcoding technology

**Smartseq2:**
1. Sortera celler med ett sånt rör (cell sorter) och lägg dem i brunnar
2. Lysera celler
3. Poly-dT-primers
4. cDNA-syntes
5. PCR och NGS library prep
6. Sekvensering
- Får whole length transcripts 10e3 cells

**Microfluidics:**
- Addera "barcoded beads", små kulor, som typ frångar cellerna i en emulsion; man lägger dem i en emulsion av olja och gör något
- Får 10e4-5 men inte whole cell eller något?
- Varje "bead" har liksom jättemånga strån med en UMI som är en identifier men det är typ random eller något

> Vi kommer inte behöva kunna så mkt om detta på provet, säger hon.

Man gör någon slags **"cell state manifold"**.

