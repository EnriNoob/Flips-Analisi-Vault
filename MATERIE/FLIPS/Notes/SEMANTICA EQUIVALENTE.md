#### :LiCalendarClock:  14/11/2024 - 21:22

#### Idea
Fino ad ora abbiamo dato una semantica operazionale, ovvero come evolvono i programmi a runtime

Ora possiamo dare una idea di semantica equivalente se dal punto di vista osservazionale se due programmi hanno lo stesso comportamento (avendo sintassi diversa e facendo percorsi diversi per arrivare allo stesso risultato)

Avere due programmi che hanno semantica equivalente per programmazione concorrente

#### Intuizione

Due programmi ad esempio $P_1$ e $P_2$ sono semanticamente equivalenti se $P_1$ può essere rimpiazzato da $P_2$ e viceversa.

$P_1$ e $P_2$ possono essere dei __moduli__ oppure delle __componenti__, cioè che se metto uno o l'altro in un contesto più grande, il contesto non cambierà il suo comportamento sia se scegliesse $P_1$ o $P_2$

![[Pasted image 20241114214615.png]]

ecco un esempio 

![[Pasted image 20241114215420.png]]

#### :LiExternalLink: REFERENZE: