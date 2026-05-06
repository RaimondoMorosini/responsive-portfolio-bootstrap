# Personal Portfolio

Questo repository ospita il codice sorgente del mio sito portfolio. Il progetto è stato sviluppato con l'obiettivo di creare una piattaforma leggera, manutenibile e accessibile.

## Stack Tecnologico
* **HTML5** strutturale.
* **Bootstrap 5**: utilizzato per il sistema di grid e la componentistica di base.
* **SASS**: impiegato per la gestione modulare degli stili, l'uso di variabili e la personalizzazione dei componenti di Bootstrap.
* **JavaScript (Vanilla)**: per le interazioni dinamiche essenziali.

## Metodologia e Standard
Il progetto segue criteri rigorosi di sviluppo web:

1. **Accessibilità (A11y):** Particolare attenzione è stata dedicata alla semantica HTML e al contrasto cromatico. Il codice viene costantemente monitorato tramite l'estensione **WAVE (Web Accessibility Evaluation Tool)** per garantire l'accessibilità a tutti gli utenti.
2. **Mobile-First Design:** L'interfaccia è stata progettata per essere completamente responsiva, garantendo un'esperienza d'uso fluida su dispositivi mobile, tablet e desktop.
3. **Ottimizzazione:** Utilizzo di SASS per mantenere il CSS organizzato e scalabile, riducendo le ridondanze nel codice finale.

## Strumenti di Validazione
* WAVE Evaluation Tool (Accessibilità)
* W3C Validator (HTML/CSS)
* Lighthouse (Performance e Best Practices)

## Installazione

Questo repository non include i file sorgente di Bootstrap per mantenere il progetto leggero. Per compilare il codice SASS correttamente, segui questi passaggi:

1. Scarica il codice sorgente di **Bootstrap 5.3.x** dal [sito ufficiale](https://getbootstrap.com/docs/5.3/getting-started/download/#source-files).
2. Estrai il contenuto del pacchetto.
3. Rinomina la cartella estratta in `bootstrap-5.3.8` (o assicurati che il percorso corrisponda a quello importato in `assets/scss/style.scss`).
4. Posiziona la cartella dentro il percorso `assets/`.

Il percorso finale dovrebbe essere: `assets/bootstrap-5.3.8/`.
