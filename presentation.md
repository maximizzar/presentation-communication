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

- Verschlüsselter Speicher für Kennworte
- Sollte Plattformübergreifend sein
- Mehr Sicherheit -> nur ein pw merken
- QoL
    - Autofillin
    - Autoregister
- Kleiner Nachteil: masterpw

---

### Passwortmanager - cloud

![bg right:20% h:160](res/microsoft_azure-icon.svg)

- Syncronisation
- "Überall" erreichbar
- Einfacher zu handeln

---

#### Passwortmanager non-cloud

![bg right:20% h:160](res/nix.png)

- Manuelle Syncronisation
- Nur lokal
- Komplizierter ab 2 Geräten

---

### Passwortmanager - Bitwarden

![bg right:20% h:160](res/bitwarden-icon.svg)

- Open source
    - Selfhost möglich
    - ebenfalls Zero Knowledge E2E-Verschlüsselung
- Auch ohne Abo sehr umfangreich
- Auch offline Nutzbar (Sync nicht möglich) 

---

## Mehr Faktor Authentisierung (MFA)



- Fragt Besitz und Biometrie ab
- Phishing wird schwerer
    - -50% Google-Account übernahmen
- Pw Verlust verkraftbar

---

### MFA - Fallstricke

![bg right:20% h:160](res/nix.png)

- Schützt nur bei Anmeldung
- Dauerhafter Zugriffsverlust möglich
    - Wichtig! -> Backupcodes sichern

---

### MFA - Email

![bg right:20% h:160](res/gmail-icon.svg)

- Übertragung im Klartext -> schlecht
- Zentrierung des Risikos
    - Worstcase: Konto-email = 2FA-email

---

### MFA - SMS

![bg right:20% h:160](res/sms-chat-bubble.svg)

- Verbeitet da es einfach ist
- Übertragung im Klartext -> schlecht

---

### MFA - apps

![bg right:20% h:160](res/web-app-developing.svg)

- Keine Dritten Involviert
    - Email Provider
    - SMS Dienstleister
- Schlüssel (QR-Code) verschlüsselt
- Funktion: 
    - Schlüssel + Zeit = Code
    - srv-Code = clnt-Code -> ok

---

# Quellen

[Ein Vergleich von PASSWORTMANAGERN](https://www.youtube.com/watch?v=YwbE2iLmAT0)
[Vergleich: NICHT ALLE Zwei-Faktor-Methoden sind sicher!](https://www.youtube.com/watch?v=EY9hiHD9XKU)

---

# Bild Quellen

[bitwarden-icon.svg](https://www.vectorlogo.zone/logos/bitwarden/index.html)
[gmail-icon.svg](https://www.vectorlogo.zone/logos/gmail/index.html)
[microsoft_azure-icon.svg](https://www.vectorlogo.zone/logos/microsoft_azure/index.html)
[sms-chat-bubble.svg](https://freesvg.org/1531719185)
[web-app-developing.svg](https://freesvg.org/web-app-developing)

---

# Extras
Präsentation in Markdown mittels Marpit

[Markdown Presentation Ecosystem](https://marp.app/)
[Never use PowerPoint again](https://www.youtube.com/watch?v=EzQ-p41wNEE#)