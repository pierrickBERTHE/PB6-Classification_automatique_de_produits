# <span style='background:blue'>Contexte</span>

L'entreprise **"Flipkart"** est une entreprise indienne qui souhaite lancer une marketplace e-commerce. Sur cette place de marché anglophone, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.

Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible, et dans l'optique d'un passage à l'échelle, il devient nécessaire **d'automatiser l'attribution de la catégorie** d'un article (actuellement effectuée manuellement par les vendeurs, donc peu fiable).


# <span style='background:blue'>Missions</span>

1/ Faire une **étude de la faisabilité d’un moteur de classification** d’article basé sur une **description** pour automatiser l’attribution de catégorie de l’article (NLP). 

2/ Faire une **étude de la faisabilité d’un moteur de classification** d’article basé sur une **image** pour automatiser l’attribution de catégorie de l’article (Computer Vision). 

3/ **Réaliser une classification supervisée** à partir des images par la mise en place d’une data augmentation afin d’optimiser le modèle. 

4/ **Extraire les 10 premiers produits à base de « champagne »** issus de l’API fournie dans un fichier “.csv”, contenant pour chaque produit les données suivantes : foodId, label, category, foodContentsLabel, image.


# <span style='background:blue'>Dataset</span>

Source : Non précisé<br>


# <span style='background:blue'>Fichiers du dépôt</span>

- **berthe_pierrick_1_notebook_faisabilite_feature_extraction_texte_122023.ipynb** : Notebook de faisaibilité de la classification des articles à partir de la description des articles en NLP (Feature extraction, deep learning : Word2Vec, BERT, USE)

- **berthe_pierrick_2_notebook_faisabilite_feature_extraction_image_122023.ipynb** : Notebook de faisaibilité de la classification des articles à partir des images des articles en Computer Vision (Feature extraction : SIFT, deep learning : VGG16)

- **berthe_pierrick_3_notebook_classification_122023.ipynb** : Notebook de classification des articles à partir des images des articles en Computer Vision (Deep learning : MLP, CNN, VGG16 avec data augmentation)

- **berthe_pierrick_4_script_python_122023.py** : Script Python pour extraire les 10 premiers produits à base de "champagne" issus de l'API

- **Berthe_Pierrick_5_export_122023.csv** : export des 10 premiers produits à base de "champagne" issus de l'API

- **Berthe_Pierrick_6_presentation_122023.pdf** : Présentation des résultats


# <span style='background:blue'>Auteur</span>

Pierrick BERTHE<br>
Décembre 2023
