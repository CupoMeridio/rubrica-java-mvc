# 📒 Rubrica per PC  
### Università degli Studi di Salerno (UNISA)  
**Corso di Ingegneria Informatica**  
**Gruppo 02 - Progetto Universitario**  

---

## 🚀 Descrizione del Progetto  
Questo progetto consiste nello sviluppo di un'applicazione desktop dedicata alla gestione di una rubrica. L'obiettivo è fornire uno strumento intuitivo e funzionale che consenta agli utenti di salvare, organizzare e ricercare facilmente i contatti.  

## 📋 Funzionalità Principali  
- **Registrazione e Login:** Accesso sicuro con credenziali utente.  
- **Gestione Contatti:** Aggiunta, modifica, eliminazione e visualizzazione dei contatti.  
- **Ricerca Avanzata:** Filtri personalizzati per trovare rapidamente i contatti.  
- **Esportazione/Importazione:** Salvataggio dei contatti in formati standard (es. CSV).  
- **Interfaccia User-Friendly:** Utilizzo di JavaFX per un'esperienza utente moderna e accattivante.  

## 🛠️ Tecnologie Utilizzate  
- **Linguaggio di Programmazione:** Java  
- **Database:** PostgreSQL  
- **Framework e Librerie:** JavaFX, dotenv-java  
- **Sicurezza:** BCrypt per hash delle password, dotenv per gestione credenziali  
- **Strumenti di Versionamento:** Git/GitHub  
- **Gestione del Progetto:** MAVEN  
- **IDE Utilizzato:** NetBeans 23  

## 👥 Team di Sviluppo  
Il progetto è stato realizzato dal **Gruppo 02**, composto da 4 studenti del corso di Ingegneria Informatica presso l'Università degli Studi di Salerno (UNISA):  

- **Postiglione Vittorio**  
- **Quaranta Valeria**  
- **Sanzari Mattia**  
- **Zouhri Anuar**  

## 📦 Installazione  

### **Clonare il repository:**  
```bash  
git clone https://github.com/CupoMeridio/rubrica-java-mvc.git  
```  

### **Configurare il database:**  
L'applicazione utilizza un database online tramite i servizi offerti da [Aiven](https://aiven.io), pertanto non è necessario configurare un database locale.

### **Configurazione delle variabili d'ambiente:**  
Per motivi di sicurezza, le credenziali del database sono gestite tramite variabili d'ambiente. Segui questi passaggi:

1. **Copia il file di esempio:**  
   ```bash
   cp .env.example .env
   ```

2. **Modifica il file .env** con le tue credenziali del database:
   ```
   DB_HOST=your-database-host.com
   DB_PORT=5432
   DB_NAME=your-database-name
   DB_USER=your-username
   DB_PASSWORD=your-password
   DB_SSL=require
   ```

3. **⚠️ IMPORTANTE:** Il file `.env` è già incluso nel `.gitignore` per evitare di caricare le credenziali su GitHub. Non rimuoverlo mai dal `.gitignore`.  

### **Compilare ed eseguire il progetto:**  
Aprire il progetto in NetBeans 23. MAVEN gestirà automaticamente le dipendenze.  

### **File eseguibile disponibile:**  
Nel repository è disponibile la prima release del progetto. Per eseguire il file .jar è necessario scaricare ed installare l'ambiente Java. Puoi scaricarlo dal seguente link: [Java Downloads | Oracle](https://www.oracle.com/java/technologies/javase-downloads.html).  

## 📄 Documentazione
Nel repository è presente l'intera documentazione redatta durante la progettazione e lo sviluppo del progetto. Questa include:

- Analisi dei requisiti
- Diagrammi UML (casi d'uso, diagrammi delle classi, sequenze, ecc.)
- Piano di sviluppo
- Manuale tecnico in formato html
