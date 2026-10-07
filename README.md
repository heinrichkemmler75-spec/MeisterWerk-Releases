# MeisterWerk

**Kampagnenverwaltung für Pen-&-Paper-Rollenspiele**  
**Linux · Windows · Android**

**MeisterWerk** ist ein systemunabhängiges Werkzeug zur Organisation und Unterstützung von Pen-&-Paper-Rollenspielkampagnen.

Es richtet sich vor allem an Spielleiterinnen und Spielleiter, die ihre Kampagnen nicht nur in einzelnen Notizen verwalten möchten, sondern **NSC, Orte, Karten, Handouts, Plots, Sitzungen, Fraktionen und Ereignisse miteinander verknüpfen** wollen.

MeisterWerk arbeitet lokal. Für die eigentliche Kampagnenverwaltung sind weder ein Cloud-Dienst noch eine KI erforderlich.

---

## Download

Dieses Repository enthält die **offiziellen stabilen Veröffentlichungen von MeisterWerk**.

Die jeweils aktuelle Version findest du hier:

**[→ MeisterWerk herunterladen](https://github.com/heinrichkemmler75-spec/MeisterWerk-Releases/releases/latest)**

MeisterWerk wird für folgende Plattformen bereitgestellt:

| Plattform | Bereitstellung |
|---|---|
| **Linux x86-64** | portable Anwendung |
| **Windows x86-64** | portable Anwendung |
| **Android** | signierte APK |

Die Android-Version wird mit einer gleichbleibenden Signatur veröffentlicht, sodass neuere Versionen als Update derselben Anwendung installiert werden können.

---

# Was kann MeisterWerk?

MeisterWerk besteht aus mehreren miteinander verbundenen **Werken**. Jedes Werk kümmert sich um einen bestimmten Teil der Kampagne.

## KampagnenWerk

Das KampagnenWerk ist die Zentrale einer Kampagne.

Hier werden unter anderem verwaltet:

- Kampagnenname und Spielsystem
- Kampagnenbeschreibung
- Spieler und Spielercharaktere
- Meilensteine und Kampagnenfortschritt
- geplante und vergangene Sitzungen
- Kampagnenbild
- Import und Export vollständiger Kampagnen

Mehrere Kampagnen können unabhängig voneinander innerhalb derselben MeisterWerk-Installation verwaltet werden.

---

## NSC-Werk

Im NSC-Werk werden Nichtspielercharaktere verwaltet.

Zu einem NSC können unter anderem hinterlegt werden:

- Name und Beschreibung
- Status und Werte
- Notizen
- Ausrüstung
- Portrait
- Bildergalerie
- Fraktionen
- Beziehungen zu anderen NSC
- Orte
- Handouts

NSC können mehreren Kampagnen zugeordnet werden, ohne für jede Kampagne eine neue Kopie anlegen zu müssen.

Einzelne oder mehrere NSC können außerdem als portable **`.mwnpc`-Pakete** exportiert und in einer anderen MeisterWerk-Installation wieder importiert werden.

---

## Fraktionen

Fraktionen besitzen eigene Beschreibungen und Mitglieder.

Damit können beispielsweise

- Organisationen
- Orden
- Familien
- politische Gruppen
- Geheimbünde
- militärische Einheiten

als eigenständige Bestandteile der Spielwelt verwaltet und mit NSC und anderen Kampagnenobjekten verbunden werden.

---

## OrtsWerk

Das OrtsWerk verwaltet Schauplätze der Kampagne.

Orte können beschrieben und mit anderen Inhalten verknüpft werden, beispielsweise mit:

- NSC
- Handouts
- Karten

So entsteht aus einzelnen Einträgen nach und nach eine zusammenhängende Spielwelt.

---

## KartenWerk

Im KartenWerk können Karten und Pläne verwaltet werden.

Karten können innerhalb einer Kampagne verwendet und mit anderen Objekten verknüpft werden.

Marker ermöglichen es, relevante Stellen einer Karte mit weiterführenden Informationen und Spielmaterial zu verbinden.

---

## HandoutWerk

Das HandoutWerk verwaltet Materialien, die während des Spiels benötigt oder den Spielern gezeigt werden sollen.

Dazu können beispielsweise gehören:

- Briefe
- Dokumente
- Bilder
- Hinweise
- Illustrationen
- andere vorbereitete Spielmaterialien

Handouts können mit Orten, NSC und anderen Kampagnenelementen verbunden werden.

---

## PlotWerk

Das PlotWerk unterstützt die Planung von Handlungssträngen und Ereignissen.

Neben klassischen Plotinformationen können Inhalte in graphischer Form miteinander verbunden werden.

Dadurch lassen sich beispielsweise Beziehungen zwischen

- NSC
- Orten
- Fraktionen
- Ereignissen
- Plotpunkten
- Handouts

sichtbar machen.

---

## Kampagnennetz

Das Kampagnennetz stellt Beziehungen innerhalb der Spielwelt graphisch dar.

Knoten können beispielsweise NSC, Orte, Fraktionen, Plotinhalte oder Handouts repräsentieren.

Damit lässt sich eine Kampagne nicht nur als Liste von Einträgen betrachten, sondern als **Netz zusammengehöriger Elemente**.

Knoten können gemeinsam ausgewählt, verschoben und über Kontextmenüs bearbeitet werden.

---

## Sitzungsmodus

Der Sitzungsmodus ist für die eigentliche Spielrunde gedacht.

Er bündelt die Informationen, die während einer Sitzung benötigt werden, und ermöglicht unter anderem den schnellen Zugriff auf:

- beteiligte NSC
- Szenen
- Karten
- Handouts
- Spielmaterial

Neue NSC können während des Spiels schnell erfasst werden.

Abgeschlossene Szenen können direkt in die Chronik der Kampagne übernommen werden.

---

## ChronikWerk

Das ChronikWerk hält fest, was innerhalb einer Kampagne tatsächlich geschehen ist.

Einträge sind Sitzungen zugeordnet und können unter anderem enthalten:

- Zusammenfassungen
- Notizen
- Ereignisse
- beteiligte NSC

Damit entsteht im Laufe der Kampagne eine fortlaufende Chronik der Spielwelt.

---

## Galerie und Präsentation

Bilder können innerhalb verschiedener Werke verwendet und gesammelt werden.

Für geeignete Inhalte stehen Präsentationsfunktionen zur Verfügung, mit denen Bilder beispielsweise auf einem zweiten Bildschirm oder Beamer gezeigt werden können.

---

# Import und Export

MeisterWerk speichert Kampagnen nicht nur innerhalb der lokalen Datenbank.

Vollständige Kampagnen können als portable Pakete exportiert und auf einer anderen MeisterWerk-Installation wieder importiert werden.

Dabei werden die zur Kampagne gehörenden Daten und benötigten Assets gemeinsam übertragen.

Zusätzlich können NSC unabhängig von einer vollständigen Kampagne über das **`.mwnpc`-Format** ausgetauscht werden.

Damit bleiben Kampagnen und Spielmaterial **portabel und sicherbar**.

---

# Automatische Updates

MeisterWerk kann beim Programmstart prüfen, ob eine neuere stabile Version veröffentlicht wurde.

Wenn ein Update vorhanden ist, zeigt MeisterWerk:

- die installierte Version
- die verfügbare Version
- die Release-Hinweise der neuen Version

Vor der Installation wird das heruntergeladene Paket mittels **SHA-256** geprüft.

Unter Linux und Windows führt ein sichtbarer Update-Helfer anschließend die Aktualisierung durch und zeigt die einzelnen Schritte an:

- MeisterWerk wird beendet
- Update wird entpackt
- Programmdateien werden aktualisiert
- MeisterWerk wird neu gestartet

Danach beendet sich der Update-Helfer selbst.

Unter Android wird die geprüfte APK an den Android-Paketinstaller übergeben. Die abschließende Installation wird dort wie üblich vom Benutzer bestätigt.

Ist keine Internetverbindung vorhanden, kann MeisterWerk normal weiterverwendet werden. Die Update-Prüfung beeinträchtigt den Offline-Betrieb nicht.

---

# Lokal statt Cloud

Die eigentliche Kampagnenverwaltung von MeisterWerk arbeitet **lokal auf dem Gerät**.

Es besteht keine Abhängigkeit von:

- einem Benutzerkonto
- einer Cloud
- einem externen Kampagnendienst
- einer KI

Die Internetverbindung wird insbesondere für die Prüfung und den Download neuer MeisterWerk-Versionen benötigt.

Die eigenen Kampagnendaten bleiben davon getrennt.

---

# Systemunabhängig

MeisterWerk ist nicht auf ein bestimmtes Pen-&-Paper-Regelwerk festgelegt.

Es kann daher beispielsweise für Fantasy-, Horror-, Science-Fiction- oder andere Kampagnen verwendet werden.

Die Anwendung verwaltet die **Kampagne und ihre Zusammenhänge**, ohne ein bestimmtes Regelsystem vorzuschreiben.

---

# Beispielkampagnen

MeisterWerk enthält beziehungsweise unterstützt Beispielkampagnen, mit denen sich die verschiedenen Funktionen und Verknüpfungen nachvollziehen lassen.

Sie können als Anschauungsmaterial dienen und zeigen praktisch, wie die einzelnen Werke zusammenspielen.

---

# Installation

## Linux

Das Linux-Paket herunterladen und entpacken.

Anschließend MeisterWerk über den enthaltenen Starter ausführen.

Die Anwendung bringt die für ihren Betrieb benötigte Java-Laufzeit selbst mit.

---

## Windows

Das Windows-Paket herunterladen und entpacken.

Danach **MeisterWerk.exe** starten.

Eine zusätzliche Java-Installation ist nicht erforderlich.

---

## Android

Die signierte APK herunterladen und auf dem Android-Gerät installieren.

Je nach Android-Version muss die Installation von Apps aus der verwendeten Quelle einmalig erlaubt werden.

Spätere signierte MeisterWerk-Versionen können als Aktualisierung derselben Anwendung installiert werden.

---

# Versionshinweise

Die Änderungen einer Veröffentlichung stehen direkt bei der jeweiligen Version unter:

**[→ Alle MeisterWerk-Releases](https://github.com/heinrichkemmler75-spec/MeisterWerk-Releases/releases)**

Die README selbst beschreibt bewusst den allgemeinen Funktionsumfang von MeisterWerk und wird deshalb nicht als fortlaufendes Änderungsprotokoll verwendet.

---

# Lizenz

MeisterWerk wird unter der **GNU General Public License v3.0 or later** veröffentlicht.

Der vollständige Lizenztext befindet sich in der Datei [`LICENSE`](LICENSE).

---

# Projekt

**Entwicklung und Projekt:** Karsten Urban

Mit Unterstützung von **ChatGPT (OpenAI)**.

---

# Unterstützung

Wer die Weiterentwicklung von MeisterWerk unterstützen möchte:

**PayPal:** Karl-Knecht@mein.gmx
