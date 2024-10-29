#### :LiCalendarClock:  29/10/2024 - 09:04

Il nostro analizzatore in sostanza deve decidere se per una certa proprietà di un programma, l'analizzatore riesce a dire se vale quella proprietà

![[Pasted image 20241029091321.png]]

#### Idea analisi statica

Sappiamo che la semantica è definita nel seguente modo 
![[Pasted image 20241029092510.png]]
- $P(D)$ è l'insieme che rappresenta tutte le semantiche del nostro programma
- $Q \subseteq P(D)$ è il dominio che rappresenta tutte le semantiche del nostro programma
- che soddisfano la proprietà invariante  

#### Analisi statiche (no semantica)
- Control flow analysis
- Data Flow analysis: come l'informazione fluisce dentro il programma (durante l'esecuzione)

Nella data flow analysis si riesce ad approssimare nella sintassi, questo perchè l'analisi non conta gli stati del programma ma andrà a guardare la relazione sintattica tra gli elementi del programma

I tipi di analisi distributive del Data Flow Analysis che approssimano bene sulla sintassi sono
- [[Available Expression]]
- [[Liveness]]
- [[Copy propagation]]
- [[Reaching definition]]
#### CFG based

Questi tipi di analisi sono cfg based, quindi che seguono un algoritmo ricorsivo di calcolo della proprietà desiderata sul cfg

La costruzione dell'analisi è composta da
- costruire il cfg
- analisi del codice Intra procedurale (sul cfg singolo)

Quello che andremo a vedere è capire come l'informazione di interesse viene trasformata dentro un blocco

![[Pasted image 20241029100337.png]]
#### :LiExternalLink: REFERENZE: