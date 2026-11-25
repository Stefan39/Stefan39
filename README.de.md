# Hallo, ich bin Stefan Jacomeit

[English](README.md) | **Deutsch**

Berater und Umsetzer für KI-Automatisierung aus Bremerhaven. Ich helfe kleinen und mittleren Unternehmen, Abläufe mit KI zu automatisieren, von der ersten Idee bis zur laufenden Integration. Dahinter stehen über 25 Jahre PHP- und Symfony-Entwicklung, damit die Lösungen belastbar sind.

Die Projekte unten sind aus dieser Arbeit entstanden. Die meisten haben in meinen eigenen Systemen angefangen, das GuardedChatBundle etwa schützt den Chat auf [www.jacomeit.de](https://www.jacomeit.de). Alle sind Open Source (MIT, Cockpit unter Apache-2.0), getestet und statisch analysiert.

## MCP-Server: Claude mit Business-Software verbinden

| Projekt | Was es macht |
| --- | --- |
| [mite-mcp-server](https://github.com/Stefan39/mite-mcp-server) | MCP-Server für die mite-Zeiterfassungs-API: Auswertungen, die der Server rechnet, Zeiteinträge und Stammdaten. Standardmäßig nur lesend; schreibende Werkzeuge erscheinen erst, wenn man sie einschaltet, eingegrenzt über eine Allowlist. Auf [npm](https://www.npmjs.com/package/mite-mcp-server), in MCP-Verzeichnissen gelistet, per Klick als Claude-Desktop-Erweiterung (`.mcpb`) installierbar. |
| [lexware-php-mcp](https://github.com/Stefan39/lexware-php-mcp) | Rein lesender MCP-Server für Lexware Office, in PHP auf dem offiziellen MCP-SDK. Belege und Kontakte suchen, einen Beleg mit Nettobeträgen öffnen, Nettoumsatz je Zeitraum. Läuft als eigenständiger Download, PHAR oder Claude-Desktop-Erweiterung, ohne PHP-Einrichtung. |

## KI-Agenten im Betrieb

| Projekt | Was es macht |
| --- | --- |
| [cockpit](https://github.com/Stefan39/cockpit) | Betriebs-Cockpit für eine KI-Automatisierungs-Box, läuft neben n8n und PostgreSQL: sehen, was die Agenten tun, ihre Entwürfe mit einem Klick freigeben, KI-Verbrauch und Kosten im Blick. Agenten melden sich über eine dokumentierte API; Cockpit verschickt, ändert oder löscht nie etwas von selbst. Passkeys, Rollen, strikte CSP. |

## Symfony-Bundles und PHP-Bibliotheken

| Projekt | Was es macht |
| --- | --- |
| [GuardedChatBundle](https://github.com/Stefan39/GuardedChatBundle) | Schutzschicht für öffentliche KI-Chats in Symfony-Apps, auf Basis von Symfony AI: Injection-Vorfilter, Budget- und Rate-Limits, Not-Aus, Prompt-Versionierung, signierte Sessions, Aufbewahrungsfristen. Installation über ein [Flex-Recipe](https://github.com/symfony/recipes-contrib/tree/main/stejac/guarded-chat-bundle). |
| [MiteBundle](https://github.com/Stefan39/MiteBundle) | Symfony-Bundle für die mite-Zeiterfassungs-API: typisierte Services und DTOs für jede Ressource. |
| [zeitangaben](https://github.com/Stefan39/zeitangaben) | Löst umgangssprachliche deutsche Zeitangaben wie „in den Herbstferien“ oder „über Ostern“ in einen konkreten Zeitraum auf, oder liefert eine Rückfrage, wenn sie nicht eindeutig sind. Kennt die Schulferien je Bundesland. |
| [code-thresholds](https://github.com/Stefan39/code-thresholds) | Abhängigkeitsfreie Größen- und Komplexitätsprüfung für PHP, die nur geänderte Dateien prüft: Methodenzahl, Parameter, Returns, Funktionslänge, Verschachtelungstiefe. Entstanden als Ersatz für SonarCloud in der CI. |

Die Composer-Pakete liegen unter [`stejac/*`](https://packagist.org/packages/stejac/) auf Packagist.

## Mehr

- Was die Werkzeuge in der Praxis leisten, mit Einrichtungsanleitungen: [www.jacomeit.de/werkzeuge](https://www.jacomeit.de/werkzeuge)
- Neues öffentliches PHP-Repository anlegen: [php-repo-template](https://github.com/Stefan39/php-repo-template) (README en/de, CI, Community-Dateien)

Issues und Pull Requests sind willkommen.
