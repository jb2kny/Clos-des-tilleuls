# Le Clos des Tilleuls — Site vitrine

Site statique (HTML + CSS) présentant l'annonce du gîte **Le Clos des Tilleuls** à Francueil (Touraine), et redirigeant vers la réservation Airbnb.

## Contenu

- `index.html` — page unique reprenant l'intégralité de l'annonce : capacité, points forts, description, chambres, équipements, avis, emplacement, hôte, règlement intérieur.
- `styles.css` — feuille de style (design vert/sable, responsive).

## Réservation

Tous les boutons et liens « Réserver » pointent vers l'annonce originale :

https://www.airbnb.fr/rooms/1110065343510003006

## Mise en ligne

Ce site est statique : il peut être hébergé sur GitHub Pages, Netlify, Vercel ou tout autre hébergeur de fichiers statiques. Aucune dépendance ni build n'est nécessaire.

Pour un aperçu local :

```bash
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```
