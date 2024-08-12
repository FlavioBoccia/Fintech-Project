Il codice è intereamente scritto su python, abbiamo usato jupyter notebook come editor per poter inserire commenti.
Consigliamo di aprire i notebook nel seguente ordine:

1)Lasso Regression Validation. Qui alleniamo il modello di regressione lineare con lasso penalty sia nel caso di weekly rebalancing che nel caso di monthly rebalancing

2)Lasso Regression Test. Qui osserviamo la performance del nostro modello sul test set.

3)Feature selection. Qui discutiamo brevemente il raziocinio utilizzato per la selezione delle feature da inserire nel kalman filter

4)Kalman Filter. Qui implementiamo il kalman filter e vediamo come si comporta nel validation set senza nessuna ottimizzazione di parametri.
Lo scopo è confrontare l'andamento base con quello della lasso regression

5)Neural Network Anomalie Detection. Qui implementiamo e ottimizziamo una rete neurale per riuscire future anomalie di mercato. Alla fine del codice dovrebbe essere creato un nuovo file excel, VALORI_PREDETTI. Lo inseriamo gia dentro la cartella sperando che non si creano problemi con la gestione dei file durante la creazione.

6)Kalman Filter Validation. Qui cerchiamo l'iperparametro ottimale per il treshold del classificatore allo scopo di ottimizzare il nostro modello.

7) Proviamo la performance del nuovo modello al variare del parametro alfa di esposizione. 