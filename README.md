# Anleitung zur Einrichtung des Projekts

Diese Anleitung führt Sie durch die Schritte zur Einrichtung und Lokalisierung des Projekts auf Ihrem lokalen Rechner.

## 1. Projekt klonen

Klonen Sie das Projekt von GitHub auf Ihren lokalen Rechner:

```bash

git clone <URL_des_Repositories>

```
## 2. Installation der Server-Abhängigkeiten
Navigieren Sie in das Verzeichnis der Serverkomponente des Projekts:

```bash

cd server

```

Installieren Sie die erforderlichen Node.js-Abhängigkeiten:

```bash

npm install

```

## 3. Installation der Client-Abhängigkeiten
Navigieren Sie in das Verzeichnis der Clientkomponente des Projekts:

```bash

cd ../client

```

Installieren Sie die erforderlichen Node.js-Abhängigkeiten:

```bash

npm install

```

## 4. Erstellung der Datenbank
Erstellen Sie eine Datenbank auf Ihrem lokalen PostgreSQL-Server.

## 5. Konfiguration der Umgebungsvariablen
Bearbeiten Sie die Datei .env im Hauptverzeichnis des Projekts entsprechend Ihren Anforderungen und Ihrer PostgreSQL-Konfiguration.

## Starten des Servers
Öffnen Sie ein Terminal und navigieren Sie zum Serververzeichnis:

```bash

cd ../server

```

Starten Sie den Server mit dem Befehl:

```bash

node index.js

```

Starten des Clients
Öffnen Sie ein Terminal und navigieren Sie zum Clientverzeichnis:

```bash

cd ../client

```

Starten Sie den Client mit dem Befehl:

```bash

npm start

```

Das startet die React.js-Anwendung auf http://localhost:3000 und öffnet automatisch Ihren Standardwebbrowser, um die Benutzeroberfläche anzuzeigen.
Vielen Dank für die Verwendung unseres Projekts!
