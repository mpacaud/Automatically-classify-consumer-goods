# Automatically classify consumer goods

## Issues addressed by the project

The company "Place de marché" wants to launch an e-commerce marketplace. Currently, sellers offer items by posting a photo and a description. The category of an item is entered manually by the seller and, for the time being, the volume of products offered on the platform remains low. In order to make the user experience for sellers and buyers as simple and seamless as possible, and with a view to scaling up to a larger volume of items, it has become necessary to automate this task.

## Objectives

In order to meet our requirements, this project will be carried out in 3 stages: 

	1. Firstly, we will study the feasibility of an article classification engine based on images and their associated text descriptions.

	2. Then, if the results of the study prove positive for the creation of a classification engine based on product description images, a more in-depth study will be carried out, aimed at comparing different techniques and models for extracting features from images.

	3. Finally, with the aim of expanding the platform's range of fine food products, we would like to test the collection of champagne-based products via a RapidAPI API by extracting the first 10 products exported in a .csv file, containing the following data: foodId, label, category, foodContentsLabel, and image for each product.

## Folder tree

- Root: Notebooks, read me.
- Exports: Dataset built after EDA and feature engineering, bag-of-visual-words (BoVW) of each images and saved models.


#
#


# Classer automatiquement des biens de consommation

## Problématique

L’entreprise « Place de marché » souhaite lancer une marketplace e-commerce. Actuellement, les vendeurs y proposent des articles en postant une photo et une description. La catégorie d'un article est entrée manuellement par celui qui le met en vente et, pour l’heure, le volume de produits proposés sur la plateforme demeure faible. Dans le but de rendre l’expérience utilisateur des vendeurs et des acheteurs la plus simple et la plus fluide possible, ainsi que dans l'optique d'un passage à l'échelle sur un volume d’articles plus important, il devient nécessaire d'automatiser cette tâche.

## Objectifs

Pour répondre à notre problématique, ce projet se déroule en 3 temps : 

	1. Tout d’abord, nous allons étudier la faisabilité d’un moteur de classification d’articles basé sur les images et les descriptions textuelles qui leur sont associées.

	2. Ensuite, si le résultat de l’étude s’avère positif pour la création d’un moteur de classification basé sur les images de description des produits, une étude plus approfondie, visant à comparer différentes techniques et modèles pour extraire les features des images, sera réalisée.

	3. Enfin, dans le but d’élargir la gamme de produits de la plateforme dans l’épicerie fine, il est souhaité de tester la collecte de produits à base de « champagne » via une API RapidAPI en extrayant les 10 premiers produits exportés dans un fichier « .csv », contenant les données suivantes : foodId, label, category, foodContentsLabel, et image pour chaque produit.

## Arborescence de dossiers

- Racine : Notebooks, read me.
- Exports : Dataset construit après EDA et feature engineering, bag-of-visual-words (BoVW) pour chaque image et modèles sauvegardés.