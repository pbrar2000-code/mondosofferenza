REGISTRO LAVORO – ISTRUZIONI

CONTENUTO
- index.html: applicazione
- manifest.webmanifest: impostazioni installazione
- sw.js: supporto offline dopo il primo caricamento
- icone PNG

FUNZIONI
- Data selezionabile e preimpostata su oggi
- Inserimento/modifica di qualsiasi data passata
- Calcolo ore e minuti tra entrata e uscita
- Pausa facoltativa in minuti (predefinita 0)
- Totali giornalieri, settimanali, mensili e generali
- Storico per mese
- Stampa/salvataggio PDF mensile o completo
- Backup JSON esportabile e reimportabile

IMPORTANTE
I dati vengono salvati nel browser sul dispositivo (localStorage). Non cancellare i dati del browser senza prima esportare un backup. Il backup JSON consente di trasferire i dati manualmente.

INSTALLAZIONE SU IPHONE
Per installarla come app PWA, i file devono essere pubblicati su un indirizzo HTTPS.
Metodo semplice da PC Windows:
1. Crea un account GitHub se non ne hai uno.
2. Crea un nuovo repository pubblico chiamato registro-lavoro.
3. Carica tutti i file di questa cartella nella cartella principale del repository.
4. In Settings > Pages, scegli Deploy from a branch, branch main, folder /(root), e salva.
5. Attendi la pubblicazione e apri l'indirizzo GitHub Pages da Safari su iPhone.
6. Premi Condividi > Aggiungi alla schermata Home.

PDF
Nella schermata Resoconti premi il pulsante PDF. Si apre la finestra di stampa: scegli "Salva come PDF" (su iPhone usa il menu Condividi/Salva su File).

NOTA
Questa è una prima versione funzionante, non ancora pubblicata online. I dati restano sul dispositivo e non vengono sincronizzati automaticamente tra più dispositivi.
