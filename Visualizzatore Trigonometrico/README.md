# Visualizzatore Trigonometrico

## Sito
[Apri il visualizzatore](https://visualizzatore-trigonometrico.pages.dev/)

## Descrizione
Il seguente è un visualizzatore grafico per studiare la trigonometria, mettendo a confronto la circonferenza trigonometrica con il grafico cartesiano della funzione scelta.

Il valore di x può andare da -10π a 10π, con intervalli di π/8. È possibile usare lo slider oppure scrivere direttamente il moltiplicatore di π, quindi ad esempio 1,5 corrisponde a 1,5π.

## Funzionalità
1. Visualizzazione contemporanea della circonferenza trigonometrica e del piano cartesiano.
2. Scelta tra seno, coseno, tangente, cotangente, arcoseno, arcocoseno e arcotangente.
3. Aggiunta di più punti, ognuno con un colore diverso, per confrontare più valori nello stesso momento.
4. Visualizzazione del valore di x e del relativo valore di y.
5. Tema chiaro e scuro, memorizzato dal browser.
6. Interfaccia adattata anche a iPhone, sia in verticale che in orizzontale.

## Utilizzo
1. Seleziona la funzione dal menu a tendina.
2. Sposta lo slider oppure inserisci il valore nel campo di testo senza scrivere π.
3. Per inserire altri valori premi "Aggiungi un punto".

Sono accettati anche valori frazionari come 3/8. Se un valore non appartiene al dominio reale della funzione viene indicato come non definito.

## Implementazione
Il progetto è contenuto interamente in un singolo file HTML e non richiede librerie esterne. I due grafici sono disegnati con Canvas e si aggiornano insieme ad ogni modifica dei punti.
