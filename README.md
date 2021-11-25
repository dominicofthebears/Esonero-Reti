# Esonero-Reti
Applicativo client-server in c realizzato per l'esonero di Reti di Calcolatori AA 2021-2022
All'interno del file zip sono presenti i due progetti: lato server e lato client dell'applicativo

Entrambi possono essere avviati sia con dei parametri da linea di comando, di cui il primo verrà utilizzato come indirizzo IP ed il secondo come numero di porta,
sia eseguendo il file .exe (ovviamente, prima il server e poi il client)

Il formato delle operazioni, come specificato dal client, è simbolo valore valore (+ 3 2), eventuali spazi aggiuntivi in qualsiasi posizione faranno sì che la stringa in input
venga rifiutata.

Per chiudere la connessione, invece, bisogna inserire il carattere '=', il quale può essere seguito (ma non preceduto) da eventuali spazi, ciò farà arrestare il processo 
lato client, mentre il server rimarrà in ascolto

La divisione per 0 produrrà un messaggio di errore, così come l'uso di valori troppo grandi. Il limite per i valori è di 10000, questo in quanto valori troppo grandi, i quali
superano il MAX_FLOAT, faranno sì che il risultato dell'operazione sia un valore casuale. Per tale motivo, abbiamo imposto tale limite.

Tali scelte sono commentate all'interno del codice in lingua inglese, come richiesto dalla traccia.
