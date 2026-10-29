# Git-Handout

## 1. Einführung in Git
### 1.1 Was ist Git?
Git ist ein verteiltes Versionsverwaltungssystem, mit dem Änderungen an Dateien und Projekten nachvollzogen werden können. Es ermöglicht mehreren Personen, gleichzeitig an einem Projekt zu arbeiten, ohne dass Änderungen unmittelbar überschrieben werden.

Git speichert unterschiedliche Entwicklungsstände eines Projekts in sogenannten Commits. Dadurch können frühere Versionen wiederhergestellt und Änderungen miteinander verglichen werden.

Jede Person verfügt über eine lokale Kopie des Repositorys. Über Plattformen wie GitHub können die Änderungen mit anderen Teammitgliedern ausgetauscht werden.
### 1.2 Warum sollte Git verwendet werden?
Git bietet verschiedene Vorteile bei der Entwicklung und Verwaltung von Projekten:
- Versionskontrolle: Änderungen werden dokumentiert und frühere Projektstände können wiederhergestellt werden.
- Teamarbeit: Mehrere Personen können parallel an einem Projekt arbeiten und ihre Änderungen zusammenführen.
- Branches: Neue Funktionen oder Änderungen können unabhängig vom Hauptprojekt entwickelt und getestet werden.
- Nachvollziehbarkeit: Jeder Commit dokumentiert einen bestimmten Entwicklungsstand und kann einer Person zugeordnet werden.
- Datensicherheit: Durch die verteilte Speicherung existieren mehrere Kopien der Projektgeschichte.
Git erleichtert somit die Organisation, Zusammenarbeit und Weiterentwicklung von Softwareprojekten.

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