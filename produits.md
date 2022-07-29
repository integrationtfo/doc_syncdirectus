# Produits

## Method

```
Get items/:collection?params
```

## Parametres

Parametre | Obligatoire | Type | Exemple
--- | --- | --- | ---
access_token | Oui | string | xxxxxx
:collection | Oui | string | tfo_products, linear_products, idello_products
filter | Non | string | filter[product_id][_eq]=xxxxxx

## Resource

Les informations fournis par l'API auront la presentation suivante.

:::code source="./assets/product.json" :::

### Resultat

Donnee | Type | Definition
--- | --- | ---
product_key | integer | Cle relationnelle pour la connexion de la base de donnees
biznumber | string | L'identifiant du produit
title | string | Titre du produit
short_title | string | Titre court
production_year | string | Annee de production
duration | ... | Duree de lecture du produit
origin_country | string | Pays d'origine
type | string | Type de produit
kind | string | ...
subkind | string | ...
category | ... | ...
target | string | Audience cible du produit
rating | string | Evaluation du produit
versions | string | Version du produit
images | array | Informations des images associes au produit
collection_title | string | Titre de la collection a laquelle appartient le produit
status | boolean | Le produit est-il actif (a ignorer)
created_at | time UTC | Date de mise enligne du produit
updated_at | time UTC | Date de derniere mise a jour du produit
press_fr_title | string | Titre du produit en francais
press_fr_short_summary | string | Courte description du produit en francais
press_fr_long_summary | string | Longue description du produit en francais
press_en_title | string | Titre du produit en anglais
press_en_short_summary | string | Courte description du produit en anglais
press_en_long_summary | string | Longue description du produit en anglais