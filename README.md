# EEX-Futures-Data
Il software EEX Futures Data è uno strumento progettato per recuperare e analizzare i dati futuri del mercato dell'energia dalla piattaforma EEX. Fornisce un'interfaccia automatizzata per estrarre informazioni cruciali sui prezzi dei future e le loro variazioni nel tempo.

## Caratteristiche Principali
- **Recupero Dati:** Estrae dati sui prezzi dei future dell'energia dalla piattaforma EEX in modo automatizzato.
- **Analisi Temporale:** Permette agli utenti di analizzare le variazioni dei prezzi nel tempo, facilitando la comprensione delle tendenze del mercato.
- **Supporto Multipiattaforma:** Utilizza la potenza di Selenium e ExcelPackage per garantire la compatibilità con diverse piattaforme.

## Tecnologie Utilizzate
- C++
- C#
- Selenium per l'automazione del web scraping.
- ExcelPackage per la manipolazione e l'analisi dei dati in formato Excel.

## Installazione
Per installare il software, seguire questi passaggi:
1. Scaricare il file [`EEXFuturesData.zip`](https://github.com/JimmyWoah/EEX-Futures-Data/raw/UpdatesVersion/EEXFuturesData.zip)
2. Estrarre i files in qualsiasi cartella del computer

## Primo avvio
1. Il driver di Chrome si installa automaticamente al primo avvio del software e si troverà al percorso `bin\chromedriver` della cartella di installazione.
3. Eseguire l'applicazione e premere il pulsante "Run" per avviare il recupero dei dati.
4. Per avviare una nuova istanza dopo aver eseguito un "Run", premere il pulsante "New session" prima di premere nuovamente "Run" (ad esempio se si volesse cambiare mese di riferimento `DateTime`

# Licenza
L'uso di questo software è libero, mentre i dati da esso estratti sono regolati dai termini del disclaimer presente alla pagina https://www.eex.com/en/disclaimer alla sezione `Website and content copyright`.

# Changelog

## [v2.2.6] - [02-11-2024]

### Aggiunte
- None

### Miglioramenti
- Ottimizzazione delle prestazioni per l'elaborazione dei dati
- Miglioramenti dell'interfaccia grafica del `form`
- Ottimizzazione della gestione degli `updates`
- Ottimizzazione download nuove versioni di `chromedriver`

### Risoluzione Problemi
- Risolto un bug per il quale il prompt del `chromedriver` non rilevava il parametro `hidden`

## [v2.1.6] - [18-03-2024]

### Aggiunte
- Aggiunta la gestione del processo di `chromedriver` in background

### Miglioramenti
- Ottimizzazione delle prestazioni per l'elaborazione dei dati
- Miglioramenti dell'interfaccia grafica del `form`

### Risoluzione Problemi
- Risolto un bug per il quale il `chromedriver` non interagiva correttamente con i `cookies`
- Risolto un bug per il quale il `chromedriver` non rilevava correttamente il disclaimer della pagina

## [v1.1.4] - [29-01-2024]

### Aggiunte
- Aggiunta la funzione di spostamento del `form`
- Aggiunta la gestione del processo di `chromedriver` in background
- Aggiunto controlli sulla validità del path del file Excel selezionato
- Implementata la funzione di controllo sulla presenza del file Excel aperto

### Miglioramenti
- Ottimizzazione delle prestazioni per l'elaborazione dei dati

### Risoluzione Problemi
- Risolto un bug per il quale il processo di estrazione dei dati non attendeva il caricamento della pagina
- Risolto un bug per il quale il `chromedriver` rimaneva in coda per la chiusura
- Risolto il problema di formattazione delle celle nel foglio Excel

## [v1.0.2] - [27-01-2024]

### Aggiunte
- Aggiunto un updater che ricerca gli aggiornamenti automaticamente.

### Miglioramenti
- Miglioramenti alle funzionalità di recupero e visualizzazione dei dati di mercato dalla European Energy Exchange (EEX).
- Ottimizzazione delle prestazioni per una rapida elaborazione dei dati.
- Migliorata l'interfaccia utente per una navigazione più intuitiva.
- Migliorati i controlli per garantire la corretta gestione delle licenze e dei diritti d'autore di EEX AG.

### Risoluzione Problemi
- Risolto problema di compatibilità con alcune versioni del driver di Chrome.
- Corretti bug minori relativi alla visualizzazione e all'aggiornamento dei dati.

## [v1.0.1] - [15-01-2024]

### Aggiunte
- Implementata funzionalità di recupero e visualizzazione dei dati di mercato dalla European Energy Exchange (EEX).
- Integrate diverse viste per fornire una panoramica completa dei dati, inclusi dettagli giornalieri, mensili, trimestrali e annuali.
- Aggiunta compatibilità con il download e l'aggiornamento automatico del driver di Chrome per garantire un'esperienza utente ottimale.

### Miglioramenti
- Ottimizzazione delle prestazioni per una rapida elaborazione dei dati.
- Migliorata l'interfaccia utente per una navigazione più intuitiva.
- Implementati controlli per garantire la corretta gestione delle licenze e dei diritti d'autore di EEX AG.

### Risoluzione Problemi
- Risolto problema di compatibilità con alcune versioni del driver di Chrome.
- Corretti bug minori relativi alla visualizzazione e all'aggiornamento dei dati.

## [v0.9.0] - [11-01-2024]

### First release
- Implementata la struttura di base dell'applicazione con la funzionalità di recupero dei dati dalla EEX.
- Aggiunta interfaccia utente per la selezione delle opzioni e la visualizzazione dei risultati.
- Funzionalità di salvataggio e caricamento dei dati su file Excel.
