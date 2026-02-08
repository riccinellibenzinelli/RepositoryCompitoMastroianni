# TripSync


# Descrizione del progetto


TripSync è una web app che aiuta gruppi di amici, coppie o colleghi a organizzare viaggi in modo collaborativo.
Ogni utente può proporre mete, votare attività, gestire il budget comune e creare un itinerario condiviso.

Integra Google Maps, Booking e Skyscanner, permettendo di trovare alloggi, voli e percorsi in un solo luogo.

# Monetizzazione

Commissioni sulle prenotazioni

Abbonamento Premium

Sponsorizzazioni

# Problema



Organizzare un viaggio di gruppo spesso è caotico: troppe chat, confusione sul budget, poche decisioni chiare e nessun sistema integrato.
TripSync risolve tutto con uno spazio unico dove pianificare, votare e gestire il viaggio insieme.

# Target



Giovani 18–35 anni

Gruppi di studenti e lavoratori

Agenzie che organizzano viaggi collettivi

# Requisiti Funzionali



Registrazione/Login (email o Google)

Creazione gruppi di viaggio

Proposte e votazioni

Gestione budget e spese

Itinerario giornaliero

Chat interna

Integrazione Google Maps / Booking / Skyscanner

Export PDF o link del viaggio

# Requisiti Non Funzionali



UI semplice e responsive

Sicurezza con JWT

Scalabilità cloud

Caricamento rapido delle mappe

Uptime ≥ 99%

Compatibile con browser e mobile

# Tabella di benchmarking
<img width="918" height="390" alt="image" src="https://github.com/user-attachments/assets/a10a111f-17b6-41fb-be5c-985902769804" />

# Uml Use Case
<img width="1288" height="355" alt="image" src="https://github.com/user-attachments/assets/5be8ad7e-0a75-49be-93ea-899c6d996ef5" />

# timestamp JWT
1758872765

# Elevator pitch
Organizzare un viaggio di gruppo oggi è sorprendentemente complicato.
Ci sono mille chat, decisioni che non arrivano mai, budget poco chiari e persone che restano escluse dalle scelte. Il risultato? Stress, discussioni e viaggi che spesso partono già male.

TripSync nasce per risolvere questo problema.
È una web app che offre a gruppi di amici, coppie o colleghi uno spazio unico dove pianificare il viaggio in modo collaborativo: si propongono mete, si votano attività, si gestisce il budget condiviso e si costruisce un itinerario giornaliero chiaro per tutti.

Grazie all’integrazione con Google Maps, Booking e Skyscanner, TripSync permette di trovare voli, alloggi e percorsi senza uscire dalla piattaforma.
Meno caos, più decisioni, più viaggi fatti davvero.

# Link lovable
https://id-preview--619d2781-a8e8-4001-9775-c819847ffb48.lovable.app/?__lovable_token=eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX2lkIjoiRThCdmdBV3NLWlFvQ3h0SnpUSXU0VTNFM3lGMyIsInByb2plY3RfaWQiOiI2MTlkMjc4MS1hOGU4LTQwMDEtOTc3NS1jODE5ODQ3ZmZiNDgiLCJhY2Nlc3NfdHlwZSI6InByb2plY3QiLCJpc3MiOiJsb3ZhYmxlLWFwaSIsInN1YiI6IjYxOWQyNzgxLWE4ZTgtNDAwMS05Nzc1LWM4MTk4NDdmZmI0OCIsImF1ZCI6WyJsb3ZhYmxlLWFwcCJdLCJleHAiOjE3NzExODU0NzUsIm5iZiI6MTc3MDU4MDY3NSwiaWF0IjoxNzcwNTgwNjc1fQ.j-xAa-IRLpplCwUyOHH1UplzydWq0DuELCSFN3yHFYUKxVV_JRAyWWmLA5eq-flzfBYbpD9YyMeHgKUTZo9UoniCttfnf8waXb4do_bOGV5Dl7mupd4R8egcYEBp9MjZkPD-7olbXYkIlJUDaVw-myzSv2n6ZcSL4xPdya4IuDB3HLhSb8kPRGB21wKdInkV_O-UrnF-38hf4qg0IxIFbJZSQXmu3yqtgvVEfVoexICFTCAC9qhTPIFdkIEV2GqWJS0Jg5jsAwGvm6sL52lZSWuxOyeodblNc-Hc8vV2hc6DRk5T10GWx9N0U8_76Pka4vEXs14dNimiILryhZrDivLPRrhvizjCNLmOzyCwANp_mp5wd_99oisXa0QJnZ5lpLq1SI00-Dglb79GJGzCzba0Il1ZSXA075J01pvwRmrcBYDImAtlXHaTtoVhOXnriaj_FzkOArFqvVvDB4F0PjLjNQ160gXy2n3cNXEDJGYScTuUr0qQTDSesaibRH4JcNKQ7q3xAbnUVvB0bMs8l_6hk4d-2dnhdIAcpE0Lw5uoOPFenHfTnXEQZZTHb-syCO-WJveXDYDJBgPVJpoh4fDfqL-5JTaEferexnaTQKSkYpUcwt9JUedarpBDHrlI_eGz32MfMoku5eXzeRu2zlSPMVdEwizTCI3TH2qQY-4

# WBS 
```mermaid
graph TD
    A["TripSync (MVP - 6 mesi)"] --> B["Project Management & Analisi"]
    A --> C["UX/UI Design"]
    A --> D["Sviluppo Frontend"]
    A --> E["Sviluppo Backend"]
    A --> F["Integrazioni Esterne"]
    A --> G["Testing & QA"]
    A --> H["Deploy & Scalabilità"]
    A --> I["Marketing & Monetizzazione"]

    B --> B1["Raccolta Requisiti"]
    B --> B2["Definizione MVP"]
    B --> B3["WBS & Roadmap"]
    B --> B4["Analisi Rischi"]

    C --> C1["User Flow & Wireframe"]
    C --> C2["Design Responsive"]
    C --> C3["Prototipo Interattivo"]
    C --> C4["User Testing"]

    D --> D1["Auth & Onboarding"]
    D --> D2["Dashboard Gruppi"]
    D --> D3["Votazioni & Proposte"]
    D --> D4["Budget & Spese"]
    D --> D5["Itinerario Giornaliero"]
    D --> D6["Chat Interna"]

    E --> E1["API REST"]
    E --> E2["Gestione Utenti & Gruppi"]
    E --> E3["Votazioni & Consenso"]
    E --> E4["Budget & Transazioni"]
    E --> E5["Itinerari"]
    E --> E6["JWT & Sicurezza"]

    F --> F1["Google Maps"]
    F --> F2["Booking"]
    F --> F3["Skyscanner"]
    F --> F4["Gestione Rate Limit & Cache"]

    G --> G1["Test Funzionali"]
    G --> G2["Test UX"]
    G --> G3["Bug Fixing"]

    H --> H1["Cloud Deploy"]
    H --> H2["Scalabilità & Performance"]
    H --> H3["Monitoring & Uptime"]

    I --> I1["Sistema Abbonamento Premium"]
    I --> I2["Tracking Commissioni"]
    I --> I3["Landing Page"]
    I --> I4["Validazione Business Model"]
```
