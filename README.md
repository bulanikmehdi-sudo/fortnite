# LAST LANDING — 3D Battle Royale

Eigenständiges, Fortnite-inspiriertes Browsergame mit eigener visueller Identität und prozedural aufgebauter 3D-Insel.

## Start

Voraussetzung: Node.js 20.19+ oder 22.12+.

```bash
npm install
npm run dev
```

Vite zeigt danach die lokale URL (üblicherweise http://localhost:5173) an.

Produktionsbuild:

```bash
npm run build
npm run preview
```

## Steuerung

- **W A S D** – bewegen
- **Maus** – Kamera / zielen
- **Linksklick** – schießen
- **Shift** – sprinten
- **Ctrl** – ducken
- **Leertaste** – springen
- **R** – nachladen
- **1–4** – Inventar-Slots auswählen
- **Esc** – Pause / fortsetzen

## Enthalten

- Third-Person-3D-Spielwelt mit Bäumen, Häusern, Landmarke, Licht und Nebel
- Gegner-KI mit Verfolgung, Angriff und Eliminierungen
- Schießen, Munition, Nachladen, Lebenspunkte und Schild
- Sammelbare Munition, Medkits und Schild-Loot
- Schrumpfende Zone mit Schaden außerhalb des sicheren Bereichs
- Match-Ende, Siege, XP und Levelaufstieg
- Hauptmenü, Locker, kosmetische Freischaltungen, Shop-Ansicht, Battle-Pass-Fortschritt, Profil und Einstellungen
- Lokales Speichern von Fortschritt und Einstellungen

## Technischer Umfang

Dies ist ein lokaler Solo-Trainingsmodus. Es gibt bewusst keine vorgetäuschten Online-Lobbys oder Multiplayer-Synchronisierung. Für echtes Online-Multiplayer wäre als nächster Entwicklungsschritt ein autoritativer Node.js/WebSocket-Server mit Account-/Matchmaking-Service nötig.

Die Welt, Charaktere und UI sind eigens prozedural bzw. per CSS erstellt; es werden keine Fortnite-Originaldateien verwendet.
