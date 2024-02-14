English is following.  
  
# Modèles  
Ce dépôt vise à documenter les modèles développés dans le cadre de l'initiative [Archétype QC](https://github.com/Archetype-QC). Les modèles déposés dans ce dépôt sont organisés selon la structure suivante:  
- [Building-Prototypes](https://github.com/Archetype-QC/models/tree/main/Building-Prototypes): ce dossier est composé de modèles de bâtiments typiques résidentiels, commerciaux et institutionnels;  
  - [Residential](https://github.com/Archetype-QC/models/tree/main/Building-Prototypes/Residential): ce dossier est composé de modèles de bâtiments typiques résidentiels (maisons unifamiliales détachées, multi-logements, etc.);  
  - Commercial-Institutional (pas encore mis en oeuvre): ce dossier est composé de modèles de bâtiments typiques commerciaux ou institutionnels (écoles, immeubles à bureaux, restaurants, hotels, etc.);  
  - Note: pour chaque modèle répertorié dans ce dossier, 1 dossier comprenant 4 fichiers est créé. Les 4 fichiers sont demandés pour documenter au mieux le modèle et sont:  
    - Le fichier .osm du modèle OpenStudio du bâtiment;  
    - Le rapport .html généré par EnergyPlus durant la simulation et permettant de donner les caractéristiques du modèle;  
    - Le fichier .dxf donnant la géométrie du bâtiment et généré par l'application EPDraw venant avec EnergyPlus;  
    - Un rapport descriptif du modèle écrit par le(s) développeur(s) du modèle (en format pdf, markdown ou autres).   
- Building-Models-Specific (pas encore mis en oeuvre): ce dossier sera composé de modèles qui auront été développés pour des applications spécifiques, par exemple pour du contrôle ou des aspects reliés à l'occupation;  
- Complementary-Models (pas encore mis en oeuvre): ce dossier sera composé de modèles complémentaires aux modèles de bâtiments, par exemple des modèles de nouveaux équipements ou des modèles d'occupation.     
  
--------------------------------------------------------------------------------
# Models
The purpose of this repository is to document the models developed in the initiative [Archetype QC](https://github.com/Archetype-QC).
Repository of models describing the energy use in the building sector in QC  

Structure:  
- Building prototypes (typical building models)  
  - Residential
    - Folder for building 1 (including 4 files: OSM model, PDF report, EnergyPlus HTML report and DXF file)
    - ...
    - Folder for building x (including 4 files: OSM model, PDF report, EnergyPlus HTML report and DXF file)
  - Commercial-Institutional
    - Folder for building 1 (including 4 files: OSM model, PDF report, EnergyPlus HTML report and DXF file)
    - ...
    - Folder for building x (including 4 files: OSM model, PDF report, EnergyPlus HTML report and DXF file)
- Building models for specific applications
- Equipment models
- Occupancy models
- ...
- README.md
- LICENSE

Test
