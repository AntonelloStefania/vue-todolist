```
1-Creo markup statico;

2-Creo array oggetti;

3- Ciclo array nel dom per ottenere la lista di cose da fare;
    3.1- mostro a schermo la lista completa;

4- associo una funzione al tasto done che ne modifica la classe per segnare se il compito è stato svolto o meno;
    4.1- attribuisco il valore false a done e creo una funzione toggle;
    4.2- al click del pulsante il valore diventa l'opposto di sé stesso;
    4.2.1- ?SE il valore è false aggiungo classi per l'undone;
    4.2.2- :ALTRIMENTI aggiungo classi per il done;

5- collego il cambio di classi dovuto al pulsante done con le classi del testo della lista;

6- creo funzione per cancellare elementi dalla lista (al click del pulsante avviene lo splice dell'elemento i  nell'array)
    6.1- collego il pulsante delete alla funzione;

7- creo funzione per aggiungere un elemento all'array;
    7.1- dichiaro una variabile vuota nella quale far rientrare (con v-model) l'input dell'utente;
    7.2- creo una funzione che mi genera l'oggetto con il contenuto dell'input;
    7.3- pusho l'oggetto nell'array iniziale e svuoto il campo input;

8- creo funzione per modificare un elemento;
    8.1- assegno ad ogni oggetto una proprietà di controllo (stile toggle sul pulsante di modifica);
    8.2- una volta che il pulsante è premuto compare un input al posto del {{text}} nel quale posso inserire un nuovo testo;
    8.3- aggiungo l'evento del doppio click sul testo, ricollegandolo alla stessa funzione di modifica;
    8.4- evento tasto enter per sostituire la vecchia task con la nuova;
