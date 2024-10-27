# Title: Ideas - L’IA hybride et explicable au service de l'imagerie médicale

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Ideas](https://www.telecom-paris.fr/fr/ideas "Ideas") > [L’IA hybride et explicable pour l’imagerie médicale](https://www.telecom-paris.fr/fr/ideas/ia-hybride-explicable-imagerie-medicale)

[](https://www.telecom-paris.fr/fr/accueil)

# Télécom Paris Ideas  
L’IA hybride et explicable au service de l'imagerie médicale

## L’IA hybride et explicable au service de l’imagerie médicale  
  

[Isabelle Bloch](https://www.telecom-paris.fr/isabelle-bloch), professeure à
Télécom Paris, juin 2024.

Entretien avec Isabelle Bloch, enseignante-chercheuse à Télécom Paris (LTCI)
et Sorbonne Université (LIP6), spécialiste de la modélisation mathématique au
service de l’intelligence artificielle, dont les recherches portent sur l’IA
hybride et explicable, avec de nombreuses applications en interprétation
d’images dans le domaine médical.

L’IA sert ici à aider les médecins à interpréter des images médicales et à
établir des diagnostics, elle facilite la planification thérapeutique ou
chirurgicale grâce à la visualisation des organes et à la définition des zones
à irradier ou au contraire à éviter…

Propos recueillis par Isabelle Mauriac

## Podcasts

Retrouvez cette interview en format audio dans le cadre du [podcast Le ¼
d’heure du chercheur](https://podcast.ausha.co/telecom-paris-ideas "podcast Le
¼ d’heure du chercheur") :

[#1 : L’IA hybride et explicable, au service de l’interprétation
d’images](https://podcast.ausha.co/telecom-paris-ideas/modelisation-
mathematique-en-ia-medicale-ep-1-2-l-ia-hybride-et-explicable-au-service-de-l-
interpretation-d-images)

[#2 : Applications de la modélisation mathématique au service de l’IA
](https://podcast.ausha.co/telecom-paris-ideas/modelisation-mathematique-en-
ia-medicale-ep-2-2-applications-de-la-modelisation-mathematique-au-service-de-
l-ia)

Podcasts Michel Desnoues, Télécom Paris

## Entretien

— Isabelle, nous allons tenter d’appréhender avec vous les principaux enjeux
de vos travaux et leurs applications dans le domaine de la santé. Pour
commencer par une approche très générale, on peut dire que vous construisez
des modèles mathématiques, qui sont ensuite intégrés dans des algorithmes pour
l’aide à l’interprétation d’images, notamment médicales. Pouvez-vous nous
expliquer en quoi cela consiste ?

Effectivement, cela correspond aux deux grands axes de mes recherches. Un
premier axe qui est très formel sur la modélisation mathématique, et en
particulier la modélisation d’informations sur l’espace et du raisonnement sur
ces informations. Le deuxième axe de mes recherches concerne les applications,
en particulier en imagerie médicale. J’essaie de faire le pont en montrant
comment des modèles mathématiques, qui modélisent par exemple nos
connaissances sur un domaine, sur une application médicale, peuvent être
transformés en formules mathématiques, en algorithmes, et ensuite servir
justement pour guider l’interprétation des images. Telle est la chaîne dont
nous disposons.

— Vous parlez d’IA symbolique puisqu’on a besoin de la logique pour
représenter des connaissances et raisonner sur ces connaissances. Pouvez-vous
nous en dire plus ? Qu’est-ce que l’IA symbolique ?

  * 

L’IA symbolique est le domaine qui cherche à modéliser des connaissances, à
les représenter et ensuite à raisonner sur ces connaissances.

Je travaille surtout sur des modèles mathématiques, algébriques et logiques.
L’idée est d’arriver à trouver le bon formalisme qui soit à la fois assez
expressif, c’est-à-dire qui permette de vraiment représenter les informations,
les connaissances dont on a besoin, et de raisonner sur celles-ci pour aider à
prendre des décisions.

— Pour interpréter ces images, vous modélisez les relations entre structures
plutôt que leurs formes elles-mêmes ? C’est ce que vous appelez le
raisonnement spatial. Alors qu’est-ce que c’est précisément ?

Le raisonnement spatial est le domaine qui consiste à modéliser des entités
spatiales, donc des objets, et des relations entre ces objets pour pouvoir
ensuite, dans le cas des applications sur lesquelles je travaille, guider
l’interprétation d’une image, en allant l’explorer à partir de la recherche de
ces objets, des relations entre ces objets. Alors il existe un pan purement
symbolique : comment va-t-on modéliser une relation spatiale par exemple entre
des objets ? Cela peut être une relation décrite de manière très qualitative
dans une base de connaissances, par exemple tel objet est à droite ou est
proche de tel autre. Pour modéliser cela, nous allons mettre en œuvre des
modèles mathématiques, et ensuite faire le lien avec l’image, donc avec des
informations très concrètes et numériques telles qu’on les a dans les images.

Par exemple, dire qu’un objet est proche d’un autre n’aura pas la même
signification si l’on parle de structures anatomiques dans une image médicale
ou si l’on parle de distance entre des villes dans une image satellitaire par
exemple. Ce que je fais en raisonnement spatial, c’est à la fois cette
modélisation, le pont avec des informations qui sont dans les images, et
guider l’exploration de l’image en combinant les informations de l’image et
ces modèles de connaissances sur les relations spatiales.

— Vous dites sur le raisonnement spatial qu’il est plus fiable et pérenne de
se reposer sur les relations spatiales entre les objets plutôt que sur leur
forme ? Pouvez-vous nous expliquer pourquoi ?

En imagerie cérébrale, on a beaucoup travaillé sur la reconnaissance des
noyaux gris internes par exemple, qui sont des structures au milieu du
cerveau, et qui en imagerie par résonance magnétique ont à peu près le même
niveau de gris. Donc on ne peut pas les reconnaître juste d’après leur
apparence. Ces structures ont des formes qui sont parfois difficiles à
distinguer et, surtout lorsqu’il y a une pathologie, ces formes peuvent
beaucoup changer. Par exemple si une tumeur vient compresser des structures ou
les repousser, la forme n’est pas du tout celle à laquelle on s’attend en
l’absence de pathologie. Donc s’appuyer uniquement sur les formes n’est pas
très robuste, justement dans le cas où il y a ces grosses déformations à cause
de pathologies. Au contraire, les relations spatiales sont assez stables et
elles restent vérifiées même quand il y a ces déformations. Ainsi par exemple,
dire qu’une structure est à droite d’une autre reste vrai même si la structure
a été compressée. Et cela est renforcé par la manière dont on modélise les
relations spatiales qui reposent sur des modèles qui sont assez souples.

— Vous avez travaillé auparavant sur la fusion d’informations, ou comment
combiner des informations variées issues d’images d’origines différentes d’un
même problème et améliorer ainsi la prise de décision quant à l’objet
d’observation. Ces travaux sur la fusion font aujourd’hui partie du processus
de traitement de l’information dans plusieurs domaines, y compris les travaux
en cours en imagerie médicale et en raisonnement spatial. De quoi s’agit-il ?

Effectivement, j’ai travaillé pendant assez longtemps sur la fusion
d’informations, plus précisément la fusion d’images multisources. Je me suis
penché en particulier sur les opérateurs qui permettent de combiner des
informations venues de ces différentes images en fonction de leurs
spécificités. Ensuite j’ai exploité ces méthodes pour combiner des
informations de natures différentes. Cela peut être des images, des modèles de
connaissances, différents types de relations spatiales.

Par exemple, pour reconnaître une structure, on va utiliser des relations
spatiales de différentes natures par rapport à différents objets et il va
falloir combiner toutes ces informations pour aider à la prise de décision.
C’est dans ce sens que je travaille sur la fusion d’informations actuellement,
sur le volet plutôt applicatif. Un autre volet, théorique, porte sur les
approches logiques, donc symboliques à nouveau, pour résoudre des problèmes de
fusion d’informations, par exemple des opinions de personnes, des préférences,
etc. avec des modèles logiques. On en revient aux méthodes algébriques et
symboliques dans ce cas-là.

— La fusion d’information nous amène à parler de l’IA hybride qui va mélanger
de la modélisation des connaissances, du raisonnement avec des informations
qu’il est possible d’apprendre à partir des données. Je crois qu’elle est
importante dans vos travaux. Alors pouvez-vous nous parler de cette
hybridation, qui permet de prendre en compte les spécificités du domaine pour
guider les algorithmes d’IA par apprentissage ?

  * 

L’IA hybride est le domaine sur lequel je travaille le plus en ce moment avec
les questions d’explicabilité. L’idée est justement de combiner des approches
qui viennent de l’IA que l’on appelle symbolique et des méthodes
d’apprentissage à partir de données (qui est le sens que l’on donne couramment
à l’IA en ce moment, mais ce n’est pas la seule partie de l’IA !).

On peut apprendre beaucoup de choses à partir des données et il y a des
algorithmes désormais très puissants qui permettent de réaliser des tâches
assez complexes uniquement à partir de données, mais en imagerie médicale on
n’a pas toujours assez de données. Je travaille beaucoup en particulier en
imagerie pédiatrique où il y a vraiment peu de données – heureusement pour les
enfants, d’ailleurs – et où il existe des pathologies rares et très
spécifiques aux enfants.  
En revanche, on a énormément de connaissances, accumulées depuis des siècles.
Donc, combiner les deux permet à la fois d’exploiter ces connaissances mais
aussi d’utiliser l’information que l’on a dans ces bases de données même si
elles sont plus limitées que dans d’autres domaines.

— Donc l’hybridation permet de contribuer à bénéficier de systèmes pouvant
fonctionner avec des jeux de données limités et plus explicables ; en quoi
précisément ?

  * 

L’IA hybride permet d’aller vers l’explicabilité dans le sens où l’on va
maintenir un lien entre les connaissances, les données et les résultats. On
peut donc faire une sorte de va-et-vient.

Par exemple, les connaissances vont guider l’interprétation des données pour
arriver à un résultat. Inversement, il est possible d’expliquer un résultat en
regardant quelles connaissances ont été mobilisées pour l’obtenir et donc
expliquer ce résultat par le lien avec tel ou tel aspect des connaissances et
des données. L’explicabilité est un domaine très vaste. Il y a beaucoup de
significations. C’est un domaine très ancien, les philosophes se sont posé ces
questions dans l’Antiquité déjà, et il a été formalisé surtout avec des
approches logiques à la fin du XIXe siècle, avec des processus de raisonnement
que l’on appelle par abduction. C’est-à-dire qu’étant donné une base de
connaissances, on cherche à expliquer une observation à partir de la base de
connaissances. On a beaucoup travaillé sur ces approches logiques et on essaie
de faire le lien avec les méthodes qui manipulent des données.  
C’est là où on retrouve le lien avec l’IA hybride .

— Après cette revue des modèles de raisonnement que vous utilisez, passons à
l’interprétation d’images, notamment médicales. Pouvez-vous nous préciser ce
que sont la segmentation et la reconnaissance en imagerie médicale ?

  * 

Une image médicale est un volume de points avec une intensité, un niveau de
gris. Dans ce volume on veut extraire des informations utiles pour les
médecins, et une des tâches importantes est ce que l’on appelle la
segmentation, c’est-à-dire extraire une structure particulière qui va
intéresser les médecins.

Par exemple, on va s’intéresser à extraire les noyaux gris, pour reprendre
l’exemple de tout à l’heure. Ensuite, la reconnaissance consiste à être
capable d’identifier la structure extraite. Donc lui attacher un nom, le nom
de l’organe, le nom de la pathologie… c’est la partie reconnaissance. Dans la
plupart des méthodes que l’on développe, la segmentation et la reconnaissance
sont souvent effectuées simultanément, c’est-à-dire que l’on cherche à
segmenter un organe particulier dont on connaît la nature, l’étiquette en
quelque sorte, ou une pathologie particulière.

— Quelles sont les applications de vos travaux dans le domaine médical ? On
voit que de fréquents échanges sont nécessaires entre vous et ces différents
praticiens. Avec quels acteurs travaillez-vous le plus régulièrement ?

Les applications médicales sont mon domaine de prédilection depuis de
nombreuses années, et je travaille de manière très étroite avec des services
hospitaliers dans des CHU, avec des radiologues et avec des chirurgiens. La
demande vient parfois des médecins qui ont une question à résoudre et nous en
discutons ensemble. Les méthodes que nous développons résultent d’un dialogue
et d’allers et retours permanents entre les médecins qui vont exprimer leurs
besoins et ce qu’on peut leur apporter. Trouver le juste équilibre prend un
petit peu de temps, mais c’est aussi l’intérêt du domaine.

— Vous nous avez parlé au début de cet entretien de l’IA hybride, qui permet
de prendre en compte les spécificités du domaine pour guider les algorithmes
d’IA par apprentissage. C’est le cas ici ?

Dans toutes ces applications-là justement, j’utilise beaucoup les méthodes que
j’ai décrites en IA hybride. Nous essayons de comprendre les connaissances
qu’utilisent les médecins pour effectuer une certaine tâche, parfois
visuellement, pour ensuite essayer de modéliser les informations qu’ils
utilisent, pour les aider à faire cette tâche de manière moins fastidieuse,
peut-être plus reproductible…

— Vous avez travaillé sur de nombreuses applications, notamment un projet avec
Necker sur la reconnaissance de faisceau de nerfs en imagerie pédiatrique
(dans lequel Pietro Gori, maître de conférence à Télécom Paris, est aussi
impliqué, je crois ?)

Nous avons travaillé dans plein de domaines différents, dont beaucoup en
imagerie pédiatrique, en particulier sur un grand projet avec l’hôpital
Necker, auquel [Pietro Gori](https://www.telecom-paris.fr/fr/ideas/ia-
imagerie-medicale-donnees) participe, dans lequel nous cherchons à aider les
chirurgiens à préparer la chirurgie à l’aide d’images. Les outils que nous
développons comblent ce fossé entre l’image et les besoins du chirurgien : les
images sont des volumes que l’on voit souvent sous forme de coupes, donc en
deux dimensions, et ça n’est pas très facile en voyant quelques coupes
d’imaginer l’espace à trois dimensions, les rapports entre les organes, les
pathologies et les organes, etc.

— L’objectif est de guider les chirurgiens pour avoir des modèles qui
comprennent les organes du patient, mais aussi les nerfs ?

Ce que nous proposons consiste à travailler sur des algorithmes pour segmenter
et reconnaître des organes, des pathologies mais aussi les vaisseaux sanguins,
les nerfs, etc., à partir des images, puis pour construire des modèles 3D
numériques qui sont des modèles individuels, donc au niveau du patient. Une
fois ce modèle disponible, la chirurgienne avec laquelle nous travaillons à
Necker peut visualiser en 3D les organes, les rapports entre les tumeurs et
les organes, voire le trajet des nerfs parce qu’évidemment ce sont des
structures qu’elle va éviter de léser pendant la chirurgie pour éviter les
effets secondaires, et donc préparer sa chirurgie à partir de toutes ces
informations.

— Pouvez-vous nous citer un exemple concret et assez poignant d’une
application de ces modèles 3D numériques sur un enfant, je crois ?

On a un exemple emblématique d’un petit enfant d’environ 18 mois qui avait
plusieurs tumeurs dans les deux reins. En voyant juste les coupes, les
chirurgiens et toute l’équipe pluridisciplinaire qui traitait ce cas avaient
l’impression qu’il allait falloir enlever les deux reins… Cela implique des
dialyses trois fois par semaine, d’énormes conséquences pour l’enfant. En
voyant le modèle 3D, la chirurgienne a mieux compris où étaient vraiment les
tumeurs ; elle est arrivée à garder un demi-rein de chaque côté et ça a
marché. Évidemment les conséquences sont complètement différentes ! Les
résultats ne sont pas toujours aussi spectaculaires que dans ce cas, mais
c’est un exemple qui montre bien l’intérêt de ces modèles.

  * 

Un autre intérêt de ces modèles, c’est l’interaction avec les patients et les
parents quand il s’agit de petits enfants. Ils vont mieux comprendre ce qui se
passe, ce que va être la chirurgie, avec ses conséquences possibles. Il y a
alors un bien meilleur accompagnement et une bien meilleure acceptation de ce
qui va se passer.

— Et concernant les applications de ces modèles à l’imagerie médicale, sommes-
nous sur une utilisation très ciblée ou au contraire qui pourrait être assez
répandue ?

Notre algorithme marche sur des cas assez variés. Pour l’instant, nous avons
surtout travaillé sur le pelvis et l’abdomen mais nous essayons de l’étendre à
d’autres parties du corps et la plupart des étapes sont automatiques. Nous
laissons quand même la possibilité au médecin de corriger par exemple des
segmentations, parce que le résultat n’est pas toujours parfait, mais cela se
fait très rapidement et il y a peu d’intervention manuelle nécessaire. Donc
cela fait gagner un temps énorme par rapport à faire toute la segmentation à
la main. Le médecin a bien sûr le contrôle sur le modèle qui est produit, et
ensuite, il décide si cela lui est utile ou pas.

— Et avez-vous recours à de l’IA hybride dans ce cas ?

C’est justement pour les nerfs qu’une approche hybride est adoptée, car il n’y
a vraiment pas assez de données pour bénéficier d’une approche pure par
apprentissage, afin de reconnaître les nerfs du pelvis par exemple. En
revanche, des livres, par exemple d’anatomie, décrivent le trajet des nerfs
par rapport à des structures anatomiques, par rapport aux vertèbres, par
rapport à certains muscles… Ce trajet des nerfs est modélisé afin de s’en
servir ensuite pour les reconnaître à partir de données venant d’une technique
particulière en imagerie par résonance magnétique : l’IRM de diffusion qui
montre le trajet de l’eau le long de fibres. Sur ces données sont appliqués
des algorithmes appelés de tractographie qui vont essayer de suivre toutes les
fibres.  
Le résultat de la tractographie est un énorme paquet de fibres avec des
millions d’entre elles parmi lesquelles il nous faut sélectionner celles
correspondant à des nerfs particuliers. Et c’est ici où le raisonnement
spatial intervient avec ces approches hybrides où l’on s’appuie sur le trajet
des nerfs pour extraire les seules fibres qui correspondent aux nerfs qui nous
intéressent.

— Grâce à ces exemples, on appréhende mieux les notions d’IA symbolique, de
raisonnement spatial et d’IA hybride. Y-a-t il encore d’autres applications
marquantes de vos travaux dans le domaine médical ?

Nous avons travaillé sur plusieurs autres applications, par exemple avec
l’hôpital Bicêtre sur des enfants prématurés qui avaient des problèmes de
croissance. Ce qui intéressait les radiologues était de mesurer le corps
calleux, une structure reliant les deux hémisphères du cerveau, et de voir si
chez les enfants prématurés le corps calleux se développait normalement ou
pas, avec l’hypothèse qu’un développement anormal du corps calleux pouvait
être un signe de problèmes cognitifs intervenant plus tard, à partir de l’âge
de deux ans. L’idée était d’avoir de manière très précoce des mesures de
l’épaisseur du corps calleux et de l’évolution dans les premiers mois de vie
de l’enfant. C’est un autre exemple d’application.

Nous avons également travaillé sur des applications en radiothérapie, en
particulier sur des images thoraciques où l’on fusionnait des informations qui
venaient d’images anatomiques, de scanner à rayons X par exemple, et d’images
fonctionnelles d’imagerie nucléaire, en particulier de tomographie par
émission de positons.  
L’idée était de localiser des tumeurs et de voir où elles se situaient par
rapport à d’autres organes situés autour, en particulier des organes à risque
qui ne devaient pas être irradiés. Cela permettait aux radiothérapeutes de
définir la zone à irradier avec une marge de sécurité comme ils ont l’habitude
de le faire en ayant une connaissance des marges à ne pas dépasser pour ne pas
atteindre des organes qui ne fallait pas irradier.

— Nous arrivons à la fin de cet entretien ; pour ouvrir le sujet, j’aimerais
que nous abordions votre second métier, celui d’enseignante. Vous formez au
traitement et à l’interprétation d’images à Télécom Paris, observez-vous un
intérêt croissant des étudiants ?

Dans le domaine de l’image, il existe une formation à Télécom Paris assez
pointue en analyse d’images, tandis que j’enseigne aussi à Sorbonne Université
dans des domaines similaires. L’intérêt des étudiants n’a jamais diminué et a
plutôt tendance à augmenter avec le développement des techniques par réseaux
de neurones, justement très développées dans le domaine de la vision par
ordinateur et l’analyse d’images.

  * 

Ce qui est enseigné porte à la fois sur les approches mathématiques de l’image
: comment on modélise des connaissances sur les images pour les analyser, et
sur des techniques qui s’appuient sur les données donc par apprentissage par
réseaux de neurones etc. Cela peut aller des prétraitements jusqu’à
l’interprétation, donc la reconnaissance de structures, l’interprétation de
scènes.

On garde ces deux volets en permanence et l’intérêt est de faire bien
comprendre aux étudiants ce que c’est qu’une image, quels types d’informations
elle apporte et de la voir vraiment comme un espace particulier où l’on parle
d’information spatiale avec des propriétés particulières. Ce n’est pas
simplement un paquet de points que l’on met en entrée d’un algorithme
d’apprentissage !

Je crois qu’il est important de garder ces deux aspects. Et c’est apprécié des
établissements qui recrutent les élèves et les étudiants pour des stages ou
pour des emplois par la suite.

— Et pour travailler sur la modélisation dans le secteur de la santé il leur
faut aussi compléter leur cursus dans ce domaine j’imagine ?

Certaines et certains étudiants n’ont pas forcément de connaissances en santé,
donc nous proposons une petite introduction aux techniques d’imagerie en cours
d’imagerie médicale, qui ne va pas très loin dans la physique des systèmes
d’imagerie évidemment, mais qui en dit juste assez pour qu’elles et ils
comprennent bien la nature de l’information présente dans les images, ce qui
permet de bien comprendre le type de bruit, le type d’informations visible ou
non suivant la modalité d’imagerie, et en arriver ensuite aux méthodes en aval
d’analyse d’images.

  * 

Dans le cadre de projets ou de stages, nous faisons très souvent travailler
nos élèves avec des médecins avec qui nous collaborons : c’est très stimulant
parce que l’intérêt est immédiatement perceptible.  
L’acquisition des connaissances en santé se fait surtout par le dialogue avec
les médecins… Nos élèves ne seront pas médecins après ce type de projet ou de
stage mais ils en sauront suffisamment pour pouvoir dialoguer et développer
des outils intéressants et répondant à des vraies questions.

— Nous allons clore cet entretien sur les applications de la modélisation
mathématique au service de l’intelligence artificielle dans un tout autre
domaine, celui de la musique. Vous avez entamé récemment une collaboration
prospective avec des chercheurs de l’Ircam (Institut de Recherche et
Coordination Acoustique/Musique) afin d’étendre les outils de représentation
spatiale que vous avez développés, pour envisager des ramifications dans la
représentation spatiale de la musique. Pouvez-vous nous en parler ?

Oui effectivement, j’ai commencé à travailler depuis quelques années avec des
chercheurs de l’Ircam (STMS) en particulier avec l’équipe de représentations
musicales. Elle s’intéresse à des représentations symboliques de la musique,
qui prennent souvent la forme de représentations dans un certain espace et
donc finalement assez proches de l’information que l’on utilise en images.

L’information n’est pas du tout de même nature mais l’idée est de voir si des
méthodes venant de l’analyse d’images peuvent être appliquées aux
représentations symboliques de la musique.

Nous avons beaucoup travaillé sur une théorie appelée la morphologie
mathématique en images, et nous nous sommes rendu compte qu’effectivement elle
pouvait être appliquée, avec évidemment des adaptations, sur des
représentations de la musique. Dans des représentations en temps et en
fréquence par exemple, il est possible de retrouver un certain nombre de
composantes d’une musique jouée, par exemple les attaques, le bruit, etc. ;
sur des représentations plus abstraites, nous avons travaillé sur
l’homogénéité et sur la répétition, qui sont des composantes importantes de la
musique. Par exemple, sur la répétition nous avons développé des outils à
partir de méthodes de morphologie mathématique pour détecter des motifs qui se
répètent, trouver ces motifs, trouver où ils démarraient, comment ils se
répétaient…

Cela structure finalement la musique et donc aide à son interprétation.
Certains de ces outils peuvent aussi être utilisés pour la génération de
musique.

— Et pour les prochains mois, quel sujet aimeriez-vous explorer davantage ?

  * 

Sur les questions d’explicabilité, il y a encore beaucoup de choses à faire et
en particulier pour voir comment des méthodes d’hybridation et d’explicabilité
pourraient compenser des biais possibles dans les données et dans
l’utilisation des algorithmes, à la fois des biais statistiques et des biais
cognitifs. Ce sont des questions qui se posent qui restent assez ouvertes.

## Vidéos

Aider les médecins à interpréter des images médicales et à établir des
diagnostics, faciliter la planification thérapeutique ou chirurgicale grâce à
la visualisation des organes, mieux définir les zones à irradier ou au
contraire à éviter… Les applications de l’IA en interprétation d’images dans
le domaine médical sont multiples.

Isabelle Bloch nous parle de ses recherches sur l’IA hybride et explicable,
qui permet de combiner des approches venant des connaissances, avec des
méthodes d’apprentissage à partir des données.

Alors, qu’est-ce que précisément l’IA hybride et explicable ?

Pour afficher ce contenu, merci d’accepter les cookies des vidéos Youtubedes
extraits de réseaux sociaux (Twitter, Instagram & Facebook).To display this
content, please accept third party cookies for Youtube videosFacebook,
Instagram and Linkedin excerpts.

Réglages

L’IA hybride et explicable au service de l’interprétation d’images dans le
domaine médical

  * L’hybridation : vers des systèmes fonctionnant avec des données limitées et plus explicables
  * La segmentation et la reconnaissance en imagerie médicale

Pour afficher ce contenu, merci d’accepter les cookies des vidéos Youtubedes
extraits de réseaux sociaux (Twitter, Instagram & Facebook).To display this
content, please accept third party cookies for Youtube videosFacebook,
Instagram and Linkedin excerpts.

Réglages

L’IA au service de la planification thérapeutique ou chirurgicale pour guider
les chirurgiens à partir de modèles 3D numériques

  * L’IA hybride : prise en compte des spécificités du domaine pour guider l’apprentissage
  * Une collaboration avec l’Hôpital Necker
  * Guider les chirurgiens par la modélisation 3D
  * Un exemple d’application des modèles 3D numériques sur un enfant
  * Reconnaissance des nerfs par approche hybride

Vidéos Michel Desnoues, Télécom Paris

[](https://www.telecom-paris.fr/fr/ideas/sommaire)

