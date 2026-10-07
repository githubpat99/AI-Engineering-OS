# Routing: Entscheidungshilfe

Die verbindlichen Kurzregeln stehen in [../AGENTS.md](../AGENTS.md). Diesen Leitfaden nur bei unklarer Zuordnung oder einer Routing-Anpassung laden. Modusauswahl erfolgt durch den arbeitenden Agenten; es läuft kein separater Router-Prozess.

## Entscheidung

1. Allgemeine Erklärung/Formulierung ohne bestehende Fakten? CHAT.
2. Benötigt die Antwort einen bestehenden Stand/Entscheid? CONTEXT.
3. Ist eine Änderung, Recherche, Auswertung oder Tool-Aufgabe nötig? AGENT.
4. Verlangt der Auftrag mehrere abhängige Ergebnisse, breite Quellenintegration oder eine erhebliche Umsetzung? MISSION.

Die passende Stufe direkt wählen. Bei Unklarheit den sicher bearbeitbaren Teil angehen und nur entscheidende fehlende Angaben klären. Ein neues Thema, viele Ordner oder eine fehlende Datei erzeugen keine Mission. MISSION beginnt mit derselben sparsamen Orientierung wie AGENT.

## Organisationszuordnung

| Organisation / lokaler Pfad | Typischer Kontext |
| --- | --- |
| [AI-Engineering-OS](../AI-Engineering-OS/) | Software, Architektur, technische Implementierung; vollständige Code-Repositories unter AI-Engineering-OS/projects: pensionierungsplanung, vermoegensplanung und next-app samt htmltools; kompakte Themenbriefe separat unter briefs |
| [AI-Consulting OS](../AI-Consulting-OS/) | Beratung, Engagements, Steuerwissen, Management-Ergebnisse |
| [AI-Private OS](../AI-Private-OS/) | Private Cases, Genossenschaft/HV, Strassensanierung, PV, Fahrzeugwechsel |

Vorhandene Ordnernamen sind verbindlich; keine vermeintlichen Aliasordner wie AI-OS-GLOBAL oder engagements annehmen. Organisation aus Arbeitsordner, benanntem Pfad und Auftrag bestimmen. Andere Organisationen nicht zur allgemeinen Orientierung lesen. Personen-, Kunden- und Falldaten nicht in shared kopieren.

## Beispiele und zulässige Vertiefung

| Anfrage | Modus | Gezielter Einstieg / Eskalation |
| --- | --- | --- |
| Was ist DDD? | CHAT | Direkt erklären. |
| Formuliere diesen Satz kürzer. | CHAT | Mit dem Text im Chat arbeiten. |
| Wann ist die nächste HV laut Dossier? | CONTEXT | Privater State bzw. Case-status.md; bei Aktualitätszweifel Terminbeleg nachladen. |
| Was ist der nächste Schritt bei der PV-Anlage? | CONTEXT | Case-status.md und bei Bedarf next-steps.md; kein automatischer Offertenvergleich. |
| Wie weit ist das Zürcher Individualbesteuerungs-Papier? | CONTEXT | Consulting-State und verlinkter Entwurf; nicht automatisch Steuerquellen importieren. |
| Vergleiche diese drei PV-Offerten. | AGENT | Passenden Case/Skill und konkrete Offerten; Quellen nach der Orientierung progressiv laden. |
| Ergänze Abschnitt X im Positionspapier. | AGENT | Zieldokument und konkret benötigte Belege; keine Gesamt-Recherche. |
| Implementiere eine grössere Änderung mit Migration und Abnahme. | MISSION | Relevantes Projekt, kurzer Etappenplan, Umsetzung und angemessene Prüfung. |
| Erstelle aus allen HV-Unterlagen eine vollständige Entscheidungsgrundlage. | MISSION | Case begrenzen, Quellenregister gezielt nutzen, führende Dokumentformate beachten. |

FAST ist eine Präferenz für wenig Kontext und kurze Ausgabe, keine Erlaubnis zum Weglassen einer beauftragten Änderung. DEEP erhöht die Tiefe bei Bedarf. Eine Modusänderung kurz erläutern, wenn sie Aufwand oder Ergebnisumfang wesentlich verändert; keine Bestätigung für die blosse Eskalation verlangen. Bestehende Handlungsberechtigungen bleiben massgeblich.
