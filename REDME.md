<!-- Wie der Server gestartet wird -->
node index.js

<!-- Was der Cookie speichert -->
Der Cookie heißt username.

Er speichert den Namen, den du im Formular eingibst.

Er hat die Flags HttpOnly und maxAge: 60000 (d. h. er läuft nach 1 Minute ab).

<!-- Wo man ihn in den DevTools sehen kann -->
Browser öffnen → F12 → Tab Application (Chrome/Edge) oder Speicher (Firefox).

Dort unter Cookies → http://localhost:3000
findest du den Cookie username mit dem gespeicherten Namen.