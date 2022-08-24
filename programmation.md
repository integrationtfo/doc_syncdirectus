# Programmation

La collection de programmation contient toutes les informations sur l'organisation des expositions sur une chaine.

## Method

```
Get items/:collection?params
```

## Parametres

Paramètre | Obligatoire | Type | Exemple
--- | --- | --- | ---
access_token | Oui | string | xxxxxx
:collection | Oui | string | programmation_tfos, programmation_linears, programmation_idellos


## Resource

Les informations fournies par l'API auront la présentation suivante.

:::code source="./assets/programmation.json" :::

### Resultat

Donnee | Type | Definition
--- | --- | ---
program_key | integer | L'identifiant primaire (Primary Key) pour les programmations [!badge text="PK" variant="primary"]
product_id | integer | L'identifiant permettant de recuperer les informations complètes d'un produit 
being | string | La date et l'heure de début de diffusion
end | string | La date et l'heure de fin de diffusion
version | string | Les versions de la programmation
titre | string | Le titre de la programmation
territories | array | Territoires dans lesquels la programmation sera accepté ou refusé
svod_right | boolean | ...
live | boolean | Informe si l'émission est en directe ou non
advertising | ... | ...
video_id | string | L'identifiant Limelight de la vidéo associée à la programmation
video_duration | string | Durée de la vidéo
video_tcin | string | Début de la vidéo - Format heures, minutes, secondes et frames
video_tcout | string | Fin de la vidéo
video_closed_captions_url | string | Lien url contenant les sous-titrages de la vidéo (format XML)
video_allow_ads | boolean | Si oui ou non la pub peut être ajoutée à la vidéo
video_caption_vtt | string | Lien url contenant le sous titrages de la vidéo (format VTT)
video_start_date | string | Date de début de la vidéo (Unix Timestamp)
video_end_date | string | Date de fin de la vidéo (Unix Timestamp)
subtitles | array | Liste de soustitres
pedagogicalcategories | array | Liste de catégories pédagogiques de la programmation
othermaterials | array | Autres ressources associées à la programmation
nonlinearcategories | array | Liste des catégories (objet json) auxquels la vidéo est associée
images | string | Nom de l'image vitrine de la vidéo
authorizedcountries | array | Liste des pays qui ont le droit de diffusion
status | boolean | Programme est-il toujours actif ou non (champs inutile)
created_at | string | Date de création dans Directus
updated_at | string | Derniere date de mise a jour dans Directus
target | string | l'audience cible
program_duration | integer | Durée du programme (en minutes)
