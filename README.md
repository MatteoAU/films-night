 # 🎬 Films Night

  Un'applicazione web per organizzare serate film con gli amici. Crea un gruppo, aggiungi film e lascia che la ruota
  della fortuna scelga cosa guardare!

  ## 🌐 Prova l'app

  **[films-night.vercel.app](https://films-night.vercel.app)**

  ---

  ##  Come funziona

  1. **Registrati** e crea un account
  2. **Crea un gruppo** con i tuoi amici (ogni gruppo ha un codice e una password)
  3. **Aggiungi film** alla lista - cerca per titolo e vengono caricati automaticamente poster, anno, regista, ecc.
  4. **Gira la ruota** per scegliere il film della serata
  5. I film non scelti vanno in "Prossimamente" e possono essere riproposti

  ---

  ## 🏗️ Architettura

  | Componente | Tecnologia | Hosting |
  |------------|------------|---------|
  | **Frontend** | React + Vite | Vercel |
  | **Backend** | FastAPI (Python) | Render |
  | **Database** | PostgreSQL | Supabase |
  | **Real-time** | WebSocket | - |

  ### Stack Frontend
  - React 18 con Context API per lo state management
  - React Router per la navigazione
  - Axios per le chiamate API
  - Framer Motion per le animazioni (ruota della fortuna)

  ### Stack Backend
  - FastAPI con autenticazione JWT
  - SQLAlchemy ORM
  - WebSocket per aggiornamenti in tempo reale
  - Bcrypt per l'hashing delle password

  ---

  ## ✨ Funzionalità

  - **Gruppi privati** - Ogni gruppo ha codice univoco e password
  - **Ricerca film** - Integrazione con database film (poster, cast, rating)
  - **Ruota della fortuna** - Selezione casuale animata
  - **Film nascosti** - Nascondi temporaneamente un film dalla ruota
  - **Aggiornamenti real-time** - Tutti i membri vedono i cambiamenti istantaneamente
  - **Storico film visti** - Tieni traccia di cosa avete guardato

  ---

  ## 👤 Autore

  Sviluppato da MatteoAU

  ---
