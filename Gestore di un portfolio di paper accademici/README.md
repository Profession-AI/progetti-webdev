# Gestore di un Portfolio di Paper Accademici

## Caso d'Uso Aziendale: ScholarPort

### Introduzione all'Azienda
ScholarPort è una piattaforma dedicata ai ricercatori accademici per gestire in modo semplice ed efficace il loro portfolio di pubblicazioni. L'obiettivo è creare uno strumento che permetta ai ricercatori di organizzare i propri articoli, tracciare citazioni e presentare il proprio lavoro in un formato professionale e intuitivo.

### Problema
I ricercatori spesso si trovano a dover gestire manualmente i loro articoli accademici, distribuendo informazioni tra vari file o piattaforme non centralizzate. Questo approccio può essere inefficiente, portando a difficoltà nella ricerca di specifiche pubblicazioni o nella gestione delle citazioni. Inoltre, la mancanza di un'interfaccia moderna e accessibile rende la presentazione del portfolio meno efficace.

### Obiettivo del Progetto
L'obiettivo è sviluppare un gestore di portfolio accademico che consenta:

1. L'inserimento manuale di dati per ogni articolo accademico, inclusi:
   - Titolo
   - Autori
   - Abstract
   - Data di pubblicazione
   - DOI (Digital Object Identifier)

2. La possibilità di aggiungere e visualizzare citazioni per ogni articolo.
3. La navigazione intuitiva tra gli articoli tramite filtri e ricerca.
4. Un'interfaccia front-end user-friendly sviluppata con HTML, CSS, JavaScript e React.
5. Un back-end scalabile per la gestione dei dati, implementato in Node.js.

### Benefici Attesi
- **Centralizzazione:** Tutti gli articoli e le citazioni gestiti in un'unica piattaforma.
- **Professionalità:** Un portfolio ben strutturato per presentare il lavoro accademico.
- **Efficienza:** Navigazione e ricerca rapide, anche con grandi volumi di articoli.

### Specifiche del Progetto
#### **Front-end**
1. **Tecnologie:** HTML, CSS, JavaScript, React.
2. **Funzionalità:**
   - Pagina principale con elenco degli articoli.
   - Form per l'inserimento e l'editing di un articolo.
   - Pannello per la visualizzazione delle citazioni associate a un articolo.
   - Ricerca e filtro degli articoli per titolo, autore o anno di pubblicazione.

#### **Back-end**
1. **Tecnologie:** Node.js
2. **Database:** MongoDB o un'alternativa SQL.
3. **Funzionalità:**
   - API REST per:
     - Creare, leggere, aggiornare e cancellare (CRUD) articoli e citazioni.
     - Gestire filtri e query per la ricerca.
   - Gestione delle relazioni tra articoli e citazioni.
   - Autenticazione utente (opzionale, per proteggere i dati del portfolio).

### Consegna
1. **Requisiti Front-end:**
   - Una Single Page Application (SPA) realizzata con React.
   - Layout responsive che si adatta a dispositivi desktop e mobile.

2. **Requisiti Back-end:**
   - API REST funzionanti con tutte le operazioni CRUD.
   - Gestione dei dati tramite un database adeguato (MongoDB o SQL).

3. **Integrazione:**
   - Collegamento tra front-end e back-end per un flusso dati continuo.

4. **Test:**
   - Almeno 5 test funzionali per ogni componente chiave (form di inserimento, ricerca, navigazione, ecc.).

5. **Documentazione:**
   - Istruzioni su come installare, configurare ed eseguire il progetto.
   - Commenti chiari nel codice per spiegare le scelte implementative.



