# Series

La table de series contient l'ensembles des séries associées aux produits. Le primary key de la série spermettra de retrouver les produits liés.

## Les données

Donnée | Type | Définition
--- | --- | ---
serie_key | integer | L'identifiant primaire (Primary Key) - [!badge text="PK" variant="primary"]
biznumber | string | L'identifiant du produit
title | string | Titre du produit
short_title | string | Titre court
production_year | string | Année de production
distributor | string | Nom du distibuteur
url | string | Nom du distibuteur
origin_country | string | Pays d'origine
type | string | Type de produit
kind | string | Définition du genre de produit
subkind | string | Définition du sous-genre de produit
category | string | Catégorie à laquelle le produit appartient
target | string | La cible au niveau de la version de la série
rating | string | Evaluation du produit
versions | string | Version du produit
images | array | Informations des images associées au produit
collection_title | string | Titre de la collection à laquelle appartient le produit
collection_key | string | L'identifiant primaire (Primary Key) de la collection à laquelle appartient le produit
collection_biznumber | string | Identifiant Louise de la collection à laquelle appartient le produit
slug_fr | string | Le slug du titre du produit en français
press_fr_title | string | Titre du produit en français
press_fr_short_summary | string | Courte description du produit en français
press_fr_long_summary | string | Longue description du produit en français
slug_en | string | Le slug du titre du produit en anglais
press_en_title | string | Titre du produit en anglais
press_en_short_summary | string | Courte description du produit en anglais
press_en_long_summary | string | Longue description du produit en anglais
casting | json | Liste du casting du produit
created_at | time America/Toronto | Date de mise enligne du produit
updated_at | time America/Toronto | Date de dernière mise à jour du produit
