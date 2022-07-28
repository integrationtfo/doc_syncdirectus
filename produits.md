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