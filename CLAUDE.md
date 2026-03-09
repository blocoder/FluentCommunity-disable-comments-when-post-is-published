# FluentCommunity-disable-comments-when-post-is-published

## Zweck

PHP-Snippet für WordPress + FluentCommunity. Erkennt den Shortcode `[NoComments]` in Feed-Posts und deaktiviert die Kommentarfunktion beim Veröffentlichen automatisch.

## Verwendete Technologien

- PHP
- WordPress
- FluentCommunity Plugin
- FluentSnippets (empfohlene Einbindung)

## Wichtige Dateien

- `FC disable comments` – PHP-Snippet (ohne `.php`-Endung, für FluentSnippets)

## Verwendung

Das Snippet über FluentSnippets in WordPress aktivieren. Danach `[NoComments]` als eigene Zeile am Ende eines Posts einfügen – Kommentare werden beim Veröffentlichen deaktiviert und der Marker aus dem sichtbaren Inhalt entfernt.
