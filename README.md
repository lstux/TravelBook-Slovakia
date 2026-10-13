# Carnet Slovaquie — données

Carnet de voyage Slovaquie (Poznávačka) : étapes, lieux, hébergements, tables, spécialités et repères culturels pour un road-trip en famille entre Vienne, la Slovaquie et Budapest. Ce dépôt ne contient que les données ; il est lu par le moteur [TravelBook](https://github.com/lstux/TravelBook), qui n'est pas ici.

**Site en ligne : <https://lstux.github.io/TravelBook-Slovakia/>** — publié automatiquement par GitHub Pages à chaque push sur `main` (workflow `.github/workflows/pages.yml`).

## Contenu

- `md/` : les fiches au format TMD (une par lieu, dodo, table, spécialité, culture, étape) et `etapes.txt`, l'ordre du voyage.
- `pages/` : pages éditoriales écrites à la main (intro du pays, articles d'histoire).
- `img/` : images utilisées par les fiches.
- `manifest.json` : manifeste PWA (nom de l'application, chemins de déploiement).
- `geocache.json` : coordonnées géocodées (cache de `geocode.py`, long à regénérer).
- `imgcache.json` : images non trouvées (cache de `fetch_images.py`).

Les rapports générés (`*-a-completer.md`) ne sont pas versionnés : ils se regénèrent.

## Utilisation

Le moteur lit ce dépôt depuis `data/` (clone local), ou depuis le chemin donné par `--data DIR` ou `CARNET_DATA`. Voir le README du moteur.

Le format des fiches est décrit dans `docs/format-tmd.md` du moteur.
