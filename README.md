# Atlas ferroviaire — fréquentation voyageurs en France

Site interactif : **https://atlas-ferroviaire.github.io/**

Atlas de la fréquentation des gares et du réseau ferré actuel, pour la France métropolitaine, ses 13 régions et ses 96 départements.

## Contenu

- **Carte interactive** du réseau : type de voie (LGV, électrifiée, non électrifiée), nombre de voies, statut des lignes, gares dimensionnées selon leur fréquentation et colorées selon leur évolution depuis 2019.
- **Chiffres clés** par territoire : voyageurs annuels, évolution 2019-2024, longueur du réseau exploité, taux d'électrification, part de voie unique, voyages par habitant, nombre de gares.
- **Évolution de la fréquentation** de 2015 à 2024.
- **Tableau des gares**, triable et filtrable.

Chaque territoire a son propre lien, par exemple :
- Jura : https://atlas-ferroviaire.github.io/#dep-39
- Bourgogne-Franche-Comté : https://atlas-ferroviaire.github.io/#reg-27
- France : https://atlas-ferroviaire.github.io/#france

## Sources

- **SNCF Open Data** : fréquentation en gares, gares de voyageurs, gares TGV, lignes par statut, lignes électrifiées, régime d'exploitation des lignes, lignes LGV (licence ODbL)
- **IGN** : Admin Express (limites départementales et régionales), Licence Ouverte Etalab
- **INSEE** : estimations de population au 1er janvier 2024, Licence Ouverte Etalab

## Choix méthodologiques

- Le réseau pris en compte est le réseau **exploité** ; les lignes neutralisées et fermées sont affichées à part.
- Les sections en **voie banalisée** sont comptées comme **voie unique**, conformément à la documentation SNCF Réseau ; seul le régime « Double voie » est compté comme double voie.
- Les longueurs sont calculées par département à partir des tracés SNCF Réseau.
- La liste des gares TGV a fait l'objet de corrections ponctuelles.

## Confidentialité

Le site ne dépose aucun cookie, ne contient aucun outil de mesure d'audience et ne fait appel à aucun service tiers : toutes les ressources (code, données, bibliothèque D3.js) sont servies depuis ce dépôt.

## Mises à jour

Le site sera actualisé avec les données 2025 dès leur publication. Les suggestions et corrections sont les bienvenues.

## Auteur

Analyse et conception : **Jules Bourgeois**

## Licence

- **Code et conception graphique** : © 2026 Jules Bourgeois, tous droits réservés.
- **Données** (`data.json`, `lignes.json`, `territoires.json`) : bases dérivées de données ouvertes, diffusées sous licence **ODbL**, comme les données SNCF d'origine.
- **D3.js** (`d3.min.js`) : licence ISC.

Détails dans [LICENSE](LICENSE).
