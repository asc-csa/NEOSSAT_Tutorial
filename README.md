<p align="center">
    <img src="https://www.asc-csa.gc.ca/images/satellites/neossat/neossat-ban.jpg" alt="image-text" height="300">
    <br> Crédit d'image | Image credit: <a href="https://www.asc-csa.gc.ca/eng/satellites/neossat.asp">ASC-CSA</a>
</p>

<p align="center">
    <a href="#stars">
        <img alt="Étoiles sur GitHub | GitHub Repo stars" src="https://img.shields.io/github/stars/asc-csa/NEOSSAT_Tutorial">
    </a>
    <a href="#watchers">
        <img alt="Spectateurs sur Github | GitHub watchers" src="https://img.shields.io/github/watchers/asc-csa/NEOSSAT_Tutorial">
    </a>
    <a href="https://github.com/asc-csa/NEOSSAT_Tutorial/commits/main">
        <img alt="Dernier commit sur GitHub | GitHub last commit" src="https://img.shields.io/github/last-commit/asc-csa/NEOSSAT_Tutorial">
    </a>
    <a href="https://github.com/asc-csa/NEOSSAT_Tutorial/graphs/contributors">
        <img alt="Contributeurs sur GitHub | GitHub contributors" src="https://img.shields.io/github/contributors/asc-csa/NEOSSAT_Tutorial">
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=csa_asc">
        <img alt="Suivre sur Twitter | Twitter Follow" src="https://img.shields.io/twitter/follow/csa_asc?style=social">
    </a>
</p>

---

<h3 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h3>

---

<a id="titre-du-projet"></a>
# Extraction de données NEOSSAT - Un tutoriel

> **Description brève :**  
> Ce tutoriel se concentre sur le téléchargement des données NEOSSAT à partir du site Web de l’Agence spatiale canadienne et du Centre canadien de données astronomiques. Les utilisateurs peuvent filtrer les données et visualiser les fichiers .fits de leur choix pour le contexte du défi des applications spatiales.

## À propos

**Extraction de données NEOSSAT - Un tutoriel** est un tutoriel qui se concentre sur le téléchargement et l'analyse des données NEOSSAT. Il couvre :

- Téléchargement de données NEOSSAT depuis les archives de l'ASC et du CCDA
- Filtrage et sélection de données astronomiques selon des critères spécifiques
- Visualisation et analyse de fichiers FITS astronomiques
- Prétraitement des données pour l'analyse d'objets proches de la Terre (NEO)

Un second tutoriel est offert pour démontrer les différentes étapes du prétraitement des données de NEOSSat ainsi que pour effectuer une première analyse des objets proches de la Terre.

*Ce tutoriel est fourni à des fins pédagogiques et expérimentales.*

## Prérequis

- Python 3.9 ou plus récent
- Jupyter Notebook ou Jupyter Lab
- Bibliothèques Python : astropy, numpy, matplotlib, pandas
- Connexion Internet (pour l'accès aux archives NEOSSAT)
- Espace de stockage pour les fichiers FITS

## Démarrage rapide

1. 📦 **Cloner le dépôt**
   ```bash
   git clone https://github.com/asc-csa/NEOSSAT_Tutorial.git
   cd NEOSSAT_Tutorial
   ```
2. 🐍 **Créer un environnement**
   ```bash
   # Avec virtualenv
   python -m venv env
   source env/bin/activate

   # Ou avec conda
   conda create -n neossat_env python=3.9
   conda activate neossat_env
   ```
3. 🚀 **Lancer le tutoriel**
   ```bash
   jupyter notebook
   ```

> **Remarque :** Deux tutoriels sont disponibles - téléchargement/visualisation de données et prétraitement pour l'analyse NEO.

## Astuces & Conseils

- **Archives NEOSSAT :** Les données sont disponibles via l'ASC et le Centre canadien de données astronomiques
- **Fichiers FITS :** Utilisez astropy pour une manipulation efficace des données astronomiques
- **Objets NEO :** NEOSSAT surveille les objets proches de la Terre et les débris spatiaux
- **Filtrage :** Les critères de sélection peuvent être ajustés selon vos besoins d'analyse

## Licence

Ce projet est sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/NEOSSAT_Tutorial/blob/main/LICENSE.txt) pour plus de détails.

---

<h3 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h3>

---

<a id="project-title"></a>
# Extracting NEOSSAT data - A Tutorial

> **Brief description:**  
> This tutorial focuses on downloading the NEOSSAT data from the website of the Canadian Space Agency and Canadian Astronomy Data Center. The users can filter through the data and visualize the .fits files of their choice for the context of the Space Apps challenges.

## About

**Extracting NEOSSAT data - A Tutorial** is a tutorial that focuses on downloading and analyzing NEOSSAT data. It covers:

- Downloading NEOSSAT data from CSA and CADC archives
- Filtering and selecting astronomical data based on specific criteria
- Visualizing and analyzing astronomical FITS files
- Pre-processing data for Near-Earth Object (NEO) analysis

A second tutorial is available to demonstrate different steps in pre-processing of NEOSSat data as well as perform initial analysis on near-earth-objects.

*This tutorial is provided for educational and experimental purposes.*

## Prerequisites

- Python 3.9 or newer
- Jupyter Notebook or Jupyter Lab
- Python libraries: astropy, numpy, matplotlib, pandas
- Internet connection (for NEOSSAT archive access)
- Storage space for FITS files

## Quick Start

1. 📦 **Clone the repo**
   ```bash
   git clone https://github.com/asc-csa/NEOSSAT_Tutorial.git
   cd NEOSSAT_Tutorial
   ```
2. 🐍 **Create environment**
   ```bash
   # Using virtualenv
   python -m venv env
   source env/bin/activate

   # Or using conda
   conda create -n neossat_env python=3.9
   conda activate neossat_env
   ```
3. 🚀 **Run the tutorial**
   ```bash
   jupyter notebook
   ```

> **Note:** Two tutorials are available - data download/visualization and pre-processing for NEO analysis.

## Tips & Tricks

- **NEOSSAT Archives:** Data is available through CSA and Canadian Astronomy Data Centre
- **FITS Files:** Use astropy for efficient manipulation of astronomical data
- **NEO Objects:** NEOSSAT monitors Near-Earth Objects and space debris
- **Filtering:** Selection criteria can be adjusted based on your analysis needs

## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/NEOSSAT_Tutorial/blob/main/LICENSE.txt) file for details.
