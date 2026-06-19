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
