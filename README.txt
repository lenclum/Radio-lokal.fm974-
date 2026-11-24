RADIO LOKAL FM 974 — application web installable

Files:
- index.html : interface + Caster.fm player
- logo.jpg : supplied radio logo
- manifest.json : install metadata
- sw.js : offline cache for app shell
- icon-192.png / icon-512.png : app icons

To publish free:
1. Upload these files to a static HTTPS hosting provider (for example GitHub Pages).
2. Open the published HTTPS URL on your phone.
3. Android/Chrome: menu ⋮ > Install app / Add to Home screen.
4. iPhone/Safari: Share > Add to Home Screen.

Mise a jour corrective : le cache de l'application est passe en version v2 pour forcer le navigateur a recharger les fichiers.
Important : le projet ne contient pas l'ancienne adresse zonaradio.x10.mx. Il utilise le lecteur Caster.fm officiel de radiolokalfm.ismyradio.com.
Apres publication de ces fichiers, supprime l'ancien raccourci de l'ecran d'accueil puis ouvre la nouvelle adresse HTTPS et ajoute-la de nouveau a l'ecran d'accueil.

Note: le direct necessite une connexion internet et le lecteur Caster.fm. Le cache hors ligne conserve uniquement l'interface.
