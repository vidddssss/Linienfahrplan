# Mein persönlicher Linienfahrplan (Android/PWA)

## Dateien
- `index.html`: die App
- `manifest.json`: Installationsinformationen
- `service-worker.js`: Offline-Cache
- `icon.svg`: App-Symbol

## Veröffentlichung mit GitHub Pages
1. Melde dich auf https://github.com an und erstelle ein neues Repository, z. B. `linienfahrplan`.
2. Lade alle vier Dateien aus diesem Ordner ins Stammverzeichnis des Repositorys hoch.
3. Öffne **Settings → Pages**.
4. Unter **Build and deployment** wähle **Deploy from a branch**, Branch `main`, Ordner `/(root)`, dann **Save**.
5. Warte, bis GitHub Pages die Website veröffentlicht hat. Die Adresse wird in **Settings → Pages** angezeigt.
6. Öffne die HTTPS-Adresse in Chrome auf Android. Wähle im Menü ⋮ **App installieren** oder **Zum Startbildschirm hinzufügen**.

## Hinweise
- Der Service Worker benötigt HTTPS (GitHub Pages erfüllt dies) und wird erst nach dem ersten Online-Aufruf aktiv.
- Browser-Speicherung gilt für diesen Browser auf diesem Gerät. Exportiere regelmäßig eine JSON-Sicherung.
- Das Repository und die veröffentlichte Website können öffentlich zugänglich sein. Lade keine privaten Daten hoch.
- Jede Abfahrt wird ausschließlich per Tastendruck bestätigt; es gibt keine automatische Weiterschaltung.
