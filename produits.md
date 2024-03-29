# Produits

La table de produit contient les éléments concernant chaque produit. Il est impératif de valider sa diffusion à partir de la table de programmation.

## Les données

Donnée | Type | Définition
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
target | string | Le public visé du produit
rating | string | Evaluation du produit
versions | string | Version du produit
images | array | Informations des images associées au produit
serie_key | string | L'identifiant primaire (Primary Key) de la séerie à laquelle appartient le produit
collection_title | string | Titre de la collection à laquelle appartient le produit
collection_key | string | L'identifiant primaire (Primary Key) de la collection à laquelle appartient le produit
collection_biznumber | string | Identifiant Louise de la collection à laquelle appartient le produit
collection_info | string | Information concernant la collection du produit
status | boolean | Information pour l'équipe TFO (veuillez ignorer ce champ)
slug_fr | string | Le slug du titre du produit en français
press_fr_title | string | Titre du produit en français
press_fr_short_summary | string | Courte description du produit en français
press_fr_long_summary | string | Longue description du produit en français
slug_en | string | Le slug du titre du produit en anglais
press_en_title | string | Titre du produit en anglais
press_en_short_summary | string | Courte description du produit en anglais
press_en_long_summary | string | Longue description du produit en anglais
casting | json | Liste du casting du produit
linked_products | json | Liste des produits liés
keywords | json | Liste des mots clés pour le produit
is_audio | boolean | Indique si le produit est un audio. Si oui, le champ audio_link est rempli
audio_link | string | Le lien pour récupérer le fichier mp3
created_at | time America/Toronto | Date de mise enligne du produit
updated_at | time America/Toronto | Date de dernière mise à jour du produit
