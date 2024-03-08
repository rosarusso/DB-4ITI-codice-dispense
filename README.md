# DB-4ITI-codice-dispense
Files per le esercitazioni

## Giovedì 14/03/24
1. Aprire Git bash
2. Posizionarsi nella cartella su cui si vuole lavorare
Esempio:
```cd \<path-to-Desktop\>```
dove \<path-to-Desktop\> va sostituito con il percorso del Desktop.
3. Clonare il repository corrente
`git clone https://github.com/rosarusso/DB-4ITI-codice-dispense.git`
4. Copiare il contenuto della cartella in una nuova cartella, che userete per il progetto da consegnare su Classroom.
**N.B.:** Il testo compreso tra "\<" e "\>" va sempre sostituito con ciò che è indicato all'interno (eliminare anche le parentesi uncinate).
```
mkdir \<nuova-cartella\>
cp DB-4ITI-codice-dispense/cB1_p182/* \<nuova-cartella\>
```

5. Andare nella cartella appena creata
```cd \<nuova-cartella\>```

5. Inizializzazione del nuovo repository locale e aggiunta dell’indirizzo del repository remoto nel repository locale
```
git init -b main
git remote add origin \<link-al-tuo-repository\>
```
È possibile utilizzare il repository creato durante l'ultima lezione.

git pull 

Modifica file
Add
Commit
Push