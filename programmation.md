# Programmation

La collection de programmation contient toutes les informations sur l'organisation des programs sur une chaine.

## Method

```
Get items/:collection?params
```

## Parametres

Parametre | Obligatoire | Type | Exemple
--- | --- | --- | ---
access_token | Oui | string | xxxxxx
:collection | Oui | string | programmation_tfos, programmation_linears, programmation_idellos


## Resource

Les informations fournis par l'API auront la presentation suivante.

:::code source="./assets/programmation.json" :::

### Resultat

Donnee | Type | Definition
--- | --- | ---
program_id | integer | L'identifiant permettant d'identifier le programme dans Mogador
product_id | integer | L'identifiant permettant de recuperer les informations completes du produit dans Mogador
being | string | La date et l'heure de debut de diffusion
end | string | La date et l'heure de fin de diffusion
version | string | Version du programme
titre | string | Le titre du produit
territories | array | Territoires dans lesquels le programme sera visible
svod_right | boolean | ...
live | boolean | Informe si l'emission est en directe ou non
advertising | ... | ...
video_id | string | L'identifiant Limelight de la video
video_duration | string | Duree de la video
video_tcin | string | ...
video_tcout | string | ...
video_closed_captions_url | string | Lien url contenant les sous-titrages de la video (format XML)
video_allow_ads | boolean | Si oui ou non la pub peut etre ajoute a la video
video_caption_vtt | string | Lien url contenant la video transcription de la video (format VTT)
video_start_date | string | Date de debut du programme (Unix Timestamp)
video_end_date | string | Date de fin du programme (Unix Timestamp)
subtitles | array | Liste de soustitres
pedagogicalcategories | array | Liste de Categories pedagogiques du programme
othermaterials | array | Autres ressources associes au programme
nonlinearcategories | array | Liste des categories (objet json) auxquels la video a est associee
images | string | Nom de l'image vitrine de la video
authorizedcountries | array | Liste des pays qui ont le droit de diffusion
status | boolean | Programme est-il toujours actif ou non (champs inutile)
created_at | string | Date de creation du programme
updated_at | string | Derniere date de mise a jour du programme
target | string | l'audience cible
program_duration | integer | Duree du programme (en minutes)
