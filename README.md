# Schemelec

Éditeur de schémas électrotechniques installable comme application web progressive (PWA).

## Lancer l’application

L’installation et le mode hors ligne nécessitent une origine sécurisée : HTTPS ou `localhost`. L’ouverture directe du fichier `index.html` (`file://`) ne permet pas d’installer l’application.

Pour tester localement, lancez un serveur depuis ce dossier :

```bash
python3 -m http.server 8000
```

Ouvrez ensuite [http://localhost:8000](http://localhost:8000). La page principale est `index.html`; `schémélecv1.html` reste également disponible.

## Installer

- Sur ordinateur ou Android, utilisez le bouton **Installer** dans l’application lorsqu’il est proposé, ou la commande d’installation du menu de votre navigateur.
- Sur iPhone ou iPad, ouvrez l’application dans Safari, touchez **Partager**, puis **Sur l’écran d’accueil**.
- Pour une installation depuis un autre appareil, hébergez les fichiers sur un site servi en HTTPS.

La première ouverture doit être faite en ligne pour charger les fichiers. Ensuite, le service worker met en cache l’application pour permettre son utilisation hors ligne. Les schémas restent enregistrés localement dans le navigateur.
