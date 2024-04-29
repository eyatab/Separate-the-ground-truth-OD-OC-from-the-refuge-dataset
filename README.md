# Separate-the-ground-truth-OD-OC-from-the-refuge-dataset   
Ce pré-traitement consiste à modifier les valeurs des pixels de manière
à séparer les masques OD OC combinés de Refuge en deux masques : un pour le disque optique
et un pour la cupule optique.   
Afin de réaliser cette séparation, les pixels noirs, qui représentaient
la cupule optique, ont été transformés en pixels gris pour former le masque du disque optique,et
vice versa pour générer le masque de la cupule optique.
![image_2024-04-29_130359853](https://github.com/eyatab/Separate-the-ground-truth-OD-OC-from-the-refuge-dataset/assets/79045818/dd3c4b1e-21e6-4545-8301-a7e367bcc21c)
    
Dataset : https://www.kaggle.com/datasets/victorlemosml/refuge2
