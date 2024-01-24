# Analisi E-commerce - Progetto 

TRACCIA

Sei un Data Analyst / Data Engineer presso un'azienda di e-commerce e l'azienda richiede un'analisi completa sull'andamento della propria attività. In particolare, si richiede uno studio sull'andamento delle vendite, dell'inventario e dei prodotti.

I dati dell'azienda sono archiviati nel database BigQuery seguente: bigquery-public-data.thelook_ecommerce. Il tuo compito è interrogare ed estrarre i dati, effettuare eventuali pulizie necessarie, manipolarli, analizzarli e creare una presentazione accattivante dei risultati in Tableau, da consegnare all'azienda.

Il tuo risultato finale dovrebbe fornire approfondimenti su argomenti specifici:

Attività sul sito web: La tabella degli eventi contiene dati a livello di sessione sul comportamento online degli utenti. Esempi: quali parti del sito web sono più visitate? Da dove proviene il traffico? ...

Composizione demografica: La tabella degli utenti include informazioni sui clienti. Esempi: età/sesso dei tuoi clienti, paesi/città popolari, clienti particolarmente fedeli (acquisti multipli), ...

Performance del prodotto: La tabella dei prodotti descrive il catalogo dei prodotti così come i costi e i prezzi al dettaglio di ciascun elemento. Tuttavia, è nella tabella degli ordini che potrai vedere quante volte è stato venduto un determinato prodotto. Esempi: prodotti più/meno venduti, prodotti che generano il maggior/minor fatturato, preferenze per genere/età per determinati prodotti/categorie, ...

Stato dell'inventario: La tabella degli oggetti di inventario mostra la disponibilità di magazzino e la tabella dei centri di distribuzione mostra la posizione di ciascun centro di distribuzione. Esempi: ci sono problemi di disponibilità per qualche prodotto/categoria? C'è un centro di distribuzione problematico? ...

Altri approfondimenti: Non dimenticare la tabella degli ordini, che fornisce informazioni a livello di ordine sulle transazioni dei clienti.

Per ampliare la tua analisi, assicurati di integrare dati aggiuntivi da un'API, come le coordinate geografiche delle località menzionate nel dataset, o le condizioni meteorologiche per quei giorni e zone, i tassi di cambio o qualsiasi altro dato che ritieni possa portare più valore all'analisi.

Assicurati di preparare un data mart per ciascuno dei temi elencati e per qualsiasi altro argomento che affronterai, in modo che i colleghi nei dipartimenti correlati possano accedere ai dati di loro interesse e solo a quelli.

Infine, come spiegato in precedenza, utilizzerai le intuizioni acquisite dalla tua analisi per preparare una presentazione sotto forma di storia, in cui spiegherai il contesto, le intuizioni trovate, la loro interpretazione e eventuali raccomandazioni/azioni future, spiegando come possono essere sfruttate per migliorare il futuro del business.

Nota: per questo progetto, dovresti utilizzare tutte e tre le seguenti tecnologie: SQL (raggruppamento, unione dei dati, data marts, ecc.), Python (pulizia, esplorazione, analisi, recupero di API, ecc.) e Tableau (visualizzazione e presentazione).

IL PROGETTO E STATO REALIZZATO IN 2 SETTIMANE

## Documentazione Scrum - Progetto Analisi E-commerce
Scopo del Progetto
Il progetto mira a condurre un'analisi completa sull'andamento delle vendite, dell'inventario e dei prodotti di un'azienda di e-commerce utilizzando i dati memorizzati nel database BigQuery. L'obiettivo finale è fornire approfondimenti chiave attraverso visualizzazioni in Tableau e raccomandazioni per migliorare le prestazioni aziendali.

## Backlog del Prodotto


Elementi del Backlog:
1. Visualizzazione e pulizia dei dati in BigQuery

2. Creazione di datamart per attività specifiche (attività sul sito web, composizione demografica, ecc.)

3. Creazione di visualizzazioni e datamart in Tableau

### Sprint 1

Backlog di Sprint:
1. Pianificazione e preparazione dell'ambiente di sviluppo. Google drive, Google bigQuery, colab, git.
2. Query iniziali in BigQuery per visualizzare e pulire i dati.
la difficoltà è stata trovare un modo che ci permettesse di recuperare tutti i dati in locale, considerando che i dati telativi alle attività sul sito web non erano in linea con il massimo permesso da bigQuery; abbiamo qundi deciso di utilizzare query che fltrassero tali eventi per età.

Sprint Review:
##### Presentazione delle query iniziali con visualizzazioni preliminari.
Sprint Retrospective:
##### il filtro dei dati per mantenere l'integrità ci ha dato modo di riflettere sull'analisi, la quale poteva essere sviluppata anche per range di età relative a vendite e attivita del sito per future azioni di marketing.

### Sprint 2


Backlog di Sprint:
1. Pulzia dei dati ( mancanti non corretti) utilizzando colab e la scrittura in Python
2. Riordino dei dati e importazione dei csv in locale.

Sprint Review:
##### presentazione dei csv da utilizzare per l'utilizzo dell'analisi e scelta della presentazione del progetto

Aggiornamento del Product Backlog.

4. Utilizzo di Python e Flask per creazione di un gestionale aziendale 

### Sprint 3

Backlog di Sprint:
1. Analisi di performance del prodotto utilizzando dati dagli ordini e integrazione in datamart.
2. Creazione di visualizzazioni iniziali in Tableau.
Sprint Review:
Presentazione delle analisi di performance del prodotto e delle prime visualizzazioni in Tableau.
Sprint Retrospective:
Identificazione di miglioramenti nelle metodologie di lavoro.

### Sprint 4


Backlog di Sprint:
1. Completa integrazione dei dati e creazione del gestionale 
2. Miglioramento delle visualizzazioni in Tableau.
3. Creazione di autentificazione per poter accedere ai dataMart nel gestionale, 
4. Creazione file json per permettere di scaricare i dati del gestionale.
Sprint Review:
Presentazione dell'analisi completa e delle visualizzazioni ottimizzate.
Sprint Retrospective:
Valutazione complessiva del progetto.

Conclusioni
Si potrebbe realizzare un autentificazione per reparto cosi da mantenere la discrezione tra i diversi dataMart.
Per le conclusioni sull'analisi e sui consigli forniti all'azienda si raccomanda di visionare il gestionale.

N.B. il presente è una descrizone delle metodoligieutilizzate e la suddivisione del lavoro.