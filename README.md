# SenAnimes — publications

Ce dépôt ne contient **aucun code source**. Il sert deux choses :

- `latest.json` — le manifeste que l'application interroge au lancement pour
  savoir si une version plus récente existe.
- les **Releases** — les fichiers APK eux-mêmes.

Il est public parce que l'application doit pouvoir lire ce manifeste sans jeton :
un jeton embarqué dans un APK est lisible par n'importe qui, ce qui reviendrait à
publier la clé d'accès au dépôt privé.
