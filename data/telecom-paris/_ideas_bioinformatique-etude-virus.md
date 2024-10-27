# Title: Ideas - La bioinformatique : les enjeux de l’informatique appliquée à l'étude des virus

## [Accueil](https://www.telecom-paris.fr "https://www.telecom-paris.fr") > [fr](https://www.telecom-paris.fr/fr "fr") > [Ideas](https://www.telecom-paris.fr/fr/ideas "Ideas") > [La bioinformatique : l’informatique appliquée à l’étude des virus](https://www.telecom-paris.fr/fr/ideas/bioinformatique-etude-virus)

[](https://www.telecom-paris.fr/fr/accueil)

# Télécom Paris Ideas  
La bioinformatique : l’informatique appliquée à l'étude des virus

## La bioinformatique : les enjeux de l’informatique appliquée à l’étude des
virus

[Pauline Rocu](https://www.linkedin.com/in/pauline-rocu-544016197), diplômée
de Télécom Paris, chargée de mission sobriété numérique à l’ADEME (Agence de
l’Environnement et de la Maîtrise de l’Énergie), sept. 2024.

  
Les recherches de Pauline Rocu ont porté sur la modélisation de la diffusion
géographique d’un virus à partir de son arbre phylogénétique.

Elle est co-autrice de trois articles en bioinformatique portant sur des
recherches auxquelles elle a contribué dans le cadre de son stage de fin
d’études dans trois laboratoires à Montpellier, financé par l’ICIT-MUSE,
programme de l’université de Montpellier.

  * 

Propos recueillis par Isabelle Mauriac

## Bioinformatique et phylogéographie

— Nous allons commencer par définir ce qu’est la bioinformatique et quelles
sont les applications et les enjeux de cette informatique appliquée au vivant.
Je précise que vos recherches portent sur la modélisation de la diffusion
spatiale d’un virus à partir de son arbre phylogénétique et que la
phylogénétique est une branche de la bioinformatique. Comment définir la
bioinformatique ?

La bioinformatique, un domaine très large, est l’application des mathématiques
et de l’informatique aux sciences biologiques. C’est une manière de résoudre
un problème ou une question biologique, par exemple comme la diffusion d’une
espèce, le diagnostic de maladies ou la diffusion d’un virus qui sont étudiées
grâce à l’informatique ou aux mathématiques.

Cela fait aujourd’hui appel à des calculs de plus en plus complexes car les
données sont très hétérogènes. On essaie de modéliser du vivant qui par
définition, est très complexe. C’est tout à fait en lien avec la base
scientifique acquise ici à Télécom Paris.

  * 

— Vous avez travaillé plus précisément sur la phylogéographie, une sous-
catégorie qui vise à reconstruire l’arbre phylogénétique, ici d’un virus en
prenant en compte sa diffusion spatiale. Pouvez-vous nous expliquer ce que
c’est ?

La phylogéographie associe phylogénétique et géographie. D’un côté, en lien
les coordonnées spatiales et de l’autre, la reconstruction des liens de
parenté au sein d’une espèce ou entre plusieurs espèces. Les liens de parenté
ici ne correspondent pas aux ancêtres, comme pour un arbre généalogique . Ici
sont étudiés des liens de proximité génétique entre les différentes espèces.
Pour le résumer, la phylogéographie consiste à reconstruire l’arbre
phylogénétique d’une espèce, c’est-à-dire les différents liens de parenté
génétique au centre de cette espèce et annoter les coordonnées géographiques
des positions de chacun des individus.

— Beaucoup de projets bioinformatiques utilisent l’IA. Dans ces rechercles en
phylogéographie, vous vous êtes basée sur des méthodologies de statistiques
bayésiennes et non sur de l’IA, pourriez-vous nous expliquer pourquoi ?

Les statistiques bayésiennes sont une autre manière de faire des statistiques.
Il est tout à fait possible de faire de l’intelligence artificielle sur des
logiques de statistiques bayésiennes. Mais dans le cas de ce projet, nous
avons simplement utilisé des modélisations de statistiques bayésiennes sans
faire intervenir l’intelligence artificielle. Ce choix a été fait parce que la
reconstruction d’arbre phylogénétique s’effectue à partir d’observations
réelles : on va sur le terrain, on sélectionne des échantillons du virus(…) et
on cherche à reconstruire à partir de ces données d’observation réelles quels
étaient les ancêtres les plus probables. Cela se reconstruit très bien par
statistiques bayésiennes et permet aussi d’intégrer justement les paramètres
géographiques à cette reconstruction. C’est la modélisation aujourd’hui la
plus courante.

## Modéliser la diffusion d’un virus

— Venons-en maintenant à votre sujet d’étude et à ces trois publications : il
est question du virus de la panachure jaune et qui touche le riz, ainsi que de
sa diffusion en Afrique de l’Est.

  
En effet, au cours de mon stage, nous avons étudié la diffusion du virus de la
panachure jaune du riz en Afrique. C’est un virus uniquement présent en
Afrique et sur l’île de Madagascar. On ne comprend pas forcément pourquoi il
n’est pas présent sur les autres continents pour le moment, mais en Afrique
c’est un vrai enjeu de souveraineté alimentaire du continent puisque, quand le
riz est touché, la perte de rendement va de 25 à 100%. Il est donc très utile
d’étudier la diffusion du virus pour comprendre tout simplement son
comportement. Pendant mon stage, j’ai étudié vraiment de manière plus précise
la diffusion en Afrique de l’Est, parce que le virus, originaire d’Afrique de
l’Est, se serait diffusé ensuite en Afrique de l’Ouest et encore plus
tardivement à Madagascar. Il y a eu des études de reconstructions
phylogéographiques assez détaillées sur l’Afrique de l’Ouest et sur Madagascar
mais il n’y en avait pas encore eu sur l’Afrique de l’Est. Grâce à un nouveau
jeu de données, il a été possible d’aller un peu plus en profondeur sur la
diffusion du virus en Afrique de l’Est pour mieux comprendre d’où venait le
virus et comment il s’était diffusé. Cela a donné lieu à un premier article.

— Et qu’avez-vous découvert au sujet des statistiques portant sur la vitesse
justement ?

  
Pour caractériser la diffusion de différents virus, on utilise effectivement
des statistiques – on pourrait appeler ça aussi des métriques-, qui permettent
de caractériser la diffusion spatiale du virus. Cela va être, par exemple, sa
vitesse de diffusion, ou bien le coefficient de diffusion, c’est-à-dire à quel
point le virus va se propager sur des surfaces en peu de temps. Ces
statistiques de diffusion sont très regardées par les épidémiologistes pour
caractériser justement la diffusion des virus. Mais comme on a assez peu de
recul sur ces statistiques aujourd’hui, on les utilise pour caractériser les
virus sans vraiment savoir si ce sont des métriques robustes ou non.

C’est pourquoi, au cours de mon stage, nous avons cherché à voir si la vitesse
notamment, ou le coefficient de diffusion, est robuste à l’échantillonnage.

  * 

Mesurer ces vitesses est en fait assez simple, il suffit de faire la moyenne
des distances parcourues sur le temps écoulé entre l’origine du virus et la
situation actuelle, c’est assez instinctif. Il faudrait que cette métrique ne
soit pas impactée par le nombre de données en entrée. Or, nous nous sommes
rendu compte, en faisant plusieurs tests avec différents jeux de données du
virus de la panachure jaune du riz, que cette vitesse de diffusion est
justement sensible au nombre de données en entrée. C’est problématique parce
que cela signifie que cette statistique n’est pas robuste à l’échantillonnage
et donc ne devrait pas être utilisée systématiquement pour caractériser la
diffusion du virus.

— Donc vous avez réfléchi à une nouvelle façon de caractériser la vitesse ;
vous disiez que c’était très important pour les épidémiologistes de savoir à
quelle vitesse évoluaient les virus. Donc j’imagine qu’il y a un fort enjeu
dans cette nouvelle modélisation mathématique ?

Savoir à quelle vitesse évolue un virus est une problématique importante pour
les épidémiologistes, parce qu’un virus qui se diffuse rapidement va sûrement
être beaucoup plus dangereux et beaucoup plus regardé qu’un virus qui se
déplace peu rapidement. Donc ces travaux nous ont amenés à réfléchir à une
nouvelle manière de modéliser la vitesse puisqu’ici nous avions une simple
moyenne, finalement, de la distance parcourue sur le temps total écoulé depuis
l’origine du virus. Or, avec la modélisation mathématique de notre modèle,
nous avons accès aux positions du virus au cours du temps, en faisant
justement la reconstruction phylogéographique. La première intuition pourrait
être de dériver la position pour obtenir la vitesse instantanée (c’est souvent
ce qui est fait en physique). Sauf qu’avec le modèle mathématique mis en
place, il n’est pas possible de procéder ainsi. Donc cela nous a amenés à
penser à un nouveau modèle : au lieu de modéliser la diffusion de la position
le long de l’arbre phylogénétique, nous avons plutôt cherché à modéliser la
diffusion de la vitesse le long de cet arbre…

… donc à reconstruire la vitesse instantanée du virus tout au long de sa
diffusion et à intégrer la vitesse pour obtenir la position, car il est
possible de le faire avec le modèle mathématique. Un article a été publié à
propos de cette modélisation prometteuse.

  * 

## Intérêt pour l’épidémiologie

— Ce travail s’est déroulé au moment de l’épidémie de Covid-19 ; je me demande
si cela a influencé ou stimulé vos recherches et, d’une façon générale, si la
phylogéographie est utilisée pour caractériser la diffusion du Covid ?
J’imagine qu’énormément de modèles sont sortis à ce moment-là, quels sont les
liens entre les deux ?

En effet, la phylogéographie est un domaine assez récent en bioinformatique.
Mon stage a eu lieu un an ou deux après le début de l’épidémie et le Covid a,
je pense, donné pas mal d’importance à ce sujet puisque cela fait partie des
modélisations qui ont permis de comprendre d’où venait le virus et d’en
refaire sa diffusion, justement pour essayer de revenir jusqu’à l’origine du
virus et de comprendre comment il avait évolué. Après, les modélisations
n’étaient pas exactement les mêmes, ici on suppose que le virus évolue de
manière continue, alors que pour le Covid, de mémoire, on a plutôt une
modélisation discrète. Mais cela reste du domaine de la phylogéographie.

— Quelle est la situation actuelle de ces recherches sur la panachure jaune et
en quoi permettent-elles de contrôler ce virus, voire d’autres maladies
virales ?

Aujourd’hui plusieurs études permettent de vraiment comprendre le comportement
de ce virus. Une étude est publiée sur le virus en Afrique de l’Ouest, une
autre sur Madagascar, et donc très récemment une qui montre son évolution en
Afrique de l’Est. On commence donc à avoir une bonne idée de la manière dont
se comporte ce virus.

Les dernières conclusions intéressantes montrent que l’humain a un rôle très
important dans la propagation de ce virus.

  * 

Ce virus touche des plantes, donc a priori savoir comment il se diffuse de
proche en proche n’est pas forcément évident, puisque les plantes, elles, ne
bougent pas. Nous considérons de ce fait que le transport des grains à travers
l’Afrique a été un vrai vecteur de transmission de ce virus et, en comprenant
comment il a évolué, il sera possible de détecter par exemple les zones à
risque dans l’avenir et donc éviter d’y planter des cultures qui seraient
vraiment en grand danger. Cela va aussi permettre de mieux s’adapter à ce
virus et de mieux le contrôler, par exemple grâce à des stratégies de
développement de plantes peut-être plus résistantes à ce virus.

## Vidéo

Pour afficher ce contenu, merci d’accepter les cookies des vidéos Youtubedes
extraits de réseaux sociaux (Twitter, Instagram & Facebook).To display this
content, please accept third party cookies for Youtube videosFacebook,
Instagram and Linkedin excerpts.

Réglages

Vidéo Michel Desnoues, Télécom Paris

[](https://www.telecom-paris.fr/fr/ideas/sommaire)

