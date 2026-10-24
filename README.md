# SimpleMathGame

`SimpleMathGame` e una piccola app pensata per aiutare gli studenti della scuola elementare ad esercitarsi con le operazioni di base in modo semplice, graduale e giocoso.

L'idea nasce dal bisogno di rendere l'allenamento quotidiano piu leggero: il bambino puo scegliere un profilo, affrontare esercizi di addizione, sottrazione, moltiplicazione e divisione, e aumentare la difficolta man mano che acquisisce sicurezza. In questo modo l'app accompagna il percorso di apprendimento senza partire subito da esercizi troppo complessi.

I premi hanno un ruolo importante: invogliano i bambini a continuare a esercitarsi, a riprovare dopo gli errori e a migliorarsi un po' alla volta. Ogni ricompensa sbloccata diventa un piccolo obiettivo raggiunto, trasformando la pratica delle operazioni in una sfida positiva.

L'app funziona come pagina statica: basta aprire `index.html` nel browser, anche da cellulare. Non richiede installazione, build o server locale.

## Cosa permette di fare

Il gioco supporta piu utenti, cosi ogni bambino puo conservare le proprie impostazioni, statistiche e ricompense. Gli esercizi sono organizzati per operazione e difficolta, permettendo di partire da calcoli semplici e passare gradualmente a quelli piu impegnativi.

Durante il gioco vengono mostrate le statistiche sulle risposte corrette e sbagliate, insieme alla percentuale di successo. La modalita a tempo aggiunge una piccola sfida da 1 minuto, utile quando il bambino ha gia preso confidenza con una certa operazione e vuole provare a migliorare il proprio record.

Sono disponibili anche temi colore, suoni opzionali e una tastiera numerica personalizzata, pensata soprattutto per l'uso su dispositivi mobili.

## Come si usa

1. Apri `index.html` con un browser.
2. Crea un nuovo utente oppure selezionane uno gia presente.
3. Scegli operazione, difficolta e tema.
4. Attiva o disattiva le opzioni disponibili:
   - sfida a tempo;
   - punteggi;
   - suoni;
   - tastiera personalizzata.
5. Rispondi alle domande inserendo il risultato e premendo `Invio` o il tasto di conferma della tastiera a schermo.

## Progressione degli esercizi

Gli esercizi sono pensati per crescere gradualmente. Ogni operazione ha tre livelli: facile, medio e difficile. Questo permette di adattare l'esperienza al livello dello studente e di aumentare la complessita solo quando serve.

### Addizione

- Facile: numeri da 0 a 10.
- Media: primo numero fino a 20, secondo fino a 10.
- Difficile: entrambi i numeri fino a 20.

### Sottrazione

- Facile: numeri da 0 a 10, senza risultati negativi.
- Media: primo numero fino a 20, secondo fino a 10.
- Difficile: entrambi i numeri fino a 20.

### Moltiplicazione

- Facile: primo fattore da 0 a 5, secondo da 0 a 10.
- Media: entrambi i fattori da 0 a 10.
- Difficile: entrambi i fattori da 6 a 10.

### Divisione

- Facile: divisioni costruite dalle tabelline, con divisore fino a 5.
- Media: divisioni costruite dalle tabelline, con divisore fino a 10.
- Difficile: divisioni con resto.

## Premi e motivazione

I premi vengono sbloccati rispondendo correttamente agli esercizi. Ogni operazione ha una raccolta di ricompense collegata alle combinazioni completate.

Questo meccanismo aiuta a mantenere alta la motivazione: invece di vedere gli esercizi solo come compiti ripetitivi, il bambino puo percepirli come piccoli obiettivi da raggiungere. I premi non sostituiscono l'apprendimento, ma lo accompagnano con un feedback immediato e positivo.

## Temi disponibili

Per rendere il gioco piu personale e piacevole, il bambino puo scegliere tra diversi temi:

- Principessa delle favole.
- Principe azzurro.
- Ginnasta.
- Rockstar.
- Streghetta.
- Dinosauri.

## Dati salvati

Il gioco salva i dati nel `localStorage` del browser, quindi le informazioni restano disponibili sullo stesso dispositivo anche dopo aver chiuso la pagina. Vengono memorizzati:

- elenco utenti;
- configurazione dell'utente;
- statistiche per utente, operazione e difficolta;
- record della modalita a tempo;
- premi sbloccati.

I dati restano disponibili nello stesso browser finche non vengono cancellati manualmente o tramite le funzioni del gioco.

## File del progetto

- `SimpleMathGame.html`: contiene struttura HTML, stili CSS, logica JavaScript e liste dei premi.
- `README.md`: descrizione e istruzioni del progetto.

## Future evoluzioni

Tra le possibili evoluzioni dell'app ci sono nuove modalita di gioco pensate per rendere l'esercizio ancora piu vario e stimolante.

La modalità `sopravvivenza` potrebbe dare al giocatore un numero limitato di vite. Ogni errore farebbe perdere una vita, rendendo la partita piu intensa e spingendo il bambino a concentrarsi. Nel livello difficile la sfida potrebbe diventare ancora piu severa, con una sola vita disponibile.

La modalità `boss` potrebbe proporre tutte le operazioni una dopo l'altra, in ordine casuale, come una prova finale. Anche se l'idea sembra semplice, puo diventare un buon modo per verificare quanto il bambino riesce a passare da un tipo di calcolo all'altro senza perdere ritmo.

La modalità `sfida tra amici` potrebbe permettere a due o più bambini di giocare a turni alternati sullo stesso dispositivo, confrontando i risultati. Sarebbe un modo per trasformare l'esercizio in un piccolo momento condiviso.

## Note tecniche

Il progetto e realizzato senza dipendenze esterne. Tutta l'applicazione si trova nel file `SimpleMathGame.html` e usa:

- HTML per la struttura;
- CSS per temi, layout e animazioni;
- JavaScript vanilla per logica di gioco, salvataggio locale, timer, suoni e premi.

Il font viene caricato da Google Fonts, quindi l'aspetto tipografico può variare se il browser non ha accesso a Internet.

## Licenza

Questo progetto e distribuito con licenza MIT.

Puoi usare, copiare, modificare e condividere il software liberamente. Se lo redistribuisci, anche in forma modificata, devi mantenere il copyright originale e includere il testo della licenza MIT.

Vedi il file `LICENSE` per i dettagli.
