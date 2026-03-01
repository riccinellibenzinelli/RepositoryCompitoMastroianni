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
<img width="918" height="332" alt="image" src="https://github.com/user-attachments/assets/d6068f2b-da95-488e-a6b2-6c8b6e0246d1" />


# Uml Use Case
<img width="809" height="666" alt="image" src="https://github.com/user-attachments/assets/9e5d73e3-5f06-41ec-8df0-2c06fbb134f8" />

# timestamp JWT
1758872765

# Elevator pitch
Ciao, sono Riccardo e vi presento TripSync, una web app pensata per rivoluzionare il modo in cui i gruppi di persone organizzano i loro viaggi insieme. Oggi pianificare un viaggio di gruppo è spesso un caos: troppe chat, decisioni che si perdono, budget poco chiari e responsabilità confuse. TripSync risolve tutto questo mettendo a disposizione un’unica piattaforma dove amici, coppie o colleghi possono proporre mete, votare attività, gestire il budget comune e creare itinerari condivisi in modo semplice ed efficace.

La nostra soluzione si integra con Google Maps, Booking e Skyscanner per trovare voli, alloggi e percorsi senza dover saltare tra siti diversi, eliminando frustrazione e dispersione di tempo. Il target principale sono i giovani tra i 18 e i 35 anni, gruppi di studenti e lavoratori, e anche agenzie che organizzano viaggi collettivi.

TripSync si finanzia tramite commissioni sulle prenotazioni, abbonamenti premium e sponsorizzazioni; per il team, tecnologie web moderne e design responsivo assicurano un’esperienza fluida e scalabile.
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
