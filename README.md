# Interface-graphique-avec-python

Ce projet fait partie d’un travail de groupe sur les initiatives écologiques à Strasbourg.
**Moi, je me suis occupée de l’interface graphique** : une page web pour faire des recherches, jouer à un quiz carbone et explorer une carte interactive.

## Fonctionnalités principales

* Recherche d'informations écologiques par mots-clés.
* Jeu interactif sur l'impact carbone des loisirs.
* Carte des lieux écologiques à Strasbourg.

## Technologies utilisées

* Python
* Gradio (pour l'interface web)
* Plotly (pour la carte)
* JSON (pour les données et la configuration)
* Collections.defaultdict

## Installation et utilisation

Pour que l'application fonctionne, les deux fichiers JSON suivants doivent être présents dans le même répertoire que le code :
* CleanAndStrutured.json
* keywords_config.json

L'exécution du script `Interface_Graphique.ipynb` générera une URL Gradio. Ce lien est temporaire (environ une semaine) et l'application ne sera accessible que si le programme est en cours d'exécution.

## Structure du projet

Le code est organisé de la manière suivante :

* **Première partie :** Importation et aperçu du fichier JSON de données.
* **Deuxième partie :** Système de conversation par mots-clés (configuration dans `keywords_config.json`).
* **Troisième partie :** Jeu interactif du Budget Vert.
* **Quatrième Partie :** Création et affichage d'une carte interactive.
* **Cinquième partie :** Création de l'interface web avec des onglets (Gradio).

## Défis rencontrés

* Nécessité de reformater le fichier JSON de données pour extraire les informations utiles.
* Utilisation d'outils d'IA (Copilot/GPT-4) pour aider à structurer le JSON souhaité.

## Apercu
![Capture d'écran 2025-04-25 004824](https://github.com/user-attachments/assets/13d571b4-df2c-4671-bc2a-3960e6d3f93c)
![Capture d'écran 2025-04-25 010042](https://github.com/user-attachments/assets/f197c380-d80e-4d47-b691-768266dab315)
![Capture d'écran 2025-04-25 002812](https://github.com/user-attachments/assets/be4c2716-f410-4f71-9228-2f444d2fc4c3)

## Auteur
BALLOGOU Essi Carole Claudia
