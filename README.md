## Composer | Performer | Live Electronics | Programmer

Benvenuti!

---

# Ambiente 1: Elaboratore58
### Performance Interattiva per Supporto Materico, Computer Vision e Live Electronics

L’opera nasce come interpretazione di **Elaboratore58** dell’artista **Gianmaria Potenza**. Il progetto è concepito per essere applicato all'intero corpus delle opere dell’artista, sia in contesti performativi che installativi, costruendo un percorso compositivo a partire dalla grammatica interna dell'opera stessa.

####  Visione Artistica e Modalità Esecutive
Il progetto propone un percorso che va dalla creazione dell’opera fisica alla sua completa digitalizzazione: un dialogo continuo tra realtà sonora, virtuale e ritorno al reale.

* **Dimensione Ritmica:** L'intreccio di più suoni genera ritmi che si deformano e si frammentano fino a perdere coerenza, per poi convergere verso la precisione matematica del computer.
* **Interazione Multimodale:** L’elaborazione è sia uditiva che visiva. Attraverso segni e materiali riconosciuti dall’Intelligenza Artificiale, il performer (o il pubblico) "scalfisce" il supporto su cui viene proiettata l’opera, rendendo visibile il dialogo tra gesto, musica e macchina.
* Performance vs Installazione:
    * In sede **performativa**, l'esecutore segue uno schema di scene prestabilito mantenendo la propria estetica. 
    * In sede **installativa**, è il pubblico a scegliere quali scene attraversare, trasformando la composizione in un’improvvisazione semi-aperta.
* **Memoria finale:** Al termine, il controllo passa al computer. Restano visibili i segni lasciati sul supporto virtuale: traccia finale e memoria dell’interazione avvenuta.

####  Architettura Tecnica del Sistema
Per rendere possibile questa "scalfitura" digitale del supporto, il sistema utilizza:

* **Computer Vision (AI):**
    * **MediaPipe:** Tracciamento di 21 punti della mano (Landmarkers) per l'analisi del gesto.
    * **YOLO (You Only Look Once):** Riconoscimento in tempo reale (45+ FPS) di strumenti specifici (Scalpello, Raschietto, Sega, Carta Abrasiva).
* **Data Flow:** Protocollo **OSC** per la comunicazione tra l'ambiente Python e il motore di sintesi.
* **Audio Engine:** Sviluppato in **Max/MSP**, utilizza l'oggetto *entrymatcher* per la gestione dei segni e la spazializzazione sonora.
* **Setup Hardware:** Sistema a 3 camere (2 webcam per il tracking, 1 videocamera zenitale per la documentazione).

---

### Competenze & Strumenti
* **Linguaggi:** Python, Max/MSP.
* **Tecnologie:** Computer Vision, Machine Learning per la musica, OSC.
* **Audio:** LiveElectronics.

---

### 📂 Documentazione e Risorse
Per approfondire gli aspetti compositivi e i requisiti tecnici del sistema:
* [**Partitura e Schemi Esecutivi (Google Drive)**](https://drive.google.com/drive/folders/18VMUkDlnxJY4QALqjEVSkM8_VhIa0Hnx?usp=sharing)
* [**Codici e Patch disponibili (Google Drive)**](https://drive.google.com/drive/folders/1UqR3JRdcOenO8MQ--DNvixIVx6fs2b53?usp=sharing)
* [**Video del concerto (YouTube)**](https://www.youtube.com/watch?v=u7rTTMUEv-U&t=2163s)
* [![Video della Performance](https://img.youtube.com/vi/u7rTTMUEv-U/0.jpg)](https://www.youtube.com/watch?v=u7rTTMUEv-U&t=2163s)
---

### Contatti & Info
📍 **Conservatorio di Musica "F. Morlacchi"**, Perugia  
📧 [e.costantino@studenti.conservatorioperugia.it]  
🔗 [https://elisabettacostanti.wixsite.com/elisabetta-costantin]

---
*© 2026 Elisabetta Costantino - Progetto ispirato alle opere di Gianmaria Potenza.*
