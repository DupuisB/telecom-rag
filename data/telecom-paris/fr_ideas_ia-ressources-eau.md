# Title: Ideas - Comment l’IA peut-elle contribuer à mieux gérer nos ressources en eau ?

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Ideas](https://www.telecom-paris.fr/fr/ideas "Ideas") > [Comment l’IA peut contribuer à mieux gérer nos ressources en eau](https://www.telecom-paris.fr/fr/ideas/ia-ressources-eau)

[](https://www.telecom-paris.fr/fr/accueil)

# Télécom Paris Ideas  
Comment l’IA peut contribuer à mieux gérer nos ressources en eau

## Comment l’IA peut-elle contribuer à mieux gérer nos ressources en eau ?  

[Florence Tupin](https://www.telecom-paris.fr/florence-tupin), professeure à
Télécom Paris, déc. 2023.

Nous cherchons à comprendre comment les algorithmes peuvent se mettre au
service des enjeux de la transition climatique, en l’occurrence la mesure de
l’hydrométrie de la planète.

Pour en parler, je reçois Florence Tupin enseignante-chercheuse à Télécom
Paris et depuis peu responsable du département Images, Données, Signal.

Propos recueillis par Isabelle Mauriac

## Podcast

Retrouvez cette interview en format audio dans le cadre des [podcasts Télécom
Paris Ideas](https://podcast.ausha.co/telecom-paris-ideas) :

Podcast Michel Desnoues, Télécom Paris

## Entretien

— Florence, vous développez des méthodes de traitement et d’analyse d’images
et vous vous êtes peu à peu spécialisée dans le domaine de l’imagerie de
télédétection. Vous travaillez sur le traitement des images en intelligence
artificielle, notamment pour améliorer la qualité et donc l’exploitation des
données acquises par les satellites. En quoi cela consiste-t-il précisément ?

Notre rôle est de développer des méthodes pour améliorer les données, des
images en ce qui nous concerne, ou d’extraire de l’information à partir de ces
données.

  * 
Nous proposons de nouveaux algorithmes qui permettent de combiner à la fois
une modélisation mathématique du problème, l’amélioration d’images ou
d’extraction d’informations, et qui permettent en même temps d’intégrer des
connaissances sur la physique d’acquisition des images d’une part, et d’autre
part d’intégrer aussi des connaissances sur le domaine applicatif.

C’est-à-dire globalement des contraintes, par exemple sur les résultats qu’on
va essayer d’obtenir. Pour résumer, nous faisons des maths, et utilisons la
physique du système d’acquisition et des connaissances expertes sur le domaine
d’application.

— Cela fait beaucoup de données de nature différentes donc beaucoup de
compétences à mobiliser dans le traitement de ces données, j’imagine ?

On peut dire que le traitement d’image est un domaine pluridisciplinaire,
puisqu’au cœur de cette discipline, on trouve les mathématiques appliquées,
avec en particulier, à l’heure actuelle, la science des données,mais aussi
l’informatique et également des connaissances physiques sur le système
d’acquisition. C’est un peu la spécificité du traiteur d’image par rapport à
un traiteur de données qui va être éventuellement agnostique par rapport à la
provenance des données et la façon dont elles ont été acquises. En image, nous
allons avoir des connaissances sur le capteur, sur le système d’acquisition
qui permet d’enregistrer les données. Puis on va essayer, autant que possible,
d’intégrer des connaissances sur le type d’application pour lequel on essaie
d’extraire des informations. Donc, si on fait de l’imagerie médicale, on va
introduire des connaissances sur le corps humain. Si on fait de la
télédétection, on va introduire des connaissances sur la cartographie, par
exemple.

— Quand vous parlez d’améliorer les données acquises, cela veut dire qu’elles
ne sont pas de très bonne qualité au départ et qu’il y a donc un enjeu
d’amélioration de leur qualité ?

Il peut y avoir différents enjeux par rapport à la qualité des données… on
peut améliorer des données, par exemple pour essayer de réduire le temps
d’acquisition. En imagerie médicale, on peut vouloir que le patient reste le
moins longtemps dans le système d’acquisition ou qu’il reçoive un faible
niveau de radiations.. On va donc acquérir des données de moins bonne qualité
pour préserver le patient, mais ensuite les traitements, l’intelligence qu’on
va mettre dans notre système vont permettre de retrouver des données d’aussi
bonne qualité.  

Pour ma part, je suis plutôt spécialiste de l’imagerie de télédétection et
notamment de l’imagerie radar à synthèse d’ouverture, appelée imagerie SAR.
Par nature, de par la physique même qui sous-tend le système d’acquisition,
les données de ce type de capteur sont forcément bruitées, c’est à dire qu’il
existe une grande variabilité autour de la vraie mesure physique qui nous
intéresse vraiment. Donc en traitement d’image, il y a toute une branche de
restauration d’image pour faire en sorte que ces images aient moins de
fluctuations, qu’il n’y ait pas d’artefacts, qu’elles ne soient pas floues…
Typiquement, nous allons améliorer ces images pour qu’ensuite elles soient
plus faciles à exploiter et que ce soit plus simple d’extraire l’information
de ces images restaurées.

— Pour être un peu plus concret, pouvez-vous nous préciser ce que l’IA peut
faire dans votre domaine pour améliorer la qualité des images en amont et donc
les performances dans l’utilisation qui va être faite par la suite ?

Cela peut consister à essayer de faire ce qu’on appelle de la super
résolution. On a par exemple une image où les pixels sont un peu trop gros, on
va essayer de mettre en œuvre des méthodes d’IA qui soient capables de
retrouver de la résolution, en combinant plusieurs images ou en utilisant des
exemples pour essayer de prédire qu’elle serait une image mieux résolue dans
un domaine particulier. Dans ce domaine, il faut faire attention parce qu’il
ne faut quand même pas créer d’information. Typiquement quand on fait de la
super résolution, on va essayer d’améliorer la résolution du capteur dont on
est parti.

— Vous parlez de capteurs. Ils sont j’imagine de type très divers… vous avez
cité l’exemple des IRM en imagerie médicale. Vous travaillez sur les images
transmises par satellites, mais on est sur un spectre très large…

  * 
Je fais partie d’une équipe qui fait du traitement d’image, et donc il y a des
gens qui travaillent sur différents types de données. Ce qui nous rassemble,
c’est qu’on va tous utiliser de la modélisation mathématique, de
l’apprentissage statistique pour résoudre des problèmes qui sont relativement
similaires, améliorer des données, extraire de l’information.

Cela va diverger notamment dans la physique d’acquisition, on ne va pas avoir
les mêmes systèmes d’acquisition si on fait de l’image médicale, cérébrale
avec de l’IRM, ou, comme moi, de l’imagerie satellitaire avec des satellites
radar. On n’aura pas non plus les mêmes domaines d’application puisque je vais
m’intéresser à des problématiques environnementales alors qu’ils vont
s’intéresser à des problématiques en santé par exemple.  
Mais disons que le cœur des méthodes et les modèles mathématiques utilisés
vont être les mêmes.

— Concentrons-nous maintenant sur votre domaine de recherche actuel, la
télédétection. D’abord pouvez-vous nous dire en quelques mots ce dont il
s’agit ?

Pour simplifier, parlons d’imagerie satellitaire ou d’imagerie aérienne. Au
départ, la télé-détection permet une acquisition de loin, à distance. Mais
cela a pris un sens un petit peu plus restreint, l’imagerie aérienne,
satellitaire ou l’imagerie acquise par des drones, par exemple.

— C’est un domaine qui se développe, de ce fait, au rythme du développement
des moyens que vous venez de citer.

  * 

De très nombreux satellites sont lancés à l’heure actuelle. Alors
qu’auparavant, il était extrêmement coûteux de lancer un satellite et un
système d’acquisition sur ce satellite, les coûts sont désormais réduits, de
nombreux acteurs commerciaux émergé sur ce marché ces dernières années.

Des compagnies sont maintenant capables de lancer des satellites, de faire de
l’acquisition et qui vont essayer de développer des marchés. Alors
qu’auparavant, c’étaient plutôt des groupes de pays qui étaient capables de
lancer ces satellites, maintenant, il y a de plus en plus d’acteurs privés sur
ce marché, qui vont développer d’autres types de services. Au départ, la
télédétection est très liée à l’observation de la Terre, à des problématiques
environnementales. Ces nouveaux acteurs vont s’intéresser à de nouvelles
applications comme la prédiction d’activité…

Un autre grand domaine historique concerne l’activité de défense, avec des
capteurs spécifiques et des données à accès restreint. Mais il y a aujourd’hui
énormément de capteurs civils. L’Agence spatiale européenne (ESA), par
exemple, a envoyé dans les dernières années plusieurs satellites équipés de
capteurs imageurs. Ce sont les missions Sentinel avec des données radar,
optiques, multi-spectrales, etc. Les données sont en libre accès pour tous les
utilisateurs, quels qu’ils soient, grâce à la politique de diffusion des
données de l’ESA.

— Le capteur SWOT est actif depuis le début de l’année. Pouvez-vous nous en
parler ?

L’imagerie radar est une imagerie spécifique qui, en même temps, est une
imagerie difficile parce qu’il y a beaucoup de bruit, cette variabilité dont
j’ai parlé au début, mais elle a un potentiel énorme parce qu’elle peut être
utilisée sous différentes formes en fonction du nombre d’images que nous
sommes capables d’acquérir. En particulier, avec ce type d’imagerie, si vous
êtes capable d’acquérir deux images dans certaines conditions, en faisant de
l’interférométrie, vous pouvez remonter à une information sur la hauteur des
objets à la surface de la Terre et donc calculer des modèles numériques de
terrain ou des modèles numériques d’élévation. SWOT est un capteur
révolutionnaire puisqu’il permet de faire de l’altimétrie, donc de mesurer la
hauteur des points, non seulement sur de toutes petites fauchées, mais aussi
sur de beaucoup plus grandes surfaces au sol. C’est un capteur qui va être
capable de faire de l’interférométrie qu’on appelle mono-passe, c’est-à-dire
qu’il va prendre deux images au même moment. Alors que d’habitude, quand on
fait de l’interférométrie, le capteur passe une première fois, puis à peu près
au même endroit une dizaine de jours après. Dans cette mission, il y a deux
antennes qui sont mises sur un très grand mât et on acquiert simultanément les
deux images. En faisant interférer ces deux images, on va pouvoir mesurer la
hauteur de l’eau à la surface de la Terre, dans les rivières, dans les lacs,
etc.

  * 
C’est révolutionnaire car il n’y avait pas d’instrument qui permettait une
surveillance aussi précise des ressources en eau de la planète auparavant.

Nous sommes impliqués dans SWOT car avons participé aux algorithmes qui
extraient les surfaces d’eau, le masque des lacs et des rivières qui va être
utilisé ensuite pour calculer leur hauteur.

C’est un exemple d’application des algorithmes que nous pouvons développer en
tant que traiteurs d’image pour une problématique environnementale qui va être
la surveillance des ressources en eau de la Terre.

— Oui, c’est un sujet majeur pour la survie de la planète et on comprend la
contribution, certes indirecte mais tout de même fondamentale, que les
algorithmes peuvent apporter. Et vous avez commencé à travailler en réel sur
les images ou bien les données ne sont pas encore acquises à ce moment ?

Nous avons encadré deux thèses en collaboration avec le CNES sur ce sujet, où
nous avons travaillé sur des données simulées sur lesquelles nous avons mis au
point les méthodes d’extraction des surfaces d’eau. Celles-ci sont maintenant
appliquées sur les données réelles qui sont acquises depuis le début de la
mission. Les premières images réellement diffusées ont commencé à être
traitées à partir de l’été.

Nous allons continuer à travailler sur ces données, mais cette fois-ci non
dans la définition de la chaîne opérationnelle comme nous avons pu le faire
dans le passé, mais pour essayer d’aller plus loin dans l’exploitation de ces
données. Il s’agit d’une mission en collaboration entre deux agences
spatiales, la NASA et le CNES. Elles ont des contraintes opérationnelles,
c’est-à-dire qu’elles doivent faire des chaînes de traitement qui soient
capables d’ingérer un très grand nombre de données, de calculer les masques
d’eau, de calculer les hauteurs et de donner des produits aux utilisateurs
finaux.

La partie développement d’algorithmes opérationnels s’est achevée pour que les
traitements puissent être mis en œuvre dès l’acquisition des données par le
satellite. Maintenant que nous avons à notre disposition de vraies images,
nous allons effectuer des travaux plus prospectifs pour voir si nous pourrions
extraire sur de plus petites zones des informations plus précises en
exploitant les images qui sont acquises.

L’idée serait de faire des algorithmes peut-être être plus coûteux et plus
longs à mettre en œuvre, mais plus performants et qu’on pourra utiliser sur
des zones d’intérêt plus restreintes, sur lesquelles on veut étudier plus en
profondeur des phénomènes.

  * 
En résumé, il y a l’aspect à large échelle, afin que les algorithmes soient
capables de tourner très vite et traiter énormément de données, et l’aspect
recherche sur des zones plus petites sur lesquelles on peut extraire des
informations plus précises.

— Vous parlez d’extraire des informations plus précises. Existe-il aussi des
enjeux de sobriété dans l’utilisation des données, et cherchez-vous faire
mieux ou aussi bien avec moins de données ?

Les traitements développés dans le cadre spécifique de SWOT n’utilisent pas
d’apprentissage profond, donc ils sont sobres en termes de temps de calcul
pour leur mise au point (pas d’entraînement). Sur les nouvelles approches que
nous envisageons, il y a effectivement des enjeux de sobriété dans
l’utilisation des données. Comme nous avons beaucoup de problématiques sans
données étiquetées (sans vérité terrain) nous travaillons essentiellement sur
des approches auto-supervisées ou faiblement supervisées.

— Vous nous avez parlé de vos travaux sur les images satellites des niveaux
d’eau et de leur exploitation pour tout ce qui est hydrique, travaillez-vous
sur d’autres applications ?

Mon expertise est essentiellement sur le traitement des images SAR. Pour la
mission SWOT, nous avons été impliqués dès la mise au point des algorithmes en
préparation de la mission en participant à l’ADT (Algorithm Definition Team).
C’est une mission que nous avons donc suivie dans le temps depuis une dizaine
d’années. Mais nous travaillons sur d’autres applications comme la
surveillance de la forêt. Nous travaillons actuellement sur des simulations ou
des données aériennes pour la préparation de la mission BIOMASS, qui va être
également un capteur radar. Plus globalement, nous travaillons sur tout type
de données SAR. Et il y a au moins une dizaine de capteurs qui acquièrent ce
type de données à l’heure actuelle.

— Pour rentrer un peu plus au cœur de votre recherche, pourriez-vous nous
décrire votre travail ?

  * 
Le cœur de notre recherche est de développer des méthodes qui soient capables
d’améliorer ou d’exploiter les données qui sont acquises par les satellites
radar :

que ce soit une unique image ou des combinaisons de plusieurs images dans les
modes interférométrique, polarimétrique ou tomographique. Il y a en effet de
nombreuses modalités différentes avec ces capteurs. Nous avons une politique
de diffusion en open source des différentes avancées que nous arrivons à
mettre au point. Ensuite ces algorithmes peuvent être réutilisés par des
entreprises ou par les agences spatiales pour leurs propres problématiques.

— C’est important pour vous cette notion du partage de données, de science
ouverte pour faire avancer la recherche ?

  * 
Je pense qu’effectivement la science ouverte permet de faire avancer la
recherche, elle est indispensable pour arriver à évaluer les progrès qui sont
faits quand nous proposons de nouvelles méthodes.

Nous avons choisi de mettre les codes en open source pour qu’il puisse y avoir
des benchmarks sur les différentes approches qui sont développées. Et nous
savons que nos algorithmes sont réutilisés pour différentes applications, par
des agences et par des entreprises.

— Justement, vous parlez des acteurs de la chaîne, des chercheurs comme vous
êtes en quelque sorte les intermédiaires entre d’un côté les ingénieurs qui
construisent les capteurs et extraient les données, et de l’autre ceux qui les
reçoivent ; donc plutôt des « climaticiens » ou des climatologues en
l’occurrence pour les questions d’hydrométrie ?

Il y a effectivement les acteurs qui font les systèmes d’acquisition, comme
les agences spatiales que ce soit le CNES ou l’ESA, qui vont essayer
d’acquérir la meilleure donnée possible.

  * 
En tant que traiteurs d’images, nous essayons d’extraire une information sur
ces données et ensuite faisons l’interface avec les utilisateurs qui ont des
problématiques spécifiques.

En l’occurrence pour SWOT, le domaine d’application concerné est l’hydrologie,
mais cela peut être sur différentes problématiques, comme par exemple la
mesure de la biomasse. Cela peut être très varié. Nous avons également des
applications liées à la surveillance et au milieu urbain.

— Pour terminer cet entretien, on parle beaucoup des modèles d’IA génératives
et de leurs applications en matière de recherche et de générations de textes.
Mais on parle beaucoup moins de l’intelligence artificielle dans domaine de
l’’imagerie. Pourtant, on peut dire que les enjeux sont au moins aussi
considérables. C’est un domaine porteur et qui va se développer de façon
exponentielle, vu tous les moyens dont on dispose aujourd’hui pour capter les
images et tous les enjeux auxquels ces technologies permettent de répondre.
Comment appréhendez-vous cela ?

L’imagerie est un champ de développement et d’application fondamentale de
l’IA. Dans le domaine spécifique de la télédétection, on commence à
s’intéresser à la construction de modèles de fondation. Mais pour l’instant,
cela a été testé sur des domaines restreints.

A priori, la nature même des données est un peu différente de celle qu’on peut
avoir en vision par ordinateur classique où il y a énormément de photos
disponibles, avec beaucoup de bases de données existantes. En télédétection,
les images ont des spécificités importantes. Ce sont de très grandes images
qui font souvent 40 000 par 40 000 pixels. Elles contiennent des types
d’objets très nombreux et très variés. De plus, on a des connaissances de
localisation sur ces objets qui sont repérés avec des latitudes et des
longitudes, etc.

Par ailleurs, il existe de multiples capteurs basés sur des principes
physiques très différents. Sera-t-on capable de construire des modèles de
fondation suffisamment abstraits pour prendre en compte différents types
d’images qui seraient acquises avec des capteurs radar, optique, de l’imagerie
hyperspectrale, qui auraient des résolutions spatiales différentes au niveau
des tailles d’objets qu’on peut observer, des résolutions temporelles
également différentes compte tenu des temps de « revisite » des satellites ?
Les travaux commencent sur ce sujet, mais à ma connaissance, nous sommes au
début des tentatives pour créer des modèles de fondation en télédétection.

[](https://www.telecom-paris.fr/fr/ideas/sommaire)

