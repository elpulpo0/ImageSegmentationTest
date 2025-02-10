# ImageSegmentationTest

## Enoncé

Projet 4 : Segmentation d'images et résumé
Énoncé :
Créez une application qui prend une image en entrée, effectue la segmentation de l'image, génère une description textuelle pour chaque segment, et produit un résumé textuel de l'image entière.
Détails :
Utilisez un modèle de segmentation d'images pré-entraîné de Hugging Face (ex: facebook/detr-resnet-50-panoptic).
Utilisez un modèle "image to text" pré-entraîné de Hugging Face (ex: nlpconnect/vit-gpt2-image-captioning).
Utilisez un modèle de résumé de texte pré-entraîné de Hugging Face (ex: facebook/bart-large-cnn).
Description détaillée :
L'utilisateur pourra charger une image via l'interface Gradio. L'application effectuera la segmentation de l'image et affichera les différents segments. Pour chaque segment, une description textuelle sera générée. Enfin, un résumé textuel de l'image entière sera produit et affiché à l'utilisateur.
Bibliothèques :
transformers
torch
gradio


## Installation

**Create Virtual environnement**

`python -m venv .venv`

**Connect to the venv**

- mac/linux
  `source .venv/bin/activate.fish`
- windows
  `.venv/Scripts/activate` or `.venv/Scripts/activate.ps1`
- bash(windows)
  `source .venv/Scripts/activate`

**Update pip**

`python.exe -m pip install --upgrade pip`

**Install Torch**

Choose the version that suit your environment.

**Install the other librairies**

`pip install -r requirements.txt`

## Exécution

SOON