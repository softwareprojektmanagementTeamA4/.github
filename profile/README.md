# Projektentwurf "Multiplayer-Car-Racing-Game"

## Einleitung
Das Ziel des Projekts ist die Entwicklung eines Multiplayer-Car-Racing-Games, bei dem mehrere Spieler gleichzeitig Rennen fahren können. Die folgende Ausarbeitung behandelt die Planung und die Organisation dieses Projekts.

## Organisation

1. Teamstruktur
    - Wir organisieren uns in 2er-Teams, um eine effektive Zusammenarbeit sicherzustellen. So wird die Kommunikation untereinander und die Verteilung der Aufgaben vereinfacht.
    - 4 Personen (Zwei 2er-Teams) befassen sich zu Beginn mit der eigentlichen Spielentwicklung: Bjarne Zaremba, Danny Meihöfer / Mattis Wellenbüscher, Marvin Petschulat
    - 2 Personen (Ein 2er-Team) befasst sich mit der Implementierung von Socket.io: David Stevic, Lukas Landmann
    - Verteilung der Rollen:
        - !!TODO!!
2. Kommunikation
    - Wir nutzen Discord für regelmäßige Team-Meetings, sowie Text- und Sprachkommunikation.
    - Wir möchten mindestens einmal in der Woche ein Jour-Fixe etabilieren, bei dem jedes Teammitglied von seinen Erfolgen der letzen Woche, sowie seiner Planung für die kommende Woche berichtet.
    - Für informelle und schnelle Absprachen wird WhatsApp verwendet.
3. Kanban-Board
    - Zur Arbeitsverteilung und Visualisierung verwenden wir ein Kanban-Board, welches mithilfe von "GitHub-Projects" erstellt und verwaltet wird.
    - Das Kanban-Board bekommt folgende Spalten:
        - Backlog: Zu bearbeitenden Aufgaben
        - Sprint-Backlog: Aufgaben, die in einem Sprint bearbeitet werden sollen
        - In Progress: Aufgaben, die gerade in Bearbeitung sind
        - Done for Branch: Aufgaben, die für den jeweiligen Branch abgeschlossen sind, und reviewed werden müssen
        - In Review: Abgeschlossene Aufgaben, die sich im Review befinden
        - Ready for merge: Aufgaben, die erfolgreich gereviewed worden sind und auf den Master-Branch gemerged werden können
4. Anforderungsbeschreibung und Priorisierung
    - Wir nutzen "GitHub-Issues", um Feautures, User-Stories und Tasks zu erstellen und zu verwalten. Dies funktioniert mithilfe von passenden Labels.
    - Die Priorisierung wird in erster Ebene durch "GitHub-Milestones" realisiert. Diese geben vor, welches Feature in welcher Zeit bearbeitet werden soll.
    - Innerhalb der Meilensteine wollen wir die Aufgaben dann noch mithilfe von Labels (high-priority, middle..., low...) priorisieren.
5. Randbedingungen des Projekts
    - Abgabetermin des Projekts: 11. Januar 2024
    - Budget: Kein Budget
    - Rechtliche Anforderungen: Rechtliche Anforderungen wie Datenschutzbestimmungen, Urheberrechte und Lizenzbedingungen werden berücksichtigt.

    
## Projektentwicklung und Zusammenarbeit im Team
1. GitHub Repository
    - Der gesamte Code wird in einem gemeinsamen GitHub-Repository verwaltet, um die Versionskontrolle zu vereinfachen.
    - Jedes 2er-Team bekommt einen eigenen Branch, auf welchem dieses seine Aufgaben bearbeiten kann. Die einzelnen Branches werden dann nach einem Code-Review der anderen Teams auf den Master-Branch gemerged.
    - Beim Push in das Repository wird die Code-Formatierung automatisch nach den Google-Standards überprüft. 
2. Meetings
    - Wir planen 1-2 Meetings pro Woche, um den Fortschritt zu besprechen, sowie Aufgaben zu koordinieren.
    - 1 festgelegtes Meeting (Jour-Fixe) am Montag, um allgemein über anstehende Aufgaben zu sprechen.
    - 1 individuell geplantes Meeting, um Probleme, den Status der Aufgaben und die Erstellung neuer Aufgaben zu besprechen.
3. Code-Kommentierung
    - Die Kommentierung des Codes ist obligatorisch, um die Verständlichkeit und Nachvollziehbarkeit des Codes sicherzustellen.
4. Tagebuchführung
    - Jedes Teammitglied ist verpflichtet, ein Tagebuch zu führen, um die wöchentliche Arbeitszeit zu dokumentieren.
    - Das Tagebuch wird in einer Excel-Tabelle realisiert (Link zur Excel-Tabelle: https://1drv.ms/x/s!Am1gh_2dJu1Z8lBw1poWYBcFyy91?e=vLbRNa)
    - Jedes Teammitglied sollte mindestens 10 Stunden pro Woche für das Projekt aufwenden und dies im Tagebuch festhalten. Dies kann über die Bilanz im Tagebuch verfolgt werden.
5. Entwicklungstools
    - Zur Softwareentwicklung nutzen wir VSCode, sowie andere geeignete IDE's.
    - Außerdem werden Grafik- und Soundentwicklungstools, wie Photoshop und FLStudio verwendet. 

## Technische Aspekte
1. Programmiersprachen und Technologien
    - Wir entwickeln 2 Client-Anwendungen (Einmal in Python und einmal in Java).
    - Server???
    - Zur bidirektionalen Kommunikation verwenden wir Socket.io.
2. GitHub
    - Link zur Organisation: https://github.com/softwareprojektmanagementTeamA4
    - Jedes 2er Team arbeitet auf einem eigenen Branch, von dem aus es selbstständig weitere Branches erstellen und verwalten kann.
    - Das Testen des Codes wird mithilfe von GitHub-Actions realisiert. Jedesmal, wenn auf den Master-Branch gemerged wird, wird ein automatisierter Job ausgeführt, der den Code umfangreich testet.
    - Bei jedem Push wird die Code-Formatierung auf Google-Standards überprüft.
3. Schnittstellen
    - Socket.io
    - GUI
4. Code Reviews/Pull Requests
    - Ein Code-Review wird von mindestens einer Person jedes Teams durchgeführt.
    - Aspekte des Code-Reviews:
        - Kommentare
        - Variablen-, Methoden- und Klassenbezeichnungen
        - Formatierungen
        - Funktionalität des Codes
        - Unklarheiten im Code?
    - Der Master-Branch des Repositorys wird protected, d.h. es kann nur nach erfolgreichem Code-Review auf diesen germerged werden.
  
## Weiteres Vorgehen
- Spielteam:
    1. In Javascript einlesen/einarbeiten			
    2. Im SourceCode einarbeiten
    3. Aufgaben fürs Kanban erstellen			
    4. Bearbeiten der Aufgaben beginnen
- SocketIO-Team:
    1. In die Dokumentation von SocketIO einarbeiten				
    2. Grundlegende Serverarchitektur erstellen				
    3. Sich dem Spielteam anschließen				
				

## Fragen an Prof. Brunsmann
- Wo wird die Anwendung deployed (FH-Server)?
- Browser-Game oder Desktop-Version?
- Programmiersprache Server?
