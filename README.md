## Introduzione

ISIQuiz è un progetto che nasce con l’intento di aiutare uno studente a ripassare i concetti chiave di un corso universitario e
verificare la completezza delle conoscenze acquisite durante lo studio.
L'obiettivo è stato raggiunto con il design di un'applicazione con domande a risposta multipla e feedback.
Lo scopo di ISIQuiz è quindi quello di gamificare il ripasso pre-esame attraverso uno strumento stimolante
che permetta allo studente di sentirsi più sicuro sulla sua preparazione, di collaborare aggiungendo domande personalizzate e di tracciare i propri progressi.

## Come giocare

Per eseguire l'applicazione sul computer, fare doppio clik, o _tasto-destro->apri con->Java_

Se non viene aperta, digitare nel terminale nella stessa cartella:
```bash
java -jar ISIQuiz.jar
```

Per l'applicazione è richiesto: Java versione 8 o successiva

### Guida utente
Una volta aperta l'applicazione, viene visualizzato un menu iniziale con:

__Gioca__:
Seleziona almeno un corso per poter iniziare una partita con quiz riguardanti i corsi indicati.
Successivamente, scegli la modalità di gioco:
- _partita standard_: 10 quiz, ciascuno da rispondere in massimo 15 secondi; ogni quiz ha 4 possibili risposte, 1 sola risposta è corretta; scoprirai la risposta corretta dopo ogni quesito
- _partita blitz_: rispondi a più quiz possibili in 2 minuti (120 secondi); ogni quiz ha 4 possibili risposte, 1 sola risposta è corretta; scoprirai le risposte corrette solo al termine della partita
- _partita personalizzata_: scegli il numero di quiz e il tempo massimo (in secondi) per rispondere a ciascuno; ogni quiz ha 4 possibili risposte, 1 sola risposta è corretta

Al termine di una partita c'è il riepilogo con: 
- il numero totale di domande risposte correttamente
- il numero totale di punti guadagnati
- per ogni quiz nel gioco:
  - corso in cui è inserito
  - risposta data
  - risposta corretta, se quella data è errata o mancante

__Statistiche__:
Visualizza le statistiche riguardanti ai tuoi ripassi:
- relative ad un corso selezionato
- relative ad un quiz selezionato tra quelli del corso indicato
- globali
 
Per ciascuna tipologia di statistica ci sono:
- punti acquisiti
- quiz risposti
- risposte corrette
- precisione (%)
- tempo medio di risposta (sec)

__Impostazioni__:
Per poter apportare modifiche nelle impostazioni generali:
- Importa quiz: importa un file (formato JSON) contenente nuovi corsi e quiz
- Esporta quiz: esporta il file (formato JSON) contenente tutti i corsi con i relativi quiz
- Aggiungi corso: inserisci un nuovo corso
- Aggiungi quiz: inserisci nuovi quiz ad un determinato corso, così da poterti esercitare su più argomenti o domande personalizzate
- Modifica corso: cambia le informazioni di un corso
- Modifica quiz: cambia il quiz di un corso

__Esci__:
Per uscire dall'applicazione

## Team

I membri del team di sviluppo di questo progetto sono:
- Daniele Gambaletta
- Igor Lirussi
- Riccardo Omiccioli
- Cecilia Teodorani

<div align="center">
    <img src="https://github.com/ISIQuiz/ISIQuiz-Report/raw/gh-pages/Extra/ISIQuizLogoLineTransparent.png" width="80%">
</div>
