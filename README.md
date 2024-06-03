
# Progetto di Messagistica con Redis

Questo progetto è una semplice applicazione di chat implementata utilizzando tkinter per l'interfaccia grafica e Redis per il database backend. L'applicazione consente agli utenti di registrarsi, accedere, gestire i contatti, inviare e ricevere messaggi e attivare una modalità silenziosa per evitare disturbi.


## Acknowledgements

 - [Sito Ufficiale di Redis](https://redis.io/)


## Authors

- [Mario Campana](https://github.com/Mario030901)
- [Francesco Iuorio](https://github.com/FrancescoIuorioITS)
- [Emanuele Miranda](https://github.com/emamira02)
- [Michele Passarelli](https://github.com/prettySun69)


## Video di Dimostrazione

[Link Google Drive](https://drive.google.com/drive/folders/1vAty3u3EGcsRGIRZl7gtY0qMhdxYLPez)


## Clonazione Repository

```bat
    https://github.com/Mario030901/whatsapp_project.git
```

## Prerequisiti

- Python 3.12.3
- Server Redis

## Librerie Python 
- redis
- tkinter
- datetime


## Installazione:

Installa Redis sul tuo sistema attraverso Docker. Le istruzioni possono essere trovate sul sito ufficiale di Redis.
Installa i pacchetti Python richiesti usando pip:
```bash
    pip install redis
```

Assicurati che il modulo startdb.py sia nella stessa directory dello script principale. 
Questo moduli dovrebbe contenere il codice necessario per inizializzare la connessione al database di Redis.

Se si desiderano avere maggiori informazioni sulla struttura del database, è possibile scaricare dal sito di Redis l'applicazione Redis Insight, che offre una comoda e veloce interfaccia grafica.

## Utilizzo:

Esegui lo script principale usando Python:
```bat
    python main_script.py
```

## Funzionalità:
Registrazione Utente
Gli utenti possono registrarsi fornendo un nome utente univoco e una password. Se il nome utente esiste già, viene mostrato un messaggio di errore.

## Accesso Utente:
Gli utenti possono accedere fornendo il proprio nome utente e password. Se le credenziali non sono valide, viene mostrato un messaggio di errore.

## Modalità Silenziosa:
Gli utenti possono attivare o disattivare la modalità silenziosa. Quando la modalità silenziosa è attivata, l'utente non riceverà messaggi.

## Gestione Contatti:
Gli utenti possono gestire i propri contatti aggiungendo nuovi contatti o visualizzando quelli esistenti nella loro rubrica.

## Messaggistica:
Gli utenti possono inviare messaggi ai contatti nella loro rubrica. Possono anche visualizzare i messaggi scambiati con un contatto specifico.

## Ricezione Messaggi in Tempo Reale:
L'applicazione include funzionalità per la ricezione dei messaggi in tempo reale utilizzando Redis Pub/Sub.






