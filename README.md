# KI-Förder-Navigator — iPhone PWA

## In 5 Minuten auf das iPhone

### Schritt 1: GitHub-Konto
Kostenlos unter github.com registrieren (falls noch nicht vorhanden).

### Schritt 2: Repository erstellen
1. github.com → „New repository"
2. Name: `ki-navigator` (genau so)
3. Public auswählen
4. „Create repository" klicken

### Schritt 3: Dateien hochladen
1. Im Repository auf „uploading an existing file" klicken
2. Diese 3 Dateien hochladen:
   - index.html
   - manifest.json
   - sw.js
3. „Commit changes" klicken

### Schritt 4: GitHub Pages aktivieren
1. Repository → Settings → Pages
2. Source: „Deploy from a branch"
3. Branch: main → / (root)
4. Save

Nach ca. 2 Minuten ist die App erreichbar unter:
`https://IHR-BENUTZERNAME.github.io/ki-navigator`

### Schritt 5: Auf iPhone installieren
1. Safari öffnen (kein Chrome — nur Safari unterstützt PWA auf iOS!)
2. URL eingeben: `https://IHR-BENUTZERNAME.github.io/ki-navigator`
3. Teilen-Symbol tippen (Rechteck mit Pfeil nach oben)
4. „Zum Home-Bildschirm" tippen
5. Name bestätigen → „Hinzufügen"

Die App erscheint jetzt als Icon auf dem Home-Bildschirm —
vollständig offline nutzbar, ohne App Store, ohne Kosten.

---

## Was die App kann

- Firmendaten & KI-Vorhaben eingeben
- Automatische Analyse aller passenden Förderprogramme
- Förder-Score (0–100)
- KI-Readiness Report als PDF herunterladen
- Vorausgefüllte Antragsformulare für alle Programme herunterladen
- Vollständig offline nutzbar (Service Worker)
- Kein Backend, keine Daten werden gesendet

## Förderprogramme enthalten

- BAFA Unternehmensberatung (bis €2.800)
- Forschungszulage FZulG (bis €4,2 Mio.)
- ZIM Zentrales Innovationsprogramm (bis €310.500)
- KMU-innovativ IKT & KI BMBF (bis €500.000)
- KfW Digitalisierungskredit 267
- EIC Accelerator Horizon Europe (bis €2,5 Mio.)
- DIGI-Zuschuss Hessen
- Digitalbonus Bayern Plus
- MID NRW
- Invest BW

## Updates einspielen

Einfach neue index.html in GitHub hochladen → App aktualisiert sich automatisch beim nächsten Start.
