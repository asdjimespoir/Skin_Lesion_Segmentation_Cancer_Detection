# Segmentation des lésions cutanées et détection du cancer par Deep Learning

## Plan du travail

Le projet consiste en trois grandes parties qui sont reparties comme suit :

1. Tâche 1 : Détection de cancer avec EfficientNetV2
2. Tâche 2 : Détection et segmentation des lésions cutanées avec Mask-RCNN
3. Tâche 3 : Détection et segmentation de lésions cutanées avec YOLO v8

Etant donné les différentes tâches constituant notre projet, nous allons essayer de comprendre les différentes notions qui y sont liées. Pour ce faire deux grandes questions se posent : `Qu'est-ce que la détection d'objets ?` `Qu'est-ce que la segementation d'image ?`



*   `Qu'est-ce que la détection d'objets ?`

  La détection d'objets est un domaine de la vision par ordinateur qui a pour but de localiser et d'identifier des objets spécifiques dans une image ou une vidéo. Il s'agit d'une tâche de reconnaissance d'images dans laquelle le système doit être capable de détecter la présence et l'emplacement des objets dans l'image, ainsi que de les classer en différentes catégories, telles que les voitures, les personnes, les animaux, etc.

  La détection d'objets est largement utilisée dans de nombreuses applications, notamment la reconnaissance de la circulation, la surveillance vidéo, la reconnaissance de la scène, la reconnaissance de la forme, la reconnaissance d'images, etc. Les algorithmes de détection d'objets peuvent être basés sur des techniques telles que les réseaux de neurones convolutionnels, les méthodes basées sur les caractéristiques, les méthodes basées sur les modèles et les méthodes de détection de bord. Les réseaux de neurones convolutionnels, tels que YOLO et Faster R-CNN, sont actuellement considérés comme les méthodes les plus avancées pour la détection d'objets en raison de leur précision et de leur efficacité en termes de temps de traitement.

*   `Qu'est-ce que la segementation d'image ?`

  La segmentation d'image est un domaine de la vision par ordinateur qui consiste à diviser une image en plusieurs régions homogènes, appelées segments, en fonction de certains critères. Chaque segment représente une région d'intérêt distincte de l'image, comme un objet, une personne, un animal, etc.

  La segmentation d'image est un prétraitement important pour de nombreuses tâches en vision par ordinateur, telles que la reconnaissance d'objets, la reconnaissance de la forme, la reconstruction 3D, etc. Les algorithmes de segmentation d'image peuvent être basés sur des techniques telles que les réseaux de neurones, les algorithmes de filtrage, les algorithmes basés sur les modèles, etc. Les réseaux de neurones, tels que U-Net et SegNet, sont actuellement considérés comme les méthodes les plus avancées pour la segmentation d'image en raison de leur capacité à capturer des caractéristiques complexes et à générer des résultats précis.
