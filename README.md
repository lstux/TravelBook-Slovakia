# Carnet Slovaquie — données

Données du carnet de voyage Slovaquie (Poznávačka). Dépôt privé : il est lu par le moteur [TravelBook](https://github.com/lstux/TravelBook), qui n'est pas ici.

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
