# Software Entwicklung

# Index
1. [Software Engineering](#software-engineering)
    - [Software Entwicklungsprobleme](#software-entwicklungsprobleme)
    - [Vorgehensmodelle](#vorgehensmodelle)
    - [Modelle und Modellierung](#modelle-und-modellierung)
    - [UML](#uml)
2. [Anforderungsanalyse](#chapter-2---anforderungsanalyse)
    - [Usability](#usability)
    - [User-Centered Design (UCD)](#user-centered-design-ucd)
    - [UCD Prozess: User & Domain Research](#ucd-prozess-user--domain-research)
    - [UCD Prozess: Anforderungsanalyse](#ucd-prozess-anforderungsanalyse)
    - [UCD Anforderungsanalyse: Artefakte](#ucd-anforderungsanalyse-artefakte)
    - [UCD Prozess: Design & Prototype](#ucd-prozess-design--prototype)
    - [UCD Prozess: Evaluate](#ucd-prozess-evaluate)
3. [Anforderungsanalyse 2](#chapter-3---anofrderungsanalyse-2)
    - [Anwendungsfälle (Use Cases)](#anwendungsfälle-use-cases)
    - [Akteur](#akteur)
    - [3 Arten von Use Cases](#3-arten-von-use-cases)
    - [Fully-Dressed Use Case](#fully-dressed-use-case)
    - [Systemsequenzdiagramm (SSD)](#systemsequenzdiagramm-ssd)




## Chapter 1 - Software Engineering / Was ist Software Engineering (Basics)

**Software Engineering ist:**
- Software Engineering beschäftigt sich mit der Herstellung von Software, der Organisation und Modellierung der zugehörigen Datenstrukturen.
- Zielorientierte Verwendung von Prinzipien, Methoden und Werkzeugen für die professionelle Softwareentwicklung.
- Erstellung durch Projektplans.

**Agile Softwareentwicklung:**
- Basieren auf empirischen Prozessen. Setzen auf kontinuierliche Beobachtung und Anpassung. Heisst am Anfang nur Grobplanung, dann wird der Prozess gesteuert und überwacht.
- Agile Softwareentwicklung ist eine Sammlung von Prinzipien und Praktiken, um den Prozess der Softwareentwicklung zu verbessern.

Bei agiler Softwareentwicklung wird die planung am Anfang durchgeführt, der Prozess gesteuert und überwacht.

Ist geeignet für gut planbare Problemstellungen.

## Software Engineering
*   **Kerndisziplinen:** Anforderungsanalyse, Architektur, Implementierung, Test, Verteilung, Einführung, Wartung
*   **Unterstützungsdisziplinen:** Projektmanagement, Konfigurationsmanagement, Qualitätsmanagement, Risikomanagement
*   **Softwareentwicklungsprozess:** Umfasst den gesamten Produktlebenszyklus
*   **Strukturierte Entwicklung:** Früherkennung von Fehlern, Minimierung von Risiken

## Software-Entwicklungsprobleme
*   **Drei Dimensionen:** Anforderungen, Technologie, Skills/Erfahrung

## Vorgehensmodelle
*   Code and Fix
*   Wasserfallmodell
*   **Iterative und inkrementelle Modelle**
*   **Verbreitete Modelle:** Hermes, RUP, Scrum

## Modelle und Modellierung
*   Modell ist ein Abbild eines Gebildes
*   **Modellierung ist Fundament des Software Engineerings**
*   **Artefakte sind Modelle**
*   **Zweck von Modellen:** Verstehen, Kommunizieren, Gestalten, Spezifikation, Experimente, Hypothesen
*   **Umfang der Modellierung:** Hängt von der Problemstellung ab (Hundehütte vs. Wolkenkratzer)

## UML

![alt text](/images/umloverview.png)

Man kann 80% der Probleme mit 20% der UML lösen.

*   **Diagramme:** Statische und dynamische Aspekte
*   **Anwendung:**
    *   **UML as a Sketch:** Informelle Diagramme
    *   **UML as a Blueprint:** Detaillierte Diagramme
    *   **UML as a Programming Language:** Ausführbare Spezifikation

## Wrap-up
*   Solide Analyse- und Entwurfskompetenzen sind notwendig
*   Gängige Prozesse verwenden iterativ-inkrementelles Vorgehensmodell
*   Modelle dienen der Kommunikation und Abstimmung

## Chapter 2 - Anforderungsanalyse

## Usability
*   **Definition (DIN ISO 9241):** Die **Effektivität**, **Effizienz** und **Zufriedenheit**, mit der die adressierten Benutzer ihre Ziele in ihren spezifischen Kontexten erreichen.
*   **Wichtige Aspekte:**
    *   Benutzer
    *   Ziele/Aufgaben des Benutzers
    *   Kontext des Benutzers
    *   Softwaresystem (inkl. UI)



## Usability-Anforderungen (DIN EN ISO 9241-110)
*   **7 wichtige Anforderungsbereiche:**
    *   **Aufgabenangemessenheit**: Minimale Anzahl Schritte für eine Aufgabe, nur Informationen, die für die Aufgabe relevant sind, minimale Anzahl Benutzereingaben (jede Eingabe nur 1 Mal, Standardwerte, Liste vordefinierter Werte, Eingaben vorschlagen)
    Beispiel: Raumreservation : Anzeigen was falsch ist nachdem absenden oder anzeigen, welche Felder noch ausgefüllt werden müssen.
    *   **Lernförderlichkeit**: System sollte Benutzer Infos über unterliegende Konzepte anbieten: Mentales Modell anzugleicehn, nur auf verlangen des Users, user sollte einfach wichtige Tasks ohne Vorwissen erledigen können. Bsp: Tooltips, Hilfsystem, Tutorials.
    *   **Individualisierbarkeit**: System sollte anpassbar sein, z.b erfahrene Benutzer mit Tastenkürzel, Sprache, Kultur, Benutzer mit Einschränkung.
    *   **Erwartungskonformität**: Bezüglich: Design, Interaktion, Struktur, Komplextiät, Funktionalität.
    Konsistenz: Terminologie, Verhalten, Informationsdarstellung.
    *   **Selbstbeschreibungsfähigkeit**: Benutzer ausreichend informiert: Wo ist er?, Was er tun soll/kann?, Was mach das System.
    Labels, Fehlermeldungen. -> Begriffe des Benutzers verwenden.
    *   **Steuerbarkeit**
    *   **Fehlertoleranz**: Benutzerfehler möglichst vermeiden, klar kommunizieren (welcher input erwartet wird, welche funktionen aktiv sind), Benutzereingaben überprüfen, nicht unbedingt beim tippen, Benutzer helfen fehler erkennen und korrigieren, einfache korrektur, kein datenverlust.

## User-Centered Design (UCD)
*   Berücksichtigt die **Bedürfnisse**, **Wünsche** und **Einschränkungen** der Benutzer in jeder Phase des Designprozesses.
*   **UCD Prozess:**
    *   **Plan UCD Process**
    *   **User & Domain Research**
    *   **Requirements Analysis**
    *   **Design & Prototype**
    *   **Evaluate**

![alt text](/images/ucdprocess.png)

### UCD Prozess: User & Domain Research
*   **Ziele bezüglich User:**
    *   Wer sind die Benutzer?
    *   Was ist ihre Arbeit, ihre Aufgaben, Ziele?
    *   Wie sieht ihre Arbeitsumgebung aus?
    *   Was brauchen sie, um ihre Ziele zu erreichen?
    *   Welche Sprache sprechen sie?
    *   Welche Normen sind wichtig für sie?
    *   Pain Points in ihrer Arbeit
*   **Ziele bezüglich Domäne:**
    *   Business der Firma verstehen
    *   Domäne verstehen (Sprache, Konzepte, Prozesse)
*   **Methoden:**
    *   Contextual Inquiry, Interviews, Beobachtung, Fokusgruppen, Umfragen, Nutzungsauswertung, Desktop Research

### UCD Prozess: User & Domain Research - Artefakte
*   **Personas:** Fiktive Person, die eine Benutzergruppe repräsentiert. Wichtig, um Designentscheidungen zu treffen.
![alt text](/images/persona.png)
---
**2 Arten von Szenarien sind wichtig**
*   **Usage-Szenarien:** Beschreiben die aktuelle Situation, wie ein Benutzer das Produkt verwendet. Zeigt allfällige Probleme auf.
*   **Kontextszenarien:** Beschreiben die zukünftige, gewünschte Situation aus Benutzersicht. Wird vor allem in der Anforderungsanalyse verwendet.

Wichtige Punkte beim Kontextszenario:
- Informelle Sprache
- Interaktion des Benutzers mit dem zukünftigen System (High-Level also nicht zu detailliert, Optimistisch, Aus Sicht einer User-Persona)
- Format gleich wie Usage-Szenario
- Beschreibt Zukunft
---
*  **Mentales Modell**
*   **Domänenmodell**
*   **Stakeholder Map:** Zeigt die wichtigsten Stakeholder im Umfeld der Problemdomäne
*   **Service Blueprint / Geschäftsprozessmodell**

### UCD Prozess: Anforderungsanalyse
*   **Ziel:** Ableiten von Benutzeranforderungen an das zu entwickelnde System
    *  Funktionale Abläufe, Interaktionen: **Kontextszenarien, Storyboards, UI-Skizzen, Use Cases**
    * Konzepte, Beziehungen, Quantitäten: **Domänenmodell**
    *  Weitere funktionale/nicht-funktionale Anforderungen, Randbedingungen: **FURPS-Modell**

### UCD Anforderungsanalyse: Artefakte
*   **Kontextszenario:** Beschreibt die zukünftige, gewünschte Situation aus Benutzersicht
*   **Storyboard:** Visualisiert ein Kontextszenario als Comic
*   **UI-Skizzen**: (Hand-) Skizzen der wichtigsten Screens
*   **Wireframes:** UI-Prototypen (Low-Fidelity, High-Fidelity), die das Interaktionskonzept demonstrieren

### UCD Prozess: Design & Prototype
*   Entwicklung des **Interaktionskonzepts**
*   Umsetzung des Konzepts mit **Interaktionsprototypen**

### UCD Prozess: Evaluate
*   Test des Interaktionskonzepts mit Benutzern und Fachexperten

## Chapter 3 - Anofrderungsanalyse 2

### Anwendungsfälle (Use Cases)

Textuelle Beschreibungen einer konkreten Interaktion eines bestimmten Bnuezers mit dem zukünftigen System.
- Aus Sicht des Akteurs
- Enthalten implizite und explizite Anforderungen
- Beschreiben das Ziel des Benutzers
- Beschreiben den Kontext

**Use Cases zentrale Rolle in SWE.**

- Funktionale Anforderungen werden in Use Cases spezifiziert.
- Wichtiger Teil der Projektplanung, Projekt wird entlang der Use Cases strukturiert.
- UC-Realisierung bestimmt die Lösungsarchitektur.
- UCs werden für funktionale Systemtests verwendet.
- Ucs bilden die Basis für Benuzterdokumentation.

---

#### Akteur

- **Akteur:**: Externe Person in einer bestimmten Rolle, die mit dem zu entwickelnden System im Laufe eines Use Cases interagiert.
Externe System, Organisationen, Maschinen können auch Akteure sein.
==Auch die Zeit kann ein Akteur sein== (bei zeitabhängigen Systemen)

Es gibt 3 Arten von Akteuren

| Akteur | Beschreibung |
| ----------- | ----------- |
| Primärakteur | - Initiiert einen Anwendungsfall, um sein Ziel zu erreichen.<br> - Erhält den Hauptnutzen des Anwendungsfalls <br> - Bsp. Kasse: Kassierer |
| Unterstützender Akteur | - Hilft dem SuD bei der Bearbeitung eines Use-Case <br> - Beispiel Kasse: Externer Dienstleister wie Zahlungsdienst für Kreditkarten |
| Offstage-Akteur | - Weitere Stakeholder, die nicht direkt mit dem System interagieren <br> - Beispiel Kasse: Steuerbehörde |

---

#### 3 Arten von Use Cases

1. **Kurz (Brief Use Case)**:
    - Titel + 1 Absatz
    - Beschreibt Standartablauf (keine Varianten, Problemfälle)
2. **Informell (Casual Use Case)**:
    - Titel + informelle Beschreibung in ein bis mehreren Absätzen
    - Beschreibt Standartablauf und wichtige Varianten
3. **Vollstädnig (Fully Dressed Use Case)**:
    - Titel + alle Schritte und Varianten werden im Detail beschrieben
    - Enthalten weitere Informationen zu Vorbedingungen, Erfolgsvarianten etc.

#### Umfang eines guten Use Case (Was gehört rein?)

- Muss einen konkreten Nutzen für den Akteur haben
- Eine Handlung, die eine Person, an einem Ort und zu einer Zeit ausführt.
- Sollte mehr als eine einzelne Aktion beschreiben.

**Titel**
- Aktiv formulieren:
    - Verb + evtl. Objekt voranstellen
    (z.B. Kasse eröffnen)
- Sollte Ziel des Akteurs beschreiben

Tests:
- **Boss-Test:** Würde der Boss des Projekts diesen Use Case als wichtig erachten?
- **Elementary Business Process (EBP):** Eine Aufgabe, die von einem Akteur ausgeführt wird, um ein Geschäftsziel zu erreichen.
- **Size-Test:** Mehr als eine einzelne Aktion?, Fully Dressed meist mehrere Seiten lang.
### Beispiel Use Case
![alt text](/images/usecasebeispiel.png)

#### Zusätzliche Beziehungen im UC-Diagramm:

Zusätzliche Beziehungen im UC-Diagramm:
Werden mit `<<include>>` gekennzeichnet.
Beispiel das Use-Case "Handle Cash Payment" und "Handle Twint Payment" sind enthalten im Use Case "Process Sale".
==Sind aber keine eigenständigen Use Cases== daher auch keine Verbindung zum Akteur.

![alt text](/images/usecaseincludesextends.png)

`<<extends>>`:
- Eigenstädniges Use-Case, der eine Erweiterung eines anderen Use-Case darstellt.
- Ursprünglicher Use-Case wird nicht beeinflusst, wenn das erweiternde Use-Case nicht ausgeführt wird.

- Akteur Generalisierung: Ein Akteur kann ein spezialisierter Akteur sein. Mit "ist-ein"-Beziehung. Akteure zusammenfassen, die ähnliche Use Cases ausführen.

### Fully-Dressed Use Case

Wird meistens die wichtigsten Use Cases in Fully-Dressed Use Cases umgewandelt.

Inhalt:
- UC-Name
- Umfang
- Ebene
- Primärakteur
- Stakeholders und Interessen
- Vorbedingungen
- Erfolgsgarantie / Nachbedingungen
- Standardablauf
- Erweiterungen
- Spezielle Anforderungen
- Liste der Techniken und Datavariationen
- Häufigkeit des Auftretens
- Verschiedenes.

#### Fully-Dressed Use Case Beispiel

| **Scope**               | StudyFlow                                                                                  |
|-------------------------|-------------------------------------------------------------------------------------------|
| **Level**               | User-goal Level Use Case                                                                  |
| **Primary Actor**       | Student                                                                                   |
| **Description**         | This use case describes the “Create Study Plan” functionality within the StudyFlow application. It aims to help students organize their study schedules by giving them an option to generate a study plan for them. It takes in factors like self-assessment values for each module and generates a study plan inside a predefined date range. |
| **Stakeholders and Interests** | - **Educational Institutions or Teachers:** Use of the study plan tool in an academic context. <br> **Interest:** They want to ensure that study plans align with curricula and are pedagogically sound. They may also be interested in monitoring and assessing student progress. |
| **Preconditions**       | - The student has created a profile, including at least one degree, with an active degree and semester selected. <br> - The active semester includes at least one module with details entered. <br> - The student has entered appointments in their calendar. |
| **Success Guarantee / Postconditions** | - A personalized study plan is generated based on the student’s self-assessment for each module. <br> - The study plan fits within the specified available time. <br> - Self-assessment values are locked and cannot be changed unless the student resets the entire plan. |
| **Main Success Scenario (Basic Flow)** | 1. The student opens the “Create Study Plan” window. <br> 2. The system retrieves self-assessment values for each module in the active semester. <br> 3. The student enters exam dates for each module. <br> 4. The student specifies available study hours per day. <br> 5. If appointments are missing, the student adds them to the calendar. <br> 6. The system generates and displays a study plan with export options (.ics file). <br> 7. The student reviews and finalizes or resets the plan. <br> 8. The finalized plan is displayed on the dashboard and schedule tab. |
| **Extensions (Alternative Flows)** | - **2a:** Adjusting Self-Assessment Values <br> &emsp; - The student can modify self-assessment values, which the system saves for plan generation. <br> - **4a:** Invalid Study Hours Entry <br> &emsp; - If an invalid value is entered, the system alerts the student to correct it. <br> - **7a:** Reviewing and Adjusting <br> &emsp; - After review, the student can reset and modify self-assessment values, exam dates, or study hours before generating a new plan. |
| **Special Requirements** | - The study plan must be clearly displayed on the dashboard, logically structured, and aligned with the active degree and semester. <br> - The system should support exporting the study plan in .ics format for compatibility. |
| **Technology and Data Variations** | - **8a:** The study plan can be viewed in the app or exported as a .ics file. <br> - **4a:** Study hours can be entered via a slider or numeric input. <br> - **5a:** Appointments can be entered manually or via a date picker. |
| **Frequency of Use**    | Typically, once per semester or exam period.                                              |
| **Miscellaneous**       | A "Reset Plan" feature allows adjustments before finalizing.                               |


### Systemsequenzdiagramm (SSD)

- Ist formal ein UML Sequenzdiagramm
- Zeigt Interaktionen der Akteure mit dem System.
    - Welche Input-Events auf das System einwirken
    - Welche Output-Events das System generiert

**Ziel:**: Wichtigste Systemoperationen identifizieren, die das System zur Verfügung stellen muss.

![alt text](/images/ssd1.png)
