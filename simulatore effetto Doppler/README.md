# Simulatore effetto Doppler

## Descrizione
Questo progetto è un simulatore interattivo dell'effetto Doppler applicato al suono di un'ambulanza.
Permette di vedere come cambia la distanza tra i fronti d'onda e come varia il suono percepito quando l'ambulanza si avvicina o si allontana dall'osservatore.

## Link al sito
[Apri il simulatore](https://simulatore-effetto-doppler.pages.dev/)

## Funzionalità
1. Regolazione della velocità dell'ambulanza da -20 m/s a +20 m/s.
2. Aggiornamento in tempo reale delle onde e della frequenza percepita.
3. Visualizzazione della compressione delle onde davanti all'ambulanza e della loro distensione sul lato opposto.
4. Riproduzione del suono dell'ambulanza tramite l'icona dell'altoparlante.
5. Utilizzabile anche da telefono.

## Utilizzo
Sposta la barra per cambiare la velocità dell'ambulanza:
- valori positivi: l'ambulanza si avvicina all'osservatore
- valori negativi: l'ambulanza si allontana
- valore zero: l'ambulanza è ferma

Premendo l'icona dell'altoparlante si può attivare o disattivare il suono.

## Implementazione
Il simulatore è contenuto in una singola pagina HTML con CSS e JavaScript.
Le onde vengono disegnate su canvas partendo dalle diverse posizioni in cui sono state emesse, così l'accumulo e la distensione risultano visibili. Il suono utilizza una registrazione reale e cambia durante lo spostamento della barra.

Le differenze visive e sonore sono amplificate rispetto ai valori reali, altrimenti con velocità così basse sarebbero difficili da notare.
