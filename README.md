# Neon Swarm

Ein 2D-Arcade-Shooter als einzelne HTML-Datei — ohne Build, ohne Abhängigkeiten, offline spielbar.

**Spielen:** https://LN848.github.io/neon-swarm/

## Steuerung

- **WASD / Pfeiltasten** — bewegen
- **Maus** — zielen
- **Linke Maustaste halten / Leertaste** — feuern
- **Rechtsklick** — Nova
- **B** — Shop
- **P / Esc** — Pause
- **M** — Ton an/aus

### Touch (Smartphone / Tablet)

- **Linke Bildschirmhälfte ziehen** — Joystick, bewegt die Figur
- **Rechte Bildschirmhälfte ziehen** — zielen; solange der Finger liegt, wird automatisch gefeuert
- **Nova-Taste unten rechts** — Nova (wird nur auf Geräten mit grobem Zeiger angezeigt)

## Features

- Manuelles Zielen, Twin-Stick-Steuerung
- Scrap-Währung und Shop mit 20 unbegrenzten Upgrades
- 12 Gegnertypen inkl. Boss, Wellen-Skalierung
- +1 Herz pro Welle, Bestwert in `localStorage`
- Partikel, Screenshake, WebAudio-Sounds, `prefers-reduced-motion`

## Lokal starten

`index.html` im Browser öffnen — fertig.

## Technik

Eine Datei, Canvas 2D, HTML/CSS/JS inline. Keine externen Ressourcen.
