# DocScanner (Image → PDF, client-side)

Einfaches Web-Tool zum Scannen von Dokument-Fotos: automatische Erkennung, Perspektivkorrektur, S/W-Optimierung und PDF-Export – alles lokal im Browser.

## Live auf GitHub Pages
1. Repository erstellen (öffentlich).
2. `index.html` hochladen.
3. **Settings → Pages**: Source = *Deploy from a branch*, Branch = `main`, Folder = `/ (root)`.
4. Ergebnis-URL: `https://<dein-user>.github.io/<repo-name>/`

## Nutzung
- Datei-Button am iPhone öffnet direkt die Kamera (via `capture="environment"`).
- Mehrere Bilder → mehrseitiges PDF.
- Keine Daten werden hochgeladen; OpenCV.js und jsPDF kommen via CDN.
