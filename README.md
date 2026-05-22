# Tischplaner

Eine einfache Web-App zur Gestaltung von Tisch- und Sitzplänen — keine Installation, kein Build-Schritt. Einfach `index.html` im Browser öffnen.

Live: **https://dbackhove.github.io/seatplanner/**

## Features

### Tische & Layout
- Tische in drei Formen: rund, quadratisch, rechteckig (Tafel mit Sitzen oben/unten)
- Drag & Drop zum Verschieben, Drehung 0–360°, Snap-to-Grid optional
- Sitzanzahl nachträglich ändern (entfernt zuerst leere Plätze, fragt nur bei belegten)
- Tische duplizieren / umbenennen / löschen
- Raumelemente: Tanzfläche, Bühne, Buffet, Bar, Tür, Wand, Textbeschriftung
- Hintergrundbild (Grundriss) hochladen mit Deckkraft & Skalierung

### Gäste
- Bulk-Eingabe per Textfeld (`Name | Gruppe`) oder CSV-Import
- Pro Gast: RSVP-Status (zugesagt/offen/abgesagt), Notizen, „nicht zusammen mit"-Regeln
- Doppelklick auf Gast öffnet Edit-Modal
- Auto-Zuweisung respektiert Gruppen, Konflikte und RSVP-Status
- Suchfeld findet Gäste und Tische, springt + highlightet im Canvas

### Bedienung
- Canvas pannen (Klick + Halten auf leere Fläche), zoomen (Strg/Cmd + Mausrad)
- Mehrere Pläne parallel speichern, einzeln oder als Bundle exportieren
- Undo/Redo (Ctrl+Z / Ctrl+Shift+Z), 50 Schritte pro Plan
- Speichern in localStorage, Export/Import als JSON

### Drucken & Export
- Plan drucken (skaliert auf A4)
- Sitzliste pro Tisch (für Caterer / Service)
- Tischkarten als A4-Seiten (8 pro Seite)
- PNG-Export des Canvas (via html2canvas, lazy-loaded)

## Nutzung

```bash
open index.html
```

Oder im Browser öffnen.
