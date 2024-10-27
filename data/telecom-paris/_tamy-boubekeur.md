# Title: Tamy Boubekeur

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Recherche](https://www.telecom-paris.fr/fr/recherche "Recherche") > [Laboratoires](https://www.telecom-paris.fr/fr/recherche/labos "Laboratoires") > [Laboratoire Traitement et Communication de l’Information (LTCI)](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci "Laboratoire Traitement et Communication de l’Information \(LTCI\)") > [Nos chercheurs](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci/nos-chercheurs "Nos chercheurs") > [Chercheurs en vue](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci/nos-chercheurs/chercheurs-en-vue "Chercheurs en vue") > [Tamy Boubekeur](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci/nos-chercheurs/chercheurs-en-vue/tamy-boubekeur)

[](https://www.telecom-paris.fr/fr/accueil)

# Tamy Boubekeur

Enseignant-chercheur à Télécom Paris depuis 2008 au sein du LTCI, Tamy
Boubekeur est spécialisé dans l’informatique graphique 3D, c’est-à-dire dans
la représentation, conception, et simulation 3D d’objets ou scènes réels ou
imaginaires.

Ses recherches ont pour axes principaux la modélisation géométrique et la
synthèse d’images, en symbiose avec les activités [de l’équipe
IMAGES](https://www.telecom-paris.fr/fr/recherche/laboratoires/laboratoire-
traitement-et-communication-de-linformation-ltci/les-equipes-de-
recherche/image-modelisation-analyse-geometrie-synthese-images) dont il fait
partie. Des domaines très transverses qui font l’originalité du groupe, avec
des applications en imagerie médicale, imagerie radar ou encore pour les jeux
vidéo.

En haut : le rendu de production généré par le moteur Shining d’Ubisoft, avec
un faible taux d’échantillonnage. En bas : l’algorithme BCD reconstruit une
valeur couleur débruitée à partir des statistiques du pixel.

Ainsi, le chercheur et son doctorant Malik Boughida ont récemment mis au point
et dévoilé une méthode pour la synthèse d’image photoréaliste aujourd’hui
intégrée par Ubisoft Motion Picture, pour la production de la série
d’animation « Rabbids Invasion » notamment. Il s’agit d’une technologie en
synthèse d’images pour les processus longs en simulation ; cette technologie
permet de prédire la couleur d’un pixel à partir des premières itérations de
la simulation, remplaçant une grande partie de cette simulation par du
traitement d’image a posteriori. La méthode, dont le code source a été publié
de manière ouverte, est très facile à intégrer ; les moteurs de rendu open-
source Appleseed et LUX Render en sont également utilisateurs. L’article
résumant ce travail de recherche, intitulé, « Bayesian Collaborative Denoising
for Monte Carlo Rendering » a été publié dans la revue Computer Graphics Forum
et présenté à la conférence internationale EGSR 2017. D’autres travaux sur le
même thème ont fait l’objet d’une collaboration avec Dassault Systèmes, pour
ses futurs systèmes de rendus en temps réel. Ces travaux s’inscrivent dans le
projet global de l’équipe sur le thème de la synthèse d’image, qui vise à
développer des méthodes extrêmement rapides de production d’images numériques
à partir de modèles 3D.

Les travaux récents du chercheur se recoupent sur les thèmes du design et de
l’optimisation de formes, qui pourraient être résumés par la question suivante
: comment faire pour représenter ce qui nous entoure avec un nombre réduit de
variables numériques ? Une démarche à contre-pied du Big Data et ses données
massives. La simplification géométrique d’un objet permet ainsi à la fois d’en
réduire la complexité et et d’en faire émerger les structures importantes, ce
qui accroît in fine la rapidité des algorithmes l’utilisant. Ce type de
méthode permet notamment de calculer des structures de contrôle, ou
superstructure, permettant d’interagir rapidement avec des objets complexes
(déformations, simulation physique).

Unsharp masking geometry

En 2017, Tamy Boubekeur et ses collègues se sont vu décerner un Best Paper
Award lors de la conférence SMI (Shape Modeling International) pour l’article
intitulé « Unsharp masking geometry improves 3D prints », co-signé avec
Philipp Herholz, Sebastian Koch, et Marc Alexa, de la TU Berlin, et publié
dans le revue Computer & Graphics. L’article propose un algorithme de
traitement géométrique pour améliorer la perception finale des impressions 3D.
Plus précisément, cet algorithme permet de rehausser à l’avance ce qui risque
d’être perdu à l’impression : à l’écran, la lumière rebondit à 100 % sur toute
la surface de l’objet alors que dans la réalité, le matériau utilisé pour
l’impression absorbe une partie de cette lumière. La technique proposée
compense cette perte en traitant et en modifiant directement la géométrie
d’une forme, pour préserver au mieux ses détails une fois imprimée.

Modèle de navigation « naturelle » LazyNav

En collaboration avec l’Université d’Osaka, le chercheur, avec sa doctorante
Émilie Guy, a également travaillé en 2015 à mettre au point un modèle de
navigation « naturelle » dans un monde virtuel, c’est-à-dire sans périphérique
à manipuler. Le système proposé scanne le corps de l’utilisateur à l’aide
d’une caméra RGB-D et reconstruit un squelette ; la caméra ‘virtuelle’ est
ensuite orientée en fonction d’éléments du corps déterminés comme moins
critiques pour d’autres interactions (ramasser un objet, activer un système),
tels que l’orientation des épaules, et laisse ainsi mains et tête libres pour
d’autres tâches. L’article original a reçu le prix du meilleur article à la
conférence internationale IEEE 3DUI 2015. L’article « Extended LazyNav:
Virtual 3D Ground Navigation for Large Displays and Head-Mounted Displays »,
qui étend ce travail aux casques de réalité virtuelle, a été publié en 2017
dans la revue IEEE Transactions on Visualization and Computer Graphics.

MADVolume Remesher

Ses travaux récents sur la génération de maillages 3D à partir de données
médicales ont été distingués en 2016 d’un Best Paper Award lors de la
conférence Shape Modeling International (SMI), pour l’article « Multi-Material
Adaptive Volume Remesher » co-signé avec Noura Faraj et Jean-Marc Thiery et
publié dans le revue Computer & Graphics. Un objet 3D composé de différents
matériaux peut être représenté par une grille en voxel (pour « volumetric
pixel » en 3D). Les simulations physiques fonctionnent généralement sur des
maillages de haute qualité générés, dans le cas de données médicales, à partir
de grilles en voxels capturées à l’aide par exemple d’IRMs. Le passage de la
grille au maillage est cependant assez difficile et résulte souvent en une
défaillance de qualité et de résolution, ce qui contraint à un remaillage. Les
chercheurs ont proposé un algorithme de remaillage rapide et passant à
l’échelle de grandes masses de données, qui génère sous différentes
résolutions des maillages de haute qualité et préservant des caractéristiques
importantes du maillage d’origine.

[Page personnelle de Tamy Boubekeur](https://perso.telecom-
paristech.fr/boubek/)

