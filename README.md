# Cartes des circonscriptions du Bas-Canada

Ce dépôt contient des cartes géospatiales des circonscriptions électorales, cantons et seigneuries du Bas-Canada, produites en fusionnant des données du gouvernement du Québec et du Centre interuniversitaire d'études québécoises (CIEQ).

## Structure du dépôt

- `raw_data/` — données brutes provenant des sources originales (voir SOURCES.md)
- `output/` — cartes finales produites (circonscriptions_1792, circonscriptions_1829)

## Sources et licences

Voir [SOURCES.md](./SOURCES.md) pour le détail des sources de données, leurs licences respectives, et les autorisations obtenues.

## Auteure

Roxanne Corriveau

## Méthodologie

Les cartes de 1792 et de 1829 ont été produites selon une méthode de reconstitution cartographique similaire pour les deux périodes, dans QGIS. L'objectif était de traduire en données spatiales des découpages territoriaux historiques à partir de descriptions textuelles, de cartes historiques et de données géographiques existantes.

Pour chacune des périodes, les unités territoriales disponibles dans les données géographiques ont d'abord été identifiées et sélectionnées en fonction de leur existence et de leur pertinence pour la période étudiée. Les données relatives aux cantons ont notamment été tirées de l'*Index des cantons* du Bureau de l'arpenteur général, tandis que les seigneuries ont été identifiées à partir des données cartographiques du Centre interuniversitaire d'études québécoises (CIEQ).

Les limites des circonscriptions ont ensuite été reconstituées à partir des descriptions territoriales contenues dans les textes législatifs correspondant à chacune des périodes étudiées. Ces descriptions ont été mises en relation avec les limites des cantons et des seigneuries disponibles dans les données géographiques. Une représentation cartographique historique du découpage a également été utilisée comme document de référence afin de contrôler l'interprétation spatiale des descriptions textuelles.

Dans QGIS, les unités territoriales correspondant aux descriptions des circonscriptions ont été sélectionnées puis fusionnées afin de créer de nouvelles entités spatiales représentant les circonscriptions reconstituées. Les nouvelles couches ont ensuite été vérifiées à partir des sources cartographiques et textuelles disponibles et exportées dans des formats permettant leur utilisation dans des analyses SIG ultérieures.

### Reconstitution de 1792

La carte de 1792 a été reconstituée à partir des descriptions contenues dans la *Proclamation divisant la province de Bas-Canada en comtés, et en districts électoraux* (7 mai 1792). Les descriptions des limites des comtés ont servi de référence principale pour déterminer les unités territoriales à regrouper.

### Reconstitution de 1829

La carte de 1829 a été reconstituée à partir des descriptions contenues dans *An Act to make a new and more convenient subdivision of the Province into Counties, for the purpose of effecting a more equal Representation thereof in the Assembly than heretofore*. Les descriptions des limites des comtés ont servi de référence principale pour déterminer les unités territoriales à regrouper.
