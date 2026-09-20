# Sources des données

## 1. Répertoire des seigneuries du Québec (RSQ)

- **Fournisseur :** Centre interuniversitaire d'études québécoises (CIEQ), en collaboration avec l'Université Laval et l'Université de Sherbrooke
- **Site :** https://rsq.cieq.ca/
- **Fichiers :** `raw_data/Seigneuries_en_1725.*` (shapefile)
- **Licence :** CC-BY-NC (Attribution – Pas d'utilisation commerciale)
- **Citation requise :**
  > Laberge, Alain et Benoit Grenier. (2023, mise à jour : 22 avril 2024). "Répertoire des seigneuries du Québec".

## 2. Index des cantons — Greffe de l'arpenteur général du Québec (GAGQ)

- **Fournisseur :** Ministère des Ressources naturelles et des Forêts (MRNF), gouvernement du Québec
- **Fichier :** `raw_data/mrnf_cantons_seigneuires.geojson`
- **Site :** https://appli.foncier.gouv.qc.ca/gagq
- **Licence :** Licence d'utilisation du Greffe de l'arpenteur général (consultation, téléchargement et reproduction autorisés pour usage normal ; revente interdite)
- **Autorisation :** Le ministère a confirmé directement l'autorisation d'utiliser et de publier ces données dans le cadre de ce projet.
- **Citation :**
  > Foncier Québec, Bureau de l'arpenteur général. "Index des cantons". Québec : Ministère de l'Énergie et des Ressources naturelles, 2006.

## Textes législatifs de référence (reconstitution des circonscriptions)

- *Proclamation divisant la province de Bas-Canada en comtés, et en districts électoraux* (7 mai 1792)
- *An Act to make a new and more convenient subdivision of the Province into Counties, for the purpose of effecting a more equal Representation thereof in the Assembly than heretofore* (1829)

## Produits dérivés (dossier `output/`)

Les fichiers `circonscriptions_1792` et `circonscriptions_1829` sont le résultat d'une fusion de ces sources, réalisée par Roxanne Corriveau. Voir `scripts/` pour le code de traitement, et la section Méthodologie du README pour les détails
