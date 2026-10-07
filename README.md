# Lokale AI-OS-Basis

Stand: 2026-10-07. Gemeinsame Arbeitsregeln für drei getrennte Organisationen. Die tatsächlichen Engineering-Code-Repositories pensionierungsplanung, vermoegensplanung und next-app samt htmltools liegen gemeinsam unter AI-Engineering-OS/projects; Consulting und Private behalten ihre vorhandenen Fachordner und Git-Repositories.

## Einstieg

- Globale Regeln: [AGENTS.md](AGENTS.md).
- Organisationsstand und Navigation: jeweilige CURRENT_STATE.md / INDEX.md.
- Details zur Ausführung: [shared/PERFORMANCE.md](shared/PERFORMANCE.md), [shared/ROUTING.md](shared/ROUTING.md), nur bei Bedarf.
- Wiederverwendbare neutrale Vorlagen: [shared/templates](shared/templates/).

| Organisation | Stand | Navigation |
| --- | --- | --- |
| Engineering | [CURRENT_STATE](AI-Engineering-OS/CURRENT_STATE.md) | [INDEX](AI-Engineering-OS/INDEX.md) |
| Consulting | [CURRENT_STATE](AI-Consulting-OS/CURRENT_STATE.md) | [INDEX](AI-Consulting-OS/INDEX.md) |
| Private | [CURRENT_STATE](AI-Private-OS/CURRENT_STATE.md) | [INDEX](AI-Private-OS/INDEX.md) |

## Einbindung in Codex

Die Organisationen Consulting und Private sind eigene Git-Wurzeln. Deshalb kann die automatische Anweisungserkennung am jeweiligen Repository beginnen und die darüber liegende AI/AGENTS.md auslassen. Jede lokale AGENTS.md verlangt ausdrücklich, die Parent-Basis einmal zu lesen, wenn sie nicht bereits geladen ist. Die Kernregeln stehen vollständig in der Basis; PERFORMANCE.md und ROUTING.md müssen für den Fast-Path nicht zusätzlich geladen werden.

Neue Arbeit im AI-Parent oder in der jeweiligen Organisation starten; in bestehenden Chats die aktualisierte globale und lokale AGENTS.md einmal ausdrücklich lesen lassen. Die drei Engineering-Repositories laden die gemeinsame Basis über ihre eigenen AGENTS.md ausdrücklich nach; ihre fachlichen Projektregeln ebenfalls beachten. Ein isolierter Clone enthält den AI-Parent/shared nicht: auf jedem Rechner separat verfügbar halten. Dieser Umbau hat keine Synchronisation des Parents, keine App-Einstellung und keinen neuen Git-Root eingerichtet.

Die Modi CHAT, CONTEXT, AGENT und MISSION sind Arbeitsanweisungen. Sie sind kein installierter Software-Router, kein technisch erzwungenes Dateilimit und keine Garantie bestimmter Antwortzeiten. Modell-/Laufzeitregeln gehen vor.

Offizielle Einbindungsreferenz: [AGENTS.md discovery](https://learn.chatgpt.com/docs/agent-configuration/agents-md).

## Konsolidierung und Erhalt

Der frühere Ordner AI-Global OS mit AGENTS.md/PERFORMANCE.md wurde aus der aktiven Struktur in eine datierte lokale Sicherung unter `.ai-os-backups/` verschoben. Alte globale Pfade werden nicht mehr verwendet. Fachinhalte, Quellen, Fallentscheide und bestehende uncommittete Arbeit bleiben erhalten. Backups niemals als aktuellen Arbeitskontext automatisch lesen.

Kein shared/skills-Verzeichnis angelegt: Die sieben vorhandenen privaten Verfahren sind fachspezifisch, Consulting enthält Skill-Vorlagen/Startkategorien. Es gibt bisher keinen nachgewiesenen gemeinsamen Skill zur Konsolidierung. Fachskills bleiben an ihren gepflegten Pfaden; INDEX.md ermöglicht gezielte Auswahl. Neutrale Vorlagen werden dagegen zentral gepflegt.

## Gemeinsamer Code-Standort — 07.10.2026

Unter AI-Engineering-OS/projects liegen die drei vollständigen Git-Repositories inklusive ihrer bisherigen Historie, Remotes und lokalen Dateien. Die früheren drei Projektpfade unter C:\Users\patri sind Verzeichnisverknüpfungen zu diesem gemeinsamen Standort. Projektbriefe liegen getrennt unter AI-Engineering-OS/briefs. [Engineering.code-workspace](AI-Engineering-OS/Engineering.code-workspace) bietet einen gemeinsamen Editor-Einstieg. Git-Commits und Pushes bleiben je Repository getrennt; ein neuer Parent-Git-Root wurde nicht angelegt.
