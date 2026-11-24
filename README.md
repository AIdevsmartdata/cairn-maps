# Cairn — cartes hors ligne

Cartes vectorielles au format [Mapsforge](https://github.com/mapsforge/mapsforge) (version 4) pour l'appli de randonnée et de trail **Cairn** (montre Wear OS + compagnon Android), découpées en dalles de 0,5° × 0,5°.

Les fichiers sont publiés dans les [releases](../../releases) de ce dépôt, avec un `catalog.json` qui décrit chaque dalle (emprise, taille, SHA-256) et des zones nommées (« Béarn et Soule », « Andorre »…). L'appli télécharge le catalogue depuis `releases/latest/download/catalog.json`, puis les dalles du même dossier.

## Couverture

| Jeu | Emprise | Dalles | Taille |
|---|---|---|---|
| `pyrenees-2026-11-24` | 42,0° N → 43,5° N, 2,0° W → 3,5° E (deux versants, Andorre) | 33 | 490 Mo |

## Sources et licences

- **Données cartographiques** : © les contributeurs d'[OpenStreetMap](https://www.openstreetmap.org/copyright), sous licence [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Extraits régionaux de [Geofabrik](https://download.geofabrik.de/).
- **Altitude (courbes de niveau, équidistance 10 m)** : contient des données modifiées du Copernicus DEM GLO-30 © DLR e.V. 2010-2014 et © Airbus Defence and Space GmbH 2014-2018, fournies dans le cadre de COPERNICUS par l'Union européenne et l'ESA ; tous droits réservés. [Conditions](https://doi.org/10.5270/ESA-c5d3d65).
- Les fichiers `.map` de ce dépôt sont une base de données dérivée d'OpenStreetMap et sont distribués sous la même licence **ODbL 1.0**. Toute réutilisation doit mentionner « © les contributeurs d'OpenStreetMap » et conserver cette licence.

Fabriqués avec osmosis, pyhgtmap et mapsforge-map-writer (dates des extraits OSM et empreintes SHA-256 des sources dans `catalog.json`).

---

Offline vector maps (Mapsforge v4) for the **Cairn** hiking app, in 0.5° tiles. Map data © OpenStreetMap contributors, ODbL 1.0; contours from Copernicus DEM GLO-30. The `.map` files are a derivative database released under ODbL 1.0.
