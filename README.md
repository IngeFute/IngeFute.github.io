# IngéFuté

Site de tri des 205 écoles d'ingénieurs en France (données du guide Onisep 2026) : filtres, fiches écoles et carte.

## Contenu

- `index.html` : le site complet (données, logo et code inclus dans le fichier).
- `b/` : tuiles du Plan IGN de secours, utilisées seulement si le Plan IGN en ligne ne répond pas.
- `.nojekyll` : indique à GitHub Pages de publier les fichiers tels quels.

## Mise en ligne avec GitHub Pages

1. Crée un dépôt (par exemple `ingefute`) et dépose tout le contenu de ce dossier à la racine.
2. Dans le dépôt : **Settings > Pages**, source **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
3. Après une à deux minutes, le site est disponible à l'adresse `https://<ton-compte>.github.io/ingefute/`.

## Sources

- Écoles : Onisep, « Les écoles d'ingénieurs » (2026). Données susceptibles d'erreurs ou de modifications.
- Adresses : fiches établissements Onisep. Coordonnées : géocodage IGN (Base Adresse Nationale, data.geopf.fr).
- Fond de carte : Plan IGN © IGN (licence ouverte Etalab 2.0). Carte : Leaflet, Leaflet.markercluster.
