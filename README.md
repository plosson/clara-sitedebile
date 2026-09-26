# Blue Lions U19 Filles — Résultats

Tableau de résultats live pour les **Blue Lions U19 Filles** (club belge Blue Lions Tervuren — *pas* le Blue Lions FHC de Pennsylvanie).

**Live :** https://clara.sitedebile.fr

## Contenu

- **U19G-1** — Nationale 3 A (saison 2026-2027)
- **U19G-2** — Régionale 2 F
- Prochains matchs, résultats récents, classement
- Snapshot JSON embarqué + rafraîchissement client via l’API publique Sportlink de hockey.be (CORS autorisé pour ce domaine)

## Sources

- https://hockey.be/fr/competition/calendrier-resultats-et-classements/
- https://hockey.be/wp-json/sportlink-api/cached (program / results / standing)
- Club : https://www.bluelions.be/ — Sportlink club id `CC6VK53`

## Données

Fichier snapshot : `data/blue-lions-u19g.json`  
Les scores ne sont jamais inventés. En cas d’échec API, le snapshot + horodatage « Dernière mise à jour » restent affichés.

## Déploiement (SiteIO)

```bash
siteio sites deploy /workspace/clara-site -n clara
```

## Stack

HTML/CSS/JS statique. Hébergé via SiteIO sur sitedebile.fr.
