# 🏁 DreamDrive 

Applicazione web che permette la prenotazione di Noleggio Auto o Track-Day in circuiti autorizzati.

# 🏗 Tecnologie utilizzate

Front-end:

* HTML 5
* JavaScript
* CSS 3

Back-end:

* Node.js
* Express.js

Database:

* MySQL

# Funzionalità principali

# 👁 Admin

L'admin dell'applicazione può visualizzare gli utenti registrati con le relative prenotazioni attive, visionare e cancellare le recensioni, aggiungere auto al database e alla gallery dedicata, rispondere ai contatti Q&A e eliminare account di utenti, il tutto attraverso la **Dashborard Admin**.

# 📊 Dashboard Admin

La dashboard admin presenta una sidebar con 5 pulsanti (Prenotazioni, Auto, Utenti, Recensioni, Contatti) dove:

* Prenotazioni: permette all'admin di controllare il numero totale di prenotazioni, ID dell'utente con relativa mail, tipo di servizio, auto scelta e data prevista dell'evento, dando anche la possibilità di cancellarle.

* Auto: permette all'admin di aggiungere, eliminare o modificare un auto. E' possibile caricare immagini andando a riempire campi descrittivi inerenti a marca, modello, nazione e motore.
  
* Utenti: permette all'admin di visionare gli utenti registrati, dando anche la possibilità di eliminarli ( a propria discrezione ).

* Recensioni: permette all'admin di visionare le varie recensioni, dando la possibilità di eliminarle.

* Contatti: permette all'admin di leggere i vari messaggi lasciati dagli utenti nel form dedicato, potendo anche rispondere o cancellarli.

# 👨‍💻 Utente registrato

L'utente, una volta registrato può selezionare il servizio che più desidera, scegliendo l'auto e il numero di giorni per il noleggio o l'auto e il circuito in caso di track-day 

# 🪪 Dashboard Utente

All'interno del profilo utente sono disponibili le informazioni riguardo l'utente loggato, come email e prenotazioni attive con relativi importi e possibilità di cancellazione delle stesse. 
E' presente una dashboard utente che contiene il tutto; inoltre se non ci sono prenotazioni attive, è possibile effettuare la prima prenotazione direttamente dalla dashboard utente. 

# 👤 Utente non registrato 

L'utente non registrato ha la possibilità di navigare all'interno del sito per scoprire le tipologie di servizio, visionare una gallery dove sono contenute le varie auto disponibili con relativi prezzi calcolati in base al tipo di servizio, leggere le recensioni degli utenti e creare un nuovo account.

# 📥 Procedura di installazione

```bash
# Clonare la repo di GitHub

git clone https://github.com/timothy-giolito/DreamDrive.git

# Entrare nella directory del progetto

cd DreamDrive

# Creare un file .env

PORT=3000
DB_NAME="dreamdrive.db"
SECRET_SESSION="dreamdrive"
NODE_ENV="development"

# Installare le dipendenze

npm install

# Avviare l'applicazione

npm run dev

```

L'applicazione sarà disponibile, in locale,  al link:  *http://localhost:3000*

# 🛠 Account di test

**Admin**

* Email: admin@dreamdrive.com 
* Password: admin1234

**Utente**

* Email: marco.rossi@gmail.com
* Password: marco1234

# 📼 Link al video di presentazione

https://youtu.be/71yw4ih7IfA

# 🌐 Link di deploy 

https://dreamdrive-motorsport-rent.up.railway.app

---

<div align="center">

**📚 Progetto per il corso di Metodologie di Programmazione Web - A.A. 2024/2025**

</div>
