# Title: Ideas - L’IA appliquée à l’imagerie médicale : quelles recherches ? quels résultats obtenus et attendus ?

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Ideas](https://www.telecom-paris.fr/fr/ideas "Ideas") > [L’IA appliquée à l’imagerie médicale, quelles recherches?](https://www.telecom-paris.fr/fr/ideas/ia-imagerie-medicale-recherches)

[](https://www.telecom-paris.fr/fr/accueil)

# Télécom Paris Ideas  
L’IA appliquée à l’imagerie médicale : quelles recherches ?

## L’IA appliquée à l’imagerie médicale :  
  
Quelles recherches ? Quels résultats attendus et obtenus ?

[Elsa Angelini](https://perso.telecom-paristech.fr/angelini/) et [Pietro
Gori](https://www.telecom-paris.fr/pietro-gori), enseignants-chercheurs à
Télécom Paris, sept. 2023.

Après nous être penchés sur les enjeux pour[ accéder à la data en imagerie
médicale](https://www.telecom-paris.fr/fr/ideas/ia-imagerie-medicale-donnees),
nous nous intéressons aux recherches en la matière, toujours avec Elsa
Angelini et Pietro Gori, enseignants-chercheurs à Télécom Paris.

Comment la recherche peut-elle répondre aux problématiques d’accès à la data
en développant des méthodes d’IA et d’apprentissage efficaces et robustes ?

Propos recueillis par Isabelle Mauriac

## Podcast

Retrouvez cette interview en format audio dans le cadre des [podcasts Télécom
Paris Ideas](https://podcast.ausha.co/telecom-paris-ideas) :

Podcast Michel Desnoues, Télécom Paris

## Entretien

— Pietro, pouvez-vous nous expliquer sur quoi porte votre recherche ?

Ces dernières années, en partenariat surtout avec NeuroSpin, nous avons essayé
de répondre à la question du manque de données. Nous avons peu de données, peu
d’annotations. En revanche, nous pouvons avoir beaucoup de données de sujets
sains. Quand on passe par exemple un scanner ou un IRM, la plupart sont sains,
ils n’ont pas de maladie. Par conséquent, on a beaucoup d’images de sujets
sains… avec NeuroSpin par exemple, nous avons collecté jusqu’à 10 000 sujets
sains. Nous nous sommes demandées comment nous pouvons exploiter ces sujets
sains pour mieux détecter certaines maladies, par exemple, des tumeurs au
sujet desquelles on a des bases de données beaucoup plus petites. Pour donner
un ordre de grandeur, quand on parle de maladies, souvent, c’est de l’ordre de
quelques centaines ou quelques milliers.

— Je comprends l’idée… un peu comme si on prenait le négatif d’une image… mais
comment cela fonctionne-t-il ?

Pour ce projet spécifique, nous sommes partis de cette idée : pourrions-nous
construire une sorte de représentation abstraite informatique de sujets sains
? Nous avons travaillé avec des images de cerveau et avons récolté une grande
base d’IRM du cerveau de sujets sains. Et nous avons réussi à construire une
représentation du cerveau sain de l’être humain avec aussi sa variabilité. Une
une fois cette représentation construite, nous avons utilisé toutes les
métadonnées à disposition, l’âge, le sexe, etc., pour pouvoir enrichir cette
représentation. Après, la question a été celle du transfert de ces données, ce
qui relève du transfer learning. Pouvons-nous la transférer vers de petites
bases pour mieux détecter les maladies ? Dans notre cas, ce sont les maladies
psychiatriques, donc l’autisme, la schizophrénie et la maladie bipolaire.

L’idée de ce projet de recherche est de construire cette représentation, en
exploitant des techniques de transfer learning, d’auto-apprentissage : on a
des sujets sains ainsi que des sujets très âgés. Ce qu’on sait, grâce à
l’expérience des cliniciens, c’est que les cerveaux de deux sujets jeunes se
ressemblent plus que ceux d’un sujet jeune et d’un sujet âgé. On sait qu’ils
devraient se ressembler d’un point de vue clinique, et on arrive à le
modéliser, dans cet espace de représentation informatique abstrait où ils
seront proches d’un point de vue mathématique et géométrique. Et inversement,
un sujet jeune et un sujet âgé, qui cliniquement ne se ressemblent pas,
doivent être situés loin l’un de l’autre dans cet espace. Donc, en exploitant
cette idée, mathématiquement et informatiquement, on a réussi à créer cet
espace de représentation et à l’exploiter, aussi pour mieux comprendre quelle
est l’anatomie du cerveau, et parvenir à mieux détecter les maladies
psychiatriques, en particulier l’autisme, la schizophrénie et les troubles
bipolaires.

— Donc cela fonctionne, et de ce fait, quelles sont les applications que vous
envisagez ou avez déjà lancées ?

Oui, nous avons réussi à l’exploiter. L’autre stratégie qui était jusque-là
utilisée, c’était plutôt de se dire, on prend des sujets sains, des sujets
malades, et « from scratch » (de zéro), on essaie de développer un algorithme
d’IA qui va distinguer les sujets malades et les sujets non malades. Notre
façon de travailler se distingue en ce que nous construisons puis appliquons
cette représentation. Et nous avons montré dans plusieurs travaux
scientifiques qu’avec cette approche, on arrive à mieux détecter les maladies.
Un sujet passe, par exemple, un IRM ; la question est de savoir s’il a ou non
une certaine maladie, mais surtout de comprendre où sont les biomarqueurs
anatomiques qui nous disent si cette personne a une maladie ou pas. C’est-à-
dire quelle est la partie du cerveau finalement « anormale » par rapport au
sujet sain.

  * 

Grâce à cette méthode d’IA que nous avons développé en collaboration avec
NeuroSpin, nous avons réussi à mieux identifier les parties du cerveau
anormales par rapport au sujet sain, qu’on pourrait qualifier de biomarqueurs
de ces maladies.

— Et comment cela va-t-il être exploité ? Qu’allez-vous faire maintenant ?
Cela donne-t-il des indications pour faire de la prévention ou pour d’autres
exploitations ?

Effectivement en utilisant ces méthodes, on arrive à mieux comprendre la
maladie, donc à trouver ces biomarqueurs, à avoir un algorithme d’IA qui se
concentre sur les bonnes parties du cerveau pour comprendre si quelqu’un est
malade ou pas, ce qui est finalement la question. Ensuite, l’idée est
d’exploiter tous ces méthodes d’IA pour mieux comprendre la maladie, ainsi que
trouver de nouveaux biomarqueurs. Quand on parle de biomarqueurs, cela veut
dire comprendre quelles sont finalement les parties du cerveau où, à l’œil nu,
on n’arrive pas forcément à repérer qu’il y a des différences par rapport au
sujet sain parce que les différences sont très subtiles.

  * 

Donc l’hypothèse est qu’un algorithme d’IA peut apprendre ces subtilités, ces
petites différences et les exploiter pour mieux détecter si quelqu’un est
malade ou pas.

Pour l’instant, nous travaillons sur la détection, mais le projet serait
ensuite d’exploiter ces données longitudinales pour pouvoir comprendre si
quelqu’un aura la maladie d’ici 5, 10 ans, 20 ans. C’est quelque chose qu’on
essaie déjà de faire par exemple pour le maladie d’Alzheimer. Le frein pour
développer ce type de méthode est une fois les données. Car qui dit des
données longitudinales implique des cohortes, encore plus de données.

Un sujet qui, âgé de 20 ans par exemple, était encore sujet sain, a passé un
IRM à l’âge de 30 ans, à 40 ans, à 50 ans, puis 60 ans. L’idée serait d’avoir
des données qui suivent u n sujet pendant toute sa vie afin d’arriver à
comprendre pourquoi cette personne tombe malade ou pas. Avoir ce type de
données serait effectivement extrêmement important mais aujourd’hui elles sont
rares.

— Oui et il y a aussi tous les facteurs externes (la façon de se nourrir, la
pratique sportive, la pollution…) qui contribuent à la pathologisation. C’est
ce que vous disiez, Elsa, dans la [précédente interview](https://www.telecom-
paris.fr/fr/ideas/ia-imagerie-medicale-donnees) sur le fait d’avoir des très
grandes cohortes qui permettent d’avoir un focus très large sur les facteurs
externes…

Tout à fait, c’est essentiel et d’ailleurs sur le sujet de l’imagerie
cérébrale et des pathologies de type, les États-Unis sont beaucoup plus en
avance et ont vraiment monté des grosses cohortes qui sont partagées et
accessibles par des groupes comme nous et où les sujets ont été suivis sur
plusieurs années. Mais la complexité, c’est que effectivement le temps
d’évolution et le moment très en amont où on voudrait faire le pré-diagnostic
est beaucoup plus long que dans d’autres maladies et donc le challenge est
énorme pour ces maladies-là.

— Et il est vrai que les maladies évoluent aussi en même temps que vous menez
vos recherches ; je pense au cancer qui a un impact énorme sur nos modes de
vie, la façon de se nourrir, le sport, la pollution… ce qui j’imagine
complexifie la recherche…

On en est vraiment au tout début d’essayer d’intégrer ce qu’on appelle les
données de style de vie et d’exposome, enfin tout ce qui est exposition et
pollution, et les rendre interopérables avec les données provenant des
hôpitaux. Mais tout le monde est bien conscient que c’est effectivement
essentiel dans la personnalisation du diagnostic ainsi que du pronostic qui
est de prévoir précocément des risques de développement de pathologie.

— Elsa, pouvez-vous nous parler de vos travaux de recherche, d’un exemple
utile ?

Actuellement, mes travaux de recherche couvrent typiquement trois domaines
assez différents. Le premier concerne l’exploitation des scanners pulmonaires
pour caractériser une pathologie qui s’appelle l’emphysème et ensuite
caractériser mieux des pathologies très localisées sur l’arbre des bronches
pulmonaires qui sont des toutes petites structures au milieu de cette immense
tissu pulmonaire.

Un deuxième exemple de projet est notre travail avec une entreprise qui
fabrique des machines d’imagerie par bio luminescence depuis deux ans, pour
essayer de mieux quantifier des images qui sortent de leurs machines de telle
sorte que, par exemple, les biologistes qui vont s’en servir pourront faire
des mesures qui soient comparables à deux jours d’intervalle quand par exemple
elles mettent la même souris sur laquelle on est en train de tester un
traitement contre le cancer… Parce que pour l’instant il y a beaucoup de
variabilité intrinsèque aux images et que les mesures pourraient être beaucoup
plus fiables et standardisées, grâce à des algorithmes qui permettent
d’éliminer la partie variable et de ne vraiment extraire que la partie qui
devrait servir à la quantification de la taille de la tumeur par exemple.

Troisième exemple : travailler à des systèmes de correction d’annotation ou de
segmentation qui soit intelligents et qui permettent aux experts d’aller très
vite sur des images d’histopathologies qui sont immenses. Cela consiste à
rendre l’algorithme intelligent et réactif à tout ce qui peut être rentré par
un expert.

— Et pouvez-vous nous parler de votre collaboration avec Columbia University
sur la qualification de l’emphysème ?

Depuis une dizaine d’années j’ai une collaboration avec Columbia University où
j’avais fait ma thèse initialement. À l’origine, c’est un médecin qui est venu
nous chercher avec une problématique très ouverte qui était de mieux exploiter
les scanners pulmonaires pour quantifier l’emphysème et le caractériser, en
partant du constat qu’il n’y a pas un type d’emphysème, mais de nombreux
types. Certains fumeurs développent de l’emphysème, certains pas du tout,
tandis que l’emphysème est une évolution naturelle chez les personnes âgées.
Un peu comme le cerveau qui évolue, le poumon évolue et se dégrade, il existe
de l’emphysème normal et de l’emphysème dû à l’exposition à la cigarette ou à
la pollution, ou des facteurs génétiques.

Columbia University, dont fait partie ce médecin, était à la tête
d’acquisition de cohortes d’images et de registres et qui comportaient des
images cardiaques avec une partie du poumon et des images qui contenaient tout
le poumon. C’est un scénario idéal où les images nous étaient apportées sur un
plateau. Nos avons commencé à travailler et avons d’abord redéfini ce qu’était
un emphysème d’un point de vue algorithmique pour être beaucoup plus précis et
spécifique que le médecin qui regarde une image. Ensuite, une fois que nous
sommes accordés sur ce qu’était l’emphysème, nous nous sommes attaqué à
essayer d’en faire des clusters de différentes signatures visuelles et de
textures. De fil en aiguille, nous sommes arrivés à nous mettre d’accord sur
six sous-types d’emphysème que les médecins ont nommés et à propos desquels
ils ont été assez rapidement persuadés que cela correspondait à une certaine
réalité. Ensuite quand on a fait des associations entre les types d’emphysème
et les métadata, il en est ressorti de façon très claire qu’il y a certains
emphysèmes qu’on ne voyait qu’avec des anciens ou actuels fumeurs alors qu’il
y a des emphysèmes qui étaient vraiment prédominants dans la population.

Nous en sommes maintenant à caractériser de façon moléculaire ces sous-type en
se disant que peut-être il y a encore d’autres sous-types. Et c’est là où nous
allons faire appel à des données de marqueurs génétiques, à essayer de les
caractériser dans le temps : évoluent-ils tous de la même façon à dix ans
d’écart, par exemple ? Également, nous allons caractériser ces marqueurs sur
d’autres acquisitions de scanners, parce que nous avons jusque-là travaillé
sur des scanners à « inflation maximum » , alors qu’il existe aussi des
scanners à « expiration maximum » : nous voudrions essayer de combiner
inflation maximum et expiration maximum pour proposer éventuellement d’autres
sous-types encore plus précis d’emphysèmes, avec ce qu’on appelle une «
significance » clinique, par exemple…

  * 

… un pouvoir prédictif de l’évolution à prévoir dans cinq ans qui soit
beaucoup plus précis.

## Vidéo

Pour afficher ce contenu, merci d’accepter les cookies des vidéos Youtubedes
extraits de réseaux sociaux (Twitter, Instagram & Facebook).To display this
content, please accept third party cookies for Youtube videosFacebook,
Instagram and Linkedin excerpts.

Réglages

« Une collaboration avec le laboratoire Neurospin pour le diagnostic des
troubles psychiatriques : nous avons développé un algorithme basé sur l’idée
de l' »auto-apprentissage ». »

Vidéo Michel Desnoues, Télécom Paris

[](https://www.telecom-paris.fr/fr/ideas/sommaire)

