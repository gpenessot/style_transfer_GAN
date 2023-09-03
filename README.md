# Transfert de style avec GAN

## Introduction
La technique de transfert de style neuronal consiste à optimiser deux images - une représentant le contenu et l'autre reflétant le style souhaité (comme une œuvre d'art d'un peintre renommé), afin de les fusionner de manière à ce que l'image résultante conserve le contenu de l'image originale, tout en étant "peinte" dans le style de l'image de référence. 

Cette méthode repose sur l'optimisation de l'image de sortie, alignant ses caractéristiques de contenu sur celles de l'image originale et ses caractéristiques stylistiques sur celles de l'image de référence. Ces caractéristiques sont extraites des images à l'aide d'un réseau convolutif.

Les photographies de portrait ont été générées à l'aide de Stable Diffusion 1.5.