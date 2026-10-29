# Git-Handout

## 1. Einführung in Git
### 1.1 Was ist Git?
### 1.2 Warum sollte Git verwendet werden?

## 2. Grundlegende Git-Befehle
Git wird über Befehle im Terminal gesteuert. Die folgenden Befehle gehören zu den wichtigsten Funktionen der Versionsverwaltung.
### 2.1 Repository erstellen
- git init: Erstellt ein neues lokales Git-Repository.
- git clone <URL>: Erstellt eine lokale Kopie eines bestehenden Remote-Repositorys.
### 2.2 Änderungen speichern
- git status: Zeigt den aktuellen Zustand des Repositorys an.
- git add <Dateiname>: Fügt eine Datei zur Staging Area hinzu.
- git add .: Fügt neue und geänderte Dateien im aktuellen Verzeichnis und seinen Unterverzeichnissen zur Staging Area hinzu.
- git commit -m "Nachricht": Speichert vorgemerkte Änderungen als Commit.
- git log: Zeigt die Commit-Historie.
### 2.3 Änderungen hochladen und herunterladen
- git remote -v: Zeigt die konfigurierten Remote-Repositories.
- git push: Überträgt lokale Commits zum Remote-Branch.
- git pull: Lädt Änderungen herunter und integriert sie.
- git fetch: Lädt Änderungen herunter, ohne sie direkt zu integrieren.
### 2.4 Beispiel: Typischer Git-Arbeitsablauf
git status
git add Git-Handout.md
git commit -m "Handout aktualisiert"
git push

## 3. Branches und Merge-Konflikte
### 3.1 Was sind Branches?
### 3.2 Branches erstellen und zusammenführen
### 3.3 Merge-Konflikte erkennen und lösen

## 4. Git mit IntelliJ und PyCharm
### 4.1 Local Repository
### 4.2 Remote Repository
### 4.3 Git-Funktionen in der IDE

## 5. Git-Tools und Plattformen
### 5.1 GitHub
### 5.2 GitLab
### 5.3 Weitere nützliche Werkzeuge