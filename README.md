#Cafe sales Data Cleaning & Recovery

Questo progetto dimostra il processo di pulizia e ripristino di un dataset di vendita retail sporco.
Il duplice obiettivo era quello di preservare l'integrità del database e quello di recuperare quante più informazioni
possibili tra i valori nulli. 

Di fatto l'applicazione di funzioni algebriche e il corretto utilizzo delle informazioni di partenza ha permesso il recupero di 
una consistente percentuale di dati.

L'uso delle librerie 'pandas', 'matplotlib' e 'numpy' non è stato un mero esercizio di stile: grazie al loro utilizzo è stato
possibile esplorare funzionalità più o meno complesse di Python e la rappresentazione ordinata dei dati.

#Fase 1

Eliminate le colonne inutili, modifica del tipo di variabili, eliminati i duplicati;

#Fase 2

Gestione di NaN, ERROR e missing value di talune colonne evitando l'utilizzo di drop.na

#Fase 3

Recupero delle informazioni sugli oggetti venduti risalendo al loro costo unitario (utilizzo strategico delle info disponibili)
(utilizzo di numpy)

#Fase 4 

La correlazione tra il prezzo unitario, la spesa totale e la quantità venduta è stata tradotta in una forma algebrica capace
di restituire circa 1000 dati (10% del database)

#Fase 5

Esempio di analisi dei dati e della loro rappresentazione tramite matplotlib,
due colonne vengono poste in relazione con groupby() e il loro risultato viene mostrato tramite un grafico a barre.
