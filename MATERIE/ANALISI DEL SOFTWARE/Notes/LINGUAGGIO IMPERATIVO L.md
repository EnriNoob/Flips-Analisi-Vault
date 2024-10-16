#### :LiCalendarClock:  13/10/2024 - 15:39
#### :LiStepBack: Nota precedente:

Questo linguaggio avrà una sintassi:

![[Pasted image 20241013154237.png]]

Per avere la semantica, quindi il comportamento dell'esecuzione del programma, abbiamo bisogno di un'informazione molto importante che è la memoria. Per questo si utilizzerà lo stato che descrive la memoria ad ogni passo di esecuzione e la sua semantica è una funzione tra stati (in modo composizionale)
$$
\mathbb{M} : Var \rightarrow Val 
$$ quindi un $m \in\mathbb{M}$ è una "mappatura" tra un variabile e un valore. Mentre la semantica è definita come l'insieme delle possibili sequenze di transizioni di stati dallo stato iniziale, in questo caso funziona come un'interprete perchè prende passo passo un'istruzione e dei input e vede la usa esecuzione.
I programmi possono contenere le espressioni e quindi la lora semantica è

![[Pasted image 20241013155529.png]]

e la semantica dei comandi è invece

![[Pasted image 20241013155712.png]]
#### :LiStepForward: Nota successiva: