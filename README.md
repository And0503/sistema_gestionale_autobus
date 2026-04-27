# sistema_gestionale_autobus
Sistema gestionale per una compagnia di autobus interregionali. Supporta la prenotazione con invio automatico di email di conferma e resoconto, oltre che l’emissione di biglietti, includendo controlli sulle disponibilità di posti e bagagli. Consente l'invio automatico di email di report delle vendite dei biglietti dell'ultima settimana. Comprende una duplice interfaccia distinta per operatori e utenti finali, con funzionalità dedicate.

Include:
1. Interfaccia grafica sviluppata con WindowBuilder o in alternativa interfaccia testuale
2. Backend completo
3. Invio automatico di email tramite server SMTP di Libero
4. Database h2

---
## 👥 Autori
- Andrea Tito - https://github.com/And0503
- Claudia Castellano - https://github.com/ClaudiaCastellano
- Gaetano Ruocco - https://github.com/gaetanor
---

---
## ⚙️ Guida tecnica
---

---
### 🛠️ Tecnologie
- Eclipse 2021-12 4.22.0
- Java 1.8.0_311
- h2 2.1.214 (embedded)
- Junit 4.13.2
---

---
### 📁 Struttura del repo

| File / Package | Descrizione |
|----------------|-------------|
| `boundary` | Interfacce testuali e grafiche |
| `control` | Logica applicativa |
| `database` | Contiene le classi DAO e `DBManager` per la gestione della connessione al database |
| `entity` | Definizione delle entità del dominio |
| `exception` | Eccezioni personalizzate |
| `test` | Test JUnit per le principali funzionalità del sistema |
| `README.md` | Documentazione del progetto |
| `Progettazione.pdf` | Documento di analisi dei requisiti, progettazione e testing |

---

---
### 🚀 Come eseguire il progetto
1. Scaricare h2
2. Installare ed aprire Eclipse
3. Creare una cartella di lavoro
4. Effettuare i seguenti passaggi:
    - Tasto destro sul progetto
    - Properties
    - Java Build Path
    - Libraries
    - Add External JARs...
    - Classpath
    - h2-2.1.214
5. Importare il progetto nella cartella di lavoro
6. Eseguire il programma avviando:
    - `MainMenu.java` per interfaccia grafica
    - `BoundaryCliente.java`, `BoundaryImpiegato.Java` o `BoundaryTempo.java`, a seconda dei casi, per interfaccia testuale
---
