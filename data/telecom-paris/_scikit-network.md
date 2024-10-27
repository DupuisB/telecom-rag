# Title: scikit-network

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Recherche](https://www.telecom-paris.fr/fr/recherche "Recherche") > [Laboratoires](https://www.telecom-paris.fr/fr/recherche/labos "Laboratoires") > [Laboratoire Traitement et Communication de l’Information (LTCI)](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci "Laboratoire Traitement et Communication de l’Information \(LTCI\)") > [Logiciels libres et innovation](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci/logiciels-libres "Logiciels libres et innovation") > [scikit-network](https://www.telecom-paris.fr/fr/recherche/labos/traitement-information-ltci/logiciels-libres/scikit-network)

[](https://www.telecom-paris.fr/fr/accueil)

# scikit-network

Analyse de grands graphes en Python.  
Licence : BSD.  
Contributeurs : Thomas Bonald et al.  
Dernière mise à jour : 30 avril 2020.  
[Site Web](https://scikit-network.readthedocs.io)

Scikit-network est une librairie Python pour l’analyse de graphes de grande
taille comme les réseaux sociaux, les graphes du Web et les données
relationnelles, développée depuis mai 2018 à Télécom Paris.

La libraire offre des algorithmes de l’état de l’art pour traiter ces graphes,
en comprendre la structure, en extraire les principaux clusters et les noeuds
les plus représentatifs. Elle embarque également des outils de visualisation
permettant d’exporter des images vectorielles de graphes, au format SVG.

Le projet scikit-network est guidé par deux exigences, souvent contradictoires
en pratique : ergonomie et performance. Côté ergonomie, la librairie
s’installe en une ligne de commande via le gestionnaire de paquets pip, et
repose sur la même API que scikit-learn, librairie Python de référence en
machine learning. Côté performance, le code utilise l’efficacité des
multiplications matrice-vecteur de SciPy, du code compilé reposant sur le
langage Cython et du calcul parallèle. Le résultat est une librairie à la fois
facile d’usage et performante sur de très grands graphes, ce qui la démarque
de ses principaux concurrents (NetworkX, graph-tool et iGraph).

Les applications de scikit-network sont nombreuses : recommandation de
contenus, classification automatique de documents, constitution de cohortes
dans le domaine médical, etc. Les graphes associés (ici respectivement entre
utilisateurs et contenus, documents et mots, patients et code médicaux)
peuvent contenir des milliers voire des millions de noeuds. Quelques lignes de
code suffisent à en comprendre la structure et en extraire les informations
pertinentes.

La librairie scikit-network est développée à Télécom Paris au sein de
l’[équipe DIG](https://www.telecom-
paris.fr/fr/recherche/laboratoires/laboratoire-traitement-et-communication-de-
linformation-ltci/les-equipes-de-recherche/data-intelligence-and-graphs-dig)
par le Professeur [Thomas Bonald](https://www.telecom-paris.fr/thomas-bonald)
et ses doctorants Nathan de Lara et Quentin Lutz. La documentation inclut des
tutoriels permettant de comprendre rapidement les principaux algorithmes et
leur application. Suivant la politique open source de l’école, cette librairie
Python est dorénavant utilisée en enseignement, à la fois en formation
initiale et en formation continue.

[Site de scikit-network](https://scikit-network.readthedocs.io "Site de
scikit-network")

