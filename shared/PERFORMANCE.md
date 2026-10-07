# Performance: Anwendung der gemeinsamen Regeln

Führende Kurzregeln: [../AGENTS.md](../AGENTS.md). Dieses Dokument nur bei Fragen zur Ausführung, Budgetplanung oder Optimierung lesen, nicht bei jeder Anfrage.

## Kontextbudget konkret anwenden

Die initiale Lektüre umfasst höchstens fünf verschiedene lokale Dateien. Automatisch bereitgestellte Basis/lokale Anweisungen zählen mit, werden aber nicht nochmals gelesen. Eine Skill-Datei oder dieses Dokument verbraucht ebenfalls einen Platz. Zwingende übergeordnete Anweisungen gehen vor; in diesem Fall keine weiteren initialen Fachdateien hinzufügen.

Beispiele:
- Allgemeine Erklärung: keine zusätzlichen Dateien.
- Unbekannter privater Case-Stand: globale/lokale AGENTS.md, CURRENT_STATE.md, INDEX.md, relevante status.md.
- Bekannte Offertenanalyse: globale/lokale AGENTS.md, Case-Sachstand, ausgewählter Skill, eine relevante Quelle; weitere Offerten danach gezielt für den Vergleich nachladen.
- Bekannte Code-Datei: globale/lokale AGENTS.md, nötige nähere Projektanweisung, Zieldatei, direkt relevante Spezifikation. Der technische Projektumfang bestimmt die spätere Prüfung.

Die Grenze betrifft die erste Orientierung, nicht die gesamte Bearbeitung. Nachladen in kleinen Schritten nur zur konkreten Frage; keine künstlichen Fünferpakete als Umgehung. Grosse Dateien abschnittsweise lesen. Kenntnis aus einem Brief ist keine Prüfung des Originals. Quellenprüfung darf bei Rechts-/Steuerfragen, Fristen, Kosten oder widersprüchlichen Angaben nicht entfallen.

## Suchumfang erweitern

1. Angegebene Datei oder Link direkt verwenden.
2. Über INDEX.md den benannten Case/Engagement/Projektordner wählen.
3. Namen oder Text nur im relevanten Teilordner suchen; ausgeschlossene Bereiche nicht beiläufig einbeziehen.
4. Erst wenn die enge Suche erfolglos ist oder ein beauftragter Gesamt-Audit dies benötigt: auf die Organisation erweitern, mit knappem Grund. Rekursive Suche ist dann aufgabengebunden erlaubt; rekursive Volllektüre bleibt unnötig.

Bei technischen Repositories Build-Verzeichnisse, Dependencies, .git und generierte Ausgaben ausnehmen, sofern nicht gerade dort das Problem liegt. Private Korrespondenz, Originale, Archive und Backups nur gezielt einbeziehen. Keine routinemässige Suche im gesamten Benutzerprofil.

## Agenten und Prüfung

Ein ausführender Agent kann mehrere Fachrollen wahrnehmen. Nur unabhängige Arbeit rechtfertigt zusätzliche Agenten; das verfügbare Laufzeit- und Autorisierungsmodell bleibt massgeblich. Planung/Recherche/Schreiben/Review nicht als separate Pflichtagenten aufziehen.

Prüfung nach Wirkung: Formulierungsänderung direkt lesen; Berechnungen und belegpflichtige Aussagen nachvollziehen; Softwareänderung mit relevanten bestehenden Tests prüfen. Kundenabnahme und rechtlich erforderliche Freigaben bleiben erhalten. Ein Review bedeutet weder automatisch einen zweiten Agenten noch eine neue Zustimmung für bereits autorisierte lokale Arbeit.

## Zustand und Erfolgsmessung

Nur betroffene Detaildateien pflegen; CURRENT_STATE.md hält wenige aktive Themen mit Datum, offenem Punkt und führendem Link. Alte Übersicht gegen Detailstatus prüfen, wenn Aktualität entscheidend ist. Rein lesende Fragen ändern keinen Zustand.

Auf Wunsch anhand vergleichbarer realer Anfragen die Startlektüre, unnötige Tool-Runden und Antwortdauer vergleichen. Keine verpflichtende Telemetrie, neuen Automationen oder Latenzversprechen. Modell, Tools, Netzwerk und bereits geladene Anweisungen beeinflussen die Laufzeit zusätzlich. Diese Basis ist eine Arbeitsanweisung, kein technisch erzwungener Scheduler.
