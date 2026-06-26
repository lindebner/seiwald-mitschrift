# seiwald-mitschrift

Das ist die README.md-Datei. MD seht für Markdown. Markdown ist eine heutzutage weit verbreitete Auszeichnungssprache (_Markup Languege_, [Wikipedia](https://en.wikipedia.org/wiki/Markup_language)).

Weitere bekannte Auszeichnungssprachen sind:

- Hyperttext Markup Language (HTML)
- Extensible Markup Language (XML)
- Yet Another Markup Language (YAML, YML)

## Installation von Node.JS

Javascript läuft in normelen Umständen in einer Browser-Sandbox (nur in Browser).
Seit ca. 2010 gibt eine Laufzeitumgebung (_Runtime Environment_) für JS, damit damit man auch serverseitig programmieren und ausführen kann: [Node.js](https://nodejs.org/en)

## Installation vin pnpm

Der standardmäßige _Package Manager_ für Node.js ist `npm` (_node packege Manager_). Eine etwas modernere und inzwischen beliebterer Variante ist [`pnpm`](https://pnpm.io/)

## Instalation von Strapi

Installation mit dem Skript `pnpm create strape`.
Daraufhinführt das CLI (_Command Line Interface_) durch die Installation.
Falls bei der Installation sogenannte `build scripts` nicht ausgeführt werden können, schlägt die CLI die Fehelerbehandelung selbständig vor:

1. Wechsle in das Installationsverzeichnis (z.B. mit `cd my-strapi-project`)
2. Neuerlicher Versuch der Installation mit `pnpm install`. Dieser scheitert in der Regel - die Build-Skripte müssen mit `pnpm approve-builds` manuell freigeben werden.

# VibeCoding / AgenticEngineering mit VS-Code und GitHub Copilot

VibeCoding passiert in VS-Code in erster Linie über die neue eingeführte Agent View.
Dort können alle Anpassungen des "_Coding Harness_" vorgenommen werde. Wir können unseren _Harness_ mit verschiedene Methoden anpassen:

- **MCP-Server:**
  MCP steht für _Model Context Protokoll_. Es ist ein Standard, der von Anthropic entwickelt wurde. Mit Hilfe von MCP können Chatbots / LLMs (_Large Language model_) auf zusätzliche Tools zugreifen, die sie zu Experten in einem bestimmten Themenbereich machen.
