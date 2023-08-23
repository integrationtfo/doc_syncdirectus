# Collections

La table collections contient le container parent qui inclut les séries et les produits.

## Les données

Donnée | Type | Définition
--- | --- | ---
collection_key | integer | L'identifiant primaire (Primary Key) - [!badge text="PK" variant="primary"]
biznumber | string | L'identifiant du produit
title | string | Titre du produit
short_title | string | Titre court
type | string | Type de produit
kind | string | Définition du genre de produit
subkind | string | Définition du sous-genre de produit
category | string | Catégorie à laquelle le produit appartient
images | array | Informations des images associées au produit
all_targets | json | Array contenant l'ensemble des cibles de chaque produit sous la collection
slug_fr | string | Le slug du titre du produit en français
press_fr_title | string | Titre du produit en français
press_fr_short_summary | string | Courte description du produit en français
press_fr_long_summary | string | Longue description du produit en français
slug_en | string | Le slug du titre du produit en anglais
press_en_title | string | Titre du produit en anglais
press_en_short_summary | string | Courte description du produit en anglais
press_en_long_summary | string | Longue description du produit en anglais
created_at | time America/Toronto | Date de mise enligne du produit
updated_at | time America/Toronto | Date de dernière mise à jour du produit
