# Programmation

La table de programmation contient toutes les informations sur l'organisation des expositions sur une chaine.
Elle indique les dates de droit de diffusion pour chaque produit.

## Les données

Donnee | Type | Definition
--- | --- | ---
program_key | integer | L'identifiant primaire (Primary Key) pour les programmations [!badge text="PK" variant="primary"]
product_id | integer | L'identifiant permettant de recuperer les informations complètes d'un produit
begin | string | La date et l'heure de début de diffusion (America\Toronto)
end | string | La date et l'heure de fin de diffusion (America\Toronto)
version | string | Les versions de la programmation
titre | string | Le titre de la programmation
territories | array | Territoires dans lesquels la programmation sera acceptée ou refusée
svod_right | boolean | Indique le droit svod
live | boolean | Informe si l'émission est en directe ou non
advertising | string | Indique les infos sur les publicités
video_id | string | L'identifiant Limelight de la vidéo associée à la programmation
video_duration | string | Durée de la vidéo en minutes
video_tcin | string | Début de la vidéo - Format heures, minutes, secondes et frames
video_tcout | string | Fin de la vidéo
video_closed_captions_url | string | Lien URL contenant les sous-titrages de la vidéo (format XML)
video_allow_ads | boolean | Indique si la publicité peut être ajoutée à la vidéo
video_caption_vtt | string | Lien URL contenant le sous titrages de la vidéo (format VTT)
video_start_date | string | Date de début de la vidéo (Unix Timestamp)
video_end_date | string | Date de fin de la vidéo (Unix Timestamp)
video_extra | json | Information supplémentaire concerant la vidéo.
subtitles | array | Liste de soustitres
pedagogicalcategories | array | Liste de catégories pédagogiques de la programmation
othermaterials | array | Autres ressources associées à la programmation
nonlinearcategories | array | Liste des catégories (objet json) auxquels la vidéo est associée
images | string | Nom de l'image vitrine de la vidéo
authorizedcountries | array | Liste des pays qui ont le droit de diffusion
status | boolean | Information pour l'équipe TFO (veuillez ignorer ce champ)
target | string | l'audience cible
program_duration | integer | Durée du programme (en minutes)
created_at | time America/Toronto | Date de mise enligne du produit
updated_at | time America/Toronto | Date de dernière mise à jour du produit
