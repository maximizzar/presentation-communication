---
marp: true
theme: uncover
class: invert

paginate: true
_paginate: false

--- 

# IT Sicherheit für Benutzer

Maximilian Krönung

---

## Passwortmanager

![bg right:20% h:160](res/bitwarden-icon.svg)

- Verschlüsselter Speicher für Kennworte
- Sollte Plattformübergreifend sein
- Mehr Sicherheit -> nur ein pw merken
- QoL
    + Autofillin
    + Autoregister
- Kleiner Nachteil: masterpw

---

### Passwortmanager - (non)cloud

![bg right:20% h:160](res/microsoft_azure-icon.svg)

- Vorteile

    + Syncronisation
    + "Überall" erreichbar
    + Einfacher zu handeln

- Nachteile

    + Manuelle Syncronisation
    + Nur lokal
    + Komplizierter ab 2 Geräten

- Mittelweg: Selfhost

---

### Passwortmanager - Bitwarden

![bg right:20% h:160](res/bitwarden-icon.svg)

- Open source

    + Selfhost möglich
    + ebenfalls Zero Knowledge E2E-Verschlüsselung

- Auch ohne Abo sehr umfangreich
- Auch offline Nutzbar (Sync nicht möglich) 

---

## Multi faktor authentisierung (MFA)

- Fragt besitz und biometrie ab
- Phishing wird schwerer

    + -50% Google-Account übernahmen

- Pw verlust verkraftbar

---
### MFA - Fallstricke

- Schützt nur bei Anmeldung
- Dauerhafter Zugriffsverlust möglich

    + Wichtig! -> Backupcodes sichern

---

### MFA - Email

![bg right:20% h:160](res/gmail-icon.svg)

- Übertragung im Klartext -> schlecht
- Zentrierung des Risikos

    + Worstcase: Konto-email = 2FA-email

---

### MFA - SMS

![bg right:20% h:160](res/sms-chat-bubble.svg)

- Verbeitet da es einfach ist
- Übertragung im Klartext -> schlecht

---

### MFA - apps