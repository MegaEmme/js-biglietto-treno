# Esercizio: Biglietto del treno

## Svolgimento

Il programma dovrà chiedere all'utente il numero di chilometri che vuole percorrere e l'età del passeggero.
Sulla base di queste informazioni dovrà calcolare il prezzo totale del viaggio, secondo queste regole:
- il prezzo del biglietto è definito in base ai km (0.21 € al km);
- va applicato uno sconto del 20% per i minorenni;
- va applicato uno sconto del 40% per gli over 65;
- L'output del prezzo finale va messo fuori in forma umana (con massimo due decimali, per indicare centesimi sul prezzo). Questo richiederà un minimo di ricerca;

### Nota bene

Prima di tutto, nel file README, indicare tutti i passaggi utili allo svolgimento del programma. Soltanto dopo scrivere la soluzione in JS.

---

## Passaggi

- Chiedo all'utente il *numero di km* e lo salvo in una variabile

- Chiedo all'utente l'*età* e la salvo in una variabile

- Calcolo il *prezzo del biglietto* e lo slavo il una variabile

- Applico solo due cifre decimali al *prezzo del biglietto*

- **Se** l'età è minore di 18 anni:

    - applico il 20% di sconto;
    - mostro il prezzo.

- **Altrimenti se** l'età è maggiore di 65 anni:

    - applico il 40% di sconto;
    - mostro il prezzo.

- **Altrimenti**:

    - mostro il prezzo.

---