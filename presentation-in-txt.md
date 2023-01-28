
## Passwortmanager
Sie bieten einen verschlüsselten Speicher für Kennworte an. Dieser ist im Bestenfall EE2-Verschlüsselt. Somit weiß nur der Besitzer des Passwortmanager was für Daten in ihm abgelegt wurden. Dies erleichtert Anwendern die verwaltung und Absicherung ihrer Konten. Dazu wird innerhalb der Anwendung Neben dem Passwort auch weitere für den Login benötigte Daten, meist Email oder Nutzername, zuzüglich der Webaddresse gespeichert. Für Apps kann anstelle der Webaddresse auch der appname gespeichert werden. Dies ist vorallem für QoL Funktionen wie Autofillin oder Autoregister, welche Registrierung und Anmeldung bei Diensten noch weiter mittels Automatisierung Vereinfachen.

### passwortmanager - (non)cloud
Je nach Anwender und Risikobereitschaft sind unterschiedliche Lösungen zu Präferieren. Vorab, Lokal die Passwörter in einer Datei zu speichern, unverschlüsselt, ist mit abstand die schlechteste idee. 

Zunächst bieten Cloudlösungen wie die von Bitwarden einige Vorteile. Geräte haben immer den neuesten Stand, da diese hiere lokale Datenbank mit dem des Servers Syncronisation. Also Perfekt für jene mit vielen Geräten. Da die Zugrundeliegende Hardware aus dem Hause Microsoft gestellt wird, kann auch mit einer gewissen Sicherheit und erreichbarkeit gerechnent werden. Ebenso ist das Handling sehr einfach, da nur die Clientanwendung installiert und Angemeldet werden muss. Somit ist das hinzufügen von Geräten sehr einfach möglich.

Nachteilig ist die Erreichbarkeit im Internet. Wer dies nicht möchte, kann stattdessen auf Lokale Passwortmanager zurückgreifen. Sie sind meist genauso Kompfortabel in der Nutzung, wenn es jedoch darum geht, auf zwei oder mehreren Geräten den Passwortmanager verfügbar zu halten, kann es recht Aufwendig werden.

Fall einem beide fälle nicht ganz zusagen gibt es noch die möglichkeit im falle von Bitwarden bspw. einfach selbst eine Instanz zu hosten. Dies bringt aber mit ganz eigene Fallstricke mitsich, da nun nicht mehr Microsoft für die Server und Sicherheit zuständig ist, sondern der Nutzer selbst.

### passwortmanager - Bitwarden
Bitwarden ist meine persönliche Wahl wenn es um Passwortmanager geht. Ich Nutze es sowohl in der Cloud für meine Konten, als auch auf meinem Server, um Interne Server und dienste passworttechnisch zu Abzusichern und zu Verwalten. Auch ist die Preisgestalltung mit $10/Jahr sehr fair, da vorallem nur wenige die zusätzlichen Funktionalitäten überhaupt nutzen werden. Einziges Manko, securiy Keys sind nicht im Kostenlosen Modell enthalten.

## Multi faktor authentisierung (MFA)
Mittels MFA wird neben dem Passwort, dem Wissen, bei einem Login auch der Besitz oder Biometrie abgefragt. Dies sorgt für eine Erhöhte Sicherheit, da nun nicht mehr die Accountsicherheit im Wissen liegt. Dies Reduziert die effektivität von Phishing massiv. Laut eigenen angaben konnte Google, durch das Erzwingen von mindestens einem Zweiten Faktor, die Übernahme von Konten um 50% Reduzieren. Nur gibt es immer noch viele Dienste, Spotifiy, Netflix, die nicht auf MFA setzen.

### MFA - Fallstricke


### Wall of shame

### MFA - Email?
Mittels Email einen Zweiten Faktor bereitzustellen ist sowohl einfach, als auch unkompliziert. Dies bringt jedoch einige Probleme mitsich. Zum einen ist der Überwiegende teil des Emailverkehrs unverschlüsselt. Für den Austausch von Anmeldeinformation ist dies generell Problematisch. Außerdem muss davon ausgegangen werden, dass auch ein Email Konto gehackt werden kann. Somit ist dieser zusätzliche Faktor nichtig, sobald der Emailaccount gehackt wurde. Im schlimmsten Fall ist der komplette Account verloren, wenn sich mit dem selben Email Konto registriert wurde.