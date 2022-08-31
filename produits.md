# Produits

## Method

```
Get items/:collection?params
```

## Parametres

Paramètre | Obligatoire | Type | Exemple
--- | --- | --- | ---
access_token | Oui | string | xxxxxx
:collection | Oui | string | tfo_products, linear_products, idello_products
filter | Non | string | filter[product_id][_eq]=xxxxxx

## Resource

Les informations fournies par l'API auront la présentation suivante.

:::code source="./assets/product.json" :::

### Resultat

Donnee | Type | Définition
--- | --- | ---
product_key | integer | L'identifiant primaire (Primary Key) - One to many sur la table de programmation [!badge text="PK" variant="primary"]
biznumber | string | L'identifiant du produit 
title | string | Titre du produit
short_title | string | Titre court
production_year | string | Année de production
duration | time format HH:MM:SS | Durée de lecture du produit
origin_country | string | Pays d'origine
type | string | Type de produit
kind | string | Définition du genre de produit
subkind | string | Définition du sous-genre de produit
category | string | Catégorie à laquelle le produit appartient
target | string | Audience cible du produit
rating | string | Evaluation du produit
versions | string | Version du produit
images | array | Informations des images associées au produit
collection_title | string | Titre de la collection à laquelle appartient le produit
status | boolean | Le produit est-il actif (a ignorer)
created_at | time UTC | Date de mise enligne du produit
updated_at | time UTC | Date de derniere mise à jour du produit
press_fr_title | string | Titre du produit en francais
press_fr_short_summary | string | Courte description du produit en francais
press_fr_long_summary | string | Longue description du produit en francais
press_en_title | string | Titre du produit en anglais
press_en_short_summary | string | Courte description du produit en anglais
press_en_long_summary | string | Longue description du produit en anglais



