#### :LiCalendarClock:  09/12/2024 - 09:05

#### Strumenti fondamentali

come descritto In [[INTERPRETAZIONE ASTRATTA]] il legame tra il mondo concreto (nel quale vogliamo calcolare le varie risposte) e il mondo astratto (nel quale possiamo dare delle risposte) avviene per ==connessione di galois== e utilizzando il processo di astrazione e concretizzazione. E estremamente necessario che il legame sia bilaterale, ovvero poter andare nel mondo astratto e ritornare nel mondo concreto

---
#### Connessione di Galois

è una coppia di funzioni $\alpha,\gamma$ monotone definite tra un dominio concreto $C$ e un dominio astratto $A$, quest'ultimi due sono reticoli completi

- **funzione di astrazione $\alpha$**
	![[Pasted image 20241209093515.png]]
- **funzione di concretizzazione $\gamma$**
	![[Pasted image 20241209093724.png]]

graficamente, un elemento $c$ che si trova nel dominio di $C$ con una sua controparte nel dominio astratto $\alpha(c)$ (attraverso $\alpha$) e quest'ultimo è minore di un valore $a$ che si trova nel dominio $A$, allora la concretizzazione con $\gamma(a)$, che lo porta nel mondo concreto, sarà maggiore di $c$ 

![[Pasted image 20241209094610.png]]

La notazione è la seguente

![[Pasted image 20241209095157.png]]


---
#### Inserzione di Galois

Un'inserzione di Galois è più raffinato rispetto alla connessione, perchè non avrà nel dominio astratto elementi inutili, cioè che ogni elemento astratto ha un proprio significato concreto specifico (non hanno lo stesso $\gamma$) 

![[Pasted image 20241209101153.png]]

La migliore approssimazione in generale è equivalente a dire che 

![[Pasted image 20241209095616.png]]

ovvero nel primo caso se si astrae e dopo si concretizza si perde informazioni su $c$, e il secondo ci dice che ci sono elementi nel dominio astratto che sono inutili rispetto ad altri, e verrano diciamo _"inclusi"_ (che sono elementi più grandi) con gli elementi cha hanno significato (più piccoli) in base alla proprietà che stiamo osservando 

Questo concetto è importante perchè ==_ogni connessione di galois può essere ridotta ad una inserzione di galois_==, rendendo il dominio astratto più snello, eliminando elementi inutili per cui il loro significato è lo stesso ad un elemento più preciso
#### :LiExternalLink: REFERENZE: