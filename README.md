# Planungs-Visualisierungen

Interaktive HTML-Visualisierungen aus meinem Studium an der RWTH Aachen (2025–2026). Sie bereiten Inhalte aus Stadtplanung, Beteiligung und Prozessanalyse für Präsentationen und Abgaben visuell auf. Jede Datei ist eine einzelne, eigenständige HTML-Seite.

## Inhalt

| Ordner / Datei | Thema | Was die Visualisierung zeigt |
|---|---|---|
| `Bitte ein Byte/Ablauf.html` | **Bitte ein BYTE – datengestützte Stadtentwicklung Dormagen** | Infografik zur Urbanen Datenplattform (UDP): Ausgangsproblem in der Planung, Aufbau der Plattform, Beispiele für UDP-Dashboards (Diagramme mit Chart.js), der iterative Weg von der Idee zur Entscheidung und ein Fazit. |
| `tu!Lab/tu!lab .html` | **Persona-Analyse „KlimaMatch“** (erste Fassung) | Vier Zielgruppen zu Klimaschutz und Lebensstil: die Offenen, die Pragmatischen, die Performer und die Skeptischen. |
| `tu!Lab/Zielgruppen.html` | Persona-Analyse, Redesign (horizontal) | Dieselben vier Personas in horizontaler Kartenansicht. |
| `tu!Lab/andere version.html` | Persona-Analyse, Redesign (Tabelle) | Dieselben Personas als Vergleichstabelle. |
| `Quartiersmanagment/Akteurmapping.html` | **Akteursmapping eines Zwischennutzungsprojekts** | Netz der Beteiligten an einer Zwischennutzung (Initiative, Politik, Verwaltung, Eigentümer, Medien, Freiwillige) mit Rollen und Beziehungen. Die Verbindungslinien werden per JavaScript gezeichnet. |
| `Quartiersmanagment/Aktuermapping neu.html` | Akteursmapping, überarbeitete Fassung | Wie oben, mit angepasstem Layout. |
| `Prozessgestaltung/Aachen_Zeitstrahl.html` | **Detail-Zeitstrahl Innenstadtmobilität Aachen** | Prozessrekonstruktion „Automobilität & Innenstadtkonzept Aachen“: Meilensteine von den ersten Sperrforderungen über die Mobilitätsstrategie 2030 und den Radentscheid bis zur emissionsfreien Innenstadt. |

Im Akteursmapping sind die realen Personen **pseudonymisiert** („Akteur A“ bis „Akteur E“). Rollen, Organisationen, Projekt und Ort sind so allgemein beschrieben, dass niemand darüber erkennbar ist.

### Autorschaft

| Visualisierung | Art der Arbeit |
|---|---|
| Bitte ein BYTE | Einzelarbeit |
| tu!Lab – Persona-Analyse | Einzelarbeit |
| Quartiersmanagement – Akteursmapping | Einzelarbeit |
| Prozessgestaltung – Zeitstrahl | Gruppenarbeit (Gruppe 7). Konzeption und Umsetzung der Visualisierung und des Codes: Lukas Willmy. Die inhaltliche Grundlage stammt aus der Gruppenarbeit. |

## Öffnen

Repository klonen oder herunterladen und `index.html` (Übersicht mit Links zu allen Seiten) oder direkt die gewünschte `.html`-Datei im Browser öffnen. Ein Build oder Server ist nicht nötig. Mit GitHub Pages ist `index.html` die Startseite.

Die meisten Seiten laden Tailwind CSS, Chart.js, Lucide-Icons und Google Fonts über ein CDN und brauchen deshalb eine **Internetverbindung**. Nur `Prozessgestaltung/Aachen_Zeitstrahl.html` funktioniert vollständig offline.

## Herkunft & Datierung

Die Dateien lagen ursprünglich nicht in Git. Die Historie wurde nachträglich aufgebaut, und jeder Commit gehört zu genau einer von drei Klassen. Welche das ist, steht im Commit selbst:

| Klasse | Commit-Datum | Kennzeichnung im Commit | In diesem Repo |
|---|---|---|---|
| **belegt** | historisch, aus einem unabhängigen Beleg (z. B. Abgabe-E-Mail) | `Provenance: <Beleg>` | keine |
| **erschlossen** | historisch, aus der Datei-Änderungszeit | `Dating: inferred-from-file-mtime`, `Source:`, je Datei `Provenance: file-mtime …` | 4 Commits (Juli 2025): Bitte ein BYTE, drei tu!Lab-Fassungen |
| **rekonstruiert** | Tag des Imports | `Reconstructed: true` | Akteursmapping (pseudonymisiert), Zeitstrahl |

Diese README und alle späteren Änderungen sind normale Commits mit ihrem tatsächlichen Datum.

Zur Einordnung:

- **Erschlossene Daten sind Näherungen.** Die Änderungszeit zeigt, wann eine Datei zuletzt gespeichert wurde, nicht wann die Arbeit begann. Kopieren oder Synchronisieren kann sie verändern. Die importierten Dateien wurden byte-genau übernommen, Inhalt und Zeitstempel sind unverändert.
- **Bereinigte Dateien werden nie rückdatiert.** Das Akteursmapping stammt laut Dateizeit vom Juli 2025. Weil es für die Veröffentlichung pseudonymisiert wurde, trägt der Commit das Datum der Bereinigung.
- **Unzuverlässige Dateizeiten werden nicht verwendet.** Für den Ordner der Prozessgestaltung sind die Dateizeiten kein verlässlicher Beleg. Der Zeitstrahl trägt deshalb das Importdatum, laut Dateizeit entstand er im April 2026.
- Die Commits zeigen den Stand der Dateien, nicht den tatsächlichen Arbeitsverlauf. Zwischenstände, die nicht als Datei erhalten sind, wurden nicht erfunden.

## Lizenz

© Lukas Willmy – alle Rechte vorbehalten. Ansicht ausdrücklich erwünscht.
