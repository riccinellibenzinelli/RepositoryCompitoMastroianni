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
Ciao, sono Riccardo e vi presento TripSync, una piattaforma SaaS pensata per semplificare l’organizzazione dei viaggi di gruppo.

Quando più persone devono organizzare un viaggio, tutto diventa complicato: chat infinite, decisioni confuse, difficoltà nel gestire il budget e nessuno che ha una visione completa del piano finale.

TripSync risolve questa situazione offrendo un’unica piattaforma online dove i membri del gruppo possono proporre destinazioni, votare attività, organizzare l’itinerario e gestire le spese condivise in modo chiaro e strutturato.

Il nostro modello di business è Software as a Service: gli utenti pagano un abbonamento per accedere al servizio. Offriamo una versione base e una versione avanzata con funzionalità extra, pensata per gruppi organizzati, community e agenzie che gestiscono viaggi collettivi.

In questo modo generiamo ricavi ricorrenti e costruiamo una piattaforma scalabile nel settore travel.

TripSync trasforma il caos organizzativo in un processo semplice, collaborativo e digitale.”
# Link lovable
https://travel-hive-co.lovable.app

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
