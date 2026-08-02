1\) Uzeti topologiju od agregata B (ima ormare s oznakama +B ...) i kopirati je za upravljanje zajedničkom potrošnjom.

2\) Konačno topologija mora imati:

&#x09;a) +Y1 CJA01 - Ormar upravljanja zajedničkih uređaja; ekvivalent +B CJA01 ormaru

&#x09;b) +Y1 CBF01 - RIO ormar upravljanja zajedničkih uređaja na turbinskom katu; 		ekvivalent +B CBF01 (ima panel)

&#x09;c) +Y1 CBF02 - RIO ormar upravljanja zajedničkih uređaja na katu strojarnice; 	ekvivalent +B CBF01 (nema panel)

&#x09;d) +E01F1 i +E02F1 - Zaštita sabirnica i 110 kV dalekovoda 1(2); spojiti ih kao black 	boxeve, odnosno ostaviti prazne structure boxeve i u svaki poslati po jednu 	optičku vezu sa svakog od dva switcha iznad panela u +Y1 CJA01 ormaru

&#x09;e) +YAHQ01 - Ormar obračunskih mjerenja, kontrola kvalitete energije; spojiti u +Y1 	CJA01 (moram provjeriti s Patrikom, ali ja bi ih zasad spojila u switcheve kod 	multimetara, ali Profinetom, po jednu vezu u svaki switch). Pretpostavljam da će to 	biti neka pametna brojila, možeš ih zasad nacrtati kao black box

&#x09;f) +AC0 - Procesna stanica veze s CPS; zasad spojiti kao i +YAHQ01, ali umjesto black 	boxa prikazati switch (ovo isto moram provjeriti s Patrikom)

3\) RIO ormare +Y1 CBF01(2) nacrtati i spojiti kako je Patrik predložio na slici "PK\_upute" iz foldera

