# Malaria-detection (French version)
Malaria detection using a customized CNN model

# Introduction 
La malaria (paludisme) est une maladie qui peut être mortelle, elle est causée par des parasites qui sont transmis par des moustiques infectés de type Anopheles. Cette maladie est présente principalement dans les régions tropicales d’Afrique et d’Asie du Sud-est, mais on peut la retrouver aussi dans de très nombreux pays tels le Mexique, l'Amérique Centrale, l'Amérique du Sud, le Moyen-Orient, etc. La détection de la présence de la maladie dans les cellules sanguines (globules rouges) se fait à travers un examen au microscope et par des techniques de diagnostic sanguin assurées par une expertise humaine.

# Problématique
La méthode standard la plus utilisée actuellement pour le diagnostic de la Malaria est celle de la microscopie optique des frottis sanguins. Des chercheurs du centre national des communications biomédicales de Lister Hill (LHNCBC), essaient de créer une application mobile capable de classer et de compter les cellules sanguines parasitées, tout ça à partir des images de cellules collectées provenant de 150 patients infectés par la malaria et de 50 patients en bonne santé, et ce dans le but de diagnostiquer rapidement et efficacement le patient dans des zones aux ressources très limitées. Dans ce contexte, plusieurs questions se posent à savoir:
Est-t'il possible d’élaborer un système capable de classifier de telles images en se basant sur une architecture de réseau de neurones convolutif simple?
Avec une telle architecture, peut-on avoir une précision et un taux de rappel assez élevé avec un jeu de donnée d'entraînement de 2000 exemples ?
Lors du déploiement de la solution, peut-on obtenir un système optimal en termes de temps d’exécution?
