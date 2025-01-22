```markdown
# Tutorial introduttivo a R e all'uso della sua console interattiva

In questo breve tutorial vedremo:
- cos'è e come usare la console interattiva (o terminale interattivo) di R
- come utilizzare R come una calcolatrice
- cos'è una variabile e come crearla in R, o modificarne il valore

## Terminale Interattivo di R

R è spesso utilizzato tramite un terminale interattivo, noto anche come console R.
Il terminale interattivo è un ambiente in cui è possibile digitare comandi R e vedere immediatamente mostrati i risultati.
Questo è molto utile per testare rapidamente il codice e sperimentare.

Per avviare il terminale interattivo di R, è possibile:

1. Avviare R dall'icona corrispondente sul nostro PC
2. Avviare R da una finestra di terminale (o prompt dei comandi) e digitare `R` seguito da invio.
3. Avviare RStudio (un popolare ambiente di sviluppo integrato per R) e utilizzare la console R integrata nella sua interfaccia.

NOTA: tutte e tre le opzioni qui sopra riportate prevedono che tu abbia una versione di R installata e funzionante sul tuo PC.
Se poi scegliessi l'opzione #3, dovrai aver installato sul tuo PC anche RStudio.
Se così non fosse, puoi vedere come installare R e/o RStudio ad esempio [qui](https://rstudio-education.github.io/hopr/starting.html).
Una volta avviato il terminale interattivo, vedrete un prompt (solitamente `>`), dove potrete digitare i vostri comandi R.

Esempio di utilizzo del terminale interattivo:

```R
> 3 + 5
[1] 8
> x <- 10
> y <- x * 2
> print(y)
[1] 20
```

## Uso di R come Calcolatrice

R può essere utilizzato per eseguire semplici operazioni aritmetiche. Ecco alcuni esempi:

```R
# Somma
3 + 5

# Sottrazione
10 - 4

# Moltiplicazione
6 * 7

# Divisione
20 / 4

# Potenza
2^3

# Radice quadrata
sqrt(16)
```

## Variabili e Assegnazione

In R, possiamo memorizzare i risultati delle operazioni in variabili. Una variabile è un nome che rappresenta un valore. Utilizziamo il simbolo `<-` per assegnare un valore a una variabile.

```R
# Assegnazione di un valore a una variabile
x <- 5

# Utilizzo della variabile in un'operazione
y <- x + 3

# Stampa del valore della variabile
print(y)
```

## Esempio Completo

Mettiamo tutto insieme in un esempio completo:

```R
# Assegnazione di valori a variabili
a <- 10
b <- 2

# Operazioni aritmetiche
somma <- a + b
differenza <- a - b
prodotto <- a * b
quoziente <- a / b
potenza <- a^b
radice <- sqrt(a)

# Stampa dei risultati
print(paste("Somma:", somma))
print(paste("Differenza:", differenza))
print(paste("Prodotto:", prodotto))
print(paste("Quoziente:", quoziente))
print(paste("Potenza:", potenza))
print(paste("Radice quadrata:", radice))
```

## Conclusione

In questo tutorial, abbiamo visto come usare R come calcolatrice e abbiamo introdotto i concetti di variabile e assegnazione.

Buon divertimento con R!
```
