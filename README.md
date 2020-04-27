# Malaria-detection (French version)
Malaria detection using a customized CNN model

# Introduction 
La malaria (paludisme) est une maladie qui peut être mortelle, elle est causée par des parasites qui sont transmis par des moustiques infectés de type Anopheles. Cette maladie est présente principalement dans les régions tropicales d’Afrique et d’Asie du Sud-est, mais on peut la retrouver aussi dans de très nombreux pays tels le Mexique, l'Amérique Centrale, l'Amérique du Sud, le Moyen-Orient, etc. La détection de la présence de la maladie dans les cellules sanguines (globules rouges) se fait à travers un examen au microscope et par des techniques de diagnostic sanguin assurées par une expertise humaine.

# Problématique
La méthode standard la plus utilisée actuellement pour le diagnostic de la Malaria est celle de la microscopie optique des frottis sanguins. Des chercheurs du centre national des communications biomédicales de Lister Hill (LHNCBC), essaient de créer une application mobile capable de classer et de compter les cellules sanguines parasitées, tout ça à partir des images de cellules collectées provenant de 150 patients infectés par la malaria et de 50 patients en bonne santé, et ce dans le but de diagnostiquer rapidement et efficacement le patient dans des zones aux ressources très limitées. Dans ce contexte, plusieurs questions se posent à savoir:
Est-t'il possible d’élaborer un système capable de classifier de telles images en se basant sur une architecture de réseau de neurones convolutif simple?
Avec une telle architecture, peut-on avoir une précision et un taux de rappel assez élevé avec un jeu de donnée d'entraînement de 2000 exemples ?
Lors du déploiement de la solution, peut-on obtenir un système optimal en termes de temps d’exécution?

# Données : 
Les données que nous avons à disposition sont les images des cellules sanguines qui ont été collectées et photographiées à
A.
l'hôpital du Chittagong Medical College au Bangladesh. Ces images ont été étiquetées par un expert de l'unité de recherche “Mahidol-Oxford Tropical Medicine” de Bangkok, en Thaïlande. Au total, 28 558 images de cellules sanguines étiquetées en deux classes égales à savoir : 14 279 cellules saines et 14 279 cellules parasitées. Dans notre cas, l’ensemble des données que nous avons utilisé pour le modèle de classification contient 2 000 exemples divisés également en deux : 1 000 images de cellules labélisées « Uninfected » et 1 000 images de cellules labélisées « parasitized ». Voici un échantillon de deux images étiquetées respectivement “Uninfected” et “Paratized” : 
Le format des images utilisées est le “Portable Network Graphics” ( PNG ). Les dimensions de ces dernières sont fixées à 128 pixels en hauteur et 128 pixels en largeur.

Les données dont disponibles sur : https://lhncbc.nlm.nih.gov/publication/pub9932

Voir le fichier Jupyter notebook ci-joint pour l'implémentation du modèle.

# Références :
[1] Sivaramakrishnan Rajaraman , Sameer K. Antani, Mahdieh Poostchi, Kamolrat Silamut, Md. A. Hossain, Richard J. Maude, Stefan Jaeger et George R. Thoma, publié le 16 avril 2018, PubMed 29682411, PeerJ, Pre-trained convolutional neural networks as feature extractors toward improved malaria parasite detection in thin blood smear images, https://peerj.com/articles/4568/ , consulté le 28 juin 2019.

[2] Stefan Jaeger, Hang Yu, Sameer Antani, Sivaramakrishnan Rajaraman, Feng Yang, Rick Fairhurst, NIH : National Institutes of Health, U.S. National Library of Medicine, Lister Hill National Center for Biomedical Communications, Communications Engineering Branch, Malaria Screener, https://ceb.nlm.nih.gov/projects/malariascreener/?fbclid=IwA R0hfqCIYexuINO16f4nVods7oCm8n-trJUobtTToB4e2-rgjrAz Yfqa2Q8  ,consulté le 22 juin 2019.

[3]  Coursera: Convolutional Neural Networks, Andrew Ng, https://fr.coursera.org/learn/convolutional-neural-networks?s pecialization=deep-learning , consulté le 04 juin 2019.

[4]  Passeport Santé,Le paludisme (malaria), https://www.passeportsante.net/fr/Maux/Problemes/Fiche.asp x?doc=paludisme_pm&fbclid=IwAR3eLD6krroHpewBD-Qh m6m4Q5lK1xl0bIQKu9J_gpwHaFtOyJlBySaRWr0,  consulté le 25 juin 2019.
SOURCE DE DONNÉES :  L'ensemble des données utilisées lors de la présente étude est disponible sur : https://ceb.nlm.nih.gov/repositories/malaria-datasets/

Copyright : @adnanebechri

Contact : adnanebechri1@gmail.com

