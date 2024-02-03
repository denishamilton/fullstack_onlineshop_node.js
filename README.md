# Anleitung zur Einrichtung des Projekts
Diese Anleitung führt Sie durch die Schritte zur Einrichtung und Lokalisierung des Projekts auf Ihrem lokalen Rechner.

## 1. Projekt klonen
Klonen Sie das Projekt von GitHub auf Ihren lokalen Rechner:
```bash
git clone <URL_des_Repositories>
```

## 2. Installation der Server-Abhängigkeiten
Navigieren Sie in das Verzeichnis der Serverkomponente des Projekts:

Installieren Sie die erforderlichen Node.js-Abhängigkeiten:
```bash
cd server # navigieren zum Serververzeichnis 
npm install # installieren
```

## 3. Installation der Client-Abhängigkeiten
Navigieren Sie in das Verzeichnis der Clientkomponente des Projekts:

Installieren Sie die erforderlichen Node.js-Abhängigkeiten:
```bash
cd ../client # navigieren zum Clientverzeichnis
npm install # installieren
```

## 4. Erstellung der Datenbank
Erstellen Sie eine Datenbank auf Ihrem lokalen PostgreSQL-Server.

## 5. Konfiguration der Umgebungsvariablen
Bearbeiten Sie die Datei .env im Hauptverzeichnis des Projekts entsprechend Ihren Anforderungen und Ihrer PostgreSQL-Konfiguration.

## Starten des Servers
Öffnen Sie ein Terminal und navigieren Sie zum Serververzeichnis:

Starten Sie den Server mit dem Befehl:
```bash
cd ../server # navigieren zum Serververzeichnis
node index.js # starten des Servers
```

## Starten des Clients
Öffnen Sie ein Terminal und navigieren Sie zum Clientverzeichnis:
```bash
cd ../client # navigieren zum Clientverzeichnis
npm start # starten des Clients
```
Das startet die React.js-Anwendung auf http://localhost:3000 und öffnet automatisch Ihren Standardwebbrowser, um die Benutzeroberfläche anzuzeigen.
Vielen Dank für die Verwendung unseres Projekts!
