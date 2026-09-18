# ToDo-Applikation

## Projektbeschreibung

Diese Anwendung ist eine ToDo-Applikation auf Basis von **Node.js**.

Das Projekt wird mit **Git und GitHub** verwaltet und mit **Docker** containerisiert.

## Voraussetzungen

Für die Einrichtung des Projekts werden folgende Programme benötigt:

* **Node.js**
* **Git**
* **Docker**
* **Docker Compose**

## Repository klonen

Das Repository kann mit folgendem Befehl geklont werden:

```bash
git clone DEINE-REPOSITORY-URL
```

Anschließend in das Projektverzeichnis wechseln:

```bash
cd docker-nodejs-sample
```

## Pakete installieren

Die benötigten Node.js-Pakete werden mit folgendem Befehl installiert:

```bash
npm install
```

## Anwendung lokal starten

Die Anwendung kann lokal mit folgendem Befehl gestartet werden:

```bash
npm run dev
```

Die Anwendung ist anschließend unter folgendem Link erreichbar:

http://localhost:3000

## Docker-Image erstellen

Das Docker-Image wird mit folgendem Befehl erstellt:

```bash
docker build -t todo-app .
```

## Anwendung mit Docker starten

Die Anwendung kann mit folgendem Befehl in einem Docker-Container gestartet werden:

```bash
docker run --name todo-container -p 3000:3000 todo-app
```

Anschließend ist die Anwendung unter folgendem Link erreichbar:

http://localhost:3000

## Anwendung mit Docker Compose starten

Die Anwendung kann mit Docker Compose gestartet werden:

```bash
docker compose up -d
```

Anschließend ist die Anwendung unter folgendem Link erreichbar:

http://localhost:3000

## Anwendung stoppen

Die Anwendung kann mit Docker Compose gestoppt werden:

```bash
docker compose down
```
