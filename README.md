# Shut The Box (12er, 10 Runden, Raumcode)

## Auf GitHub Pages veröffentlichen
1. Auf github.com ein neues **öffentliches** Repository anlegen, z. B. `shutthebox`.
2. „uploading an existing file“ → `index.html`, `manifest.json`, `icon-180.png`, `icon-512.png` hochladen → Commit.
3. Repo → **Settings → Pages** → Source: „Deploy from a branch“, Branch `main`, Ordner `/ (root)` → Save.
4. Nach ca. 1 Minute läuft das Spiel unter `https://<dein-name>.github.io/shutthebox/`.

## Aufs iPhone
Link in **Safari** öffnen → Teilen-Symbol → **Zum Home-Bildschirm**.

## Spielen
- Einer tippt **Raum erstellen** und teilt den 4-stelligen Code, der andere gibt ihn ein → **Beitreten**.
- Jeder spielt für sich 10 Runden. Die Gegnerpunkte stehen oben rechts.
- Pro Runde zählen die offenen Klappen als Punkte, alles wird addiert. **Weniger Punkte gewinnen.**
- Sind 7–12 zu, darf man wahlweise mit nur 1 Würfel würfeln.
- Link mit Code direkt: `.../shutthebox/?room=ABCD`

Die Punkte werden über den öffentlichen MQTT-Broker `broker.emqx.io` synchronisiert (nur Name und Punkte, kein Konto nötig).
