Protowiping
===========
  

## Ressources
[Brian van Bruggen on rapid prototyping for games](http://www.brianvanbruggen.com/?page=rapid_prototyping)   
[Map in creation for TF2](http://forums.tf2maps.net/showthread.php?t=5196)


## Building

### 1/ Pourquoi prototyper?

#### 1. Trouver une direction et éviter les pièges

L'ésprit du développeur du jeu est une machine à travers laquelle filtrent des centaines ou des milliers d'idées, terriblement efficace et polyvalent, il présente tout de même des désavantages.

##### Même celui qui n'est pas tout seul dans sa tête ne peut pas inviter tout le monde

Lorsqu'on pense à une idée ou un concept, il faut se rendre compte que cette idée est au moins en partie compréhensible seulement parce qu'on est celui qui l'a imaginé. A moins d'être capable de communiquer l'intégralité de sa culture et de ses connaissances, il y a la possibilité que ses collègues et que ses testeurs ne comprennent tout simplement pas.

##### *"Mais dans ma tête ça marchait bien"*

L'imagination humaine est basée sur notre connaissance du monde réel, mais n'est finalement pas une bonne représentation de celle-ci. Par conséquent, il arrive qu'on imagine quelque chose qui paraît très intéressant, et tant qu'on reste dans le domaine de l'imaginaire, on n'en voit pas les limites.

##### Prototyper pour ne pas être victime de ses propres défauts

Le but du prototypage est de rapidement se confronter à la plupart des problèmes qui peuvent se mettre en travers du chemin d'un bon jeu. Que ce soit en écartant les fausses bonnes idées ou en repérant les limites du concept qu'on cherche à exploiter.
Aussi, prototyper une idée permet de mieux la communiquer à ses collègues et s'assurer que chacun a compris la direction que le concepteur imagine.


#### 2. Exemple: Une bonne idée qui ne l'est pas

Un éxemple de jeu basé sur une idée qui parait bonne mais qui ne l'est finalement pas est Shattered Horizon. Dans Shattered Horizon, les développeurs ont proposé un shooter proche de Call of Duty, mais en apesanteur. Les degrés de liberté supplémentaires sont censés offrir des possibilités tactiques et stratégiques supplémentaires. Dans l'ésprit du concepteur, le champ de bataille devient plus dynamique, il a trouvé une solution à la stagnation qui a atteint le genre du FPS.

![Où est-il?](http://i882.photobucket.com/albums/ac26/Hayabusa85Screens/Shattered%20Horizon/shattered_horizon2009-12-0215-45-28.jpg)
*Shattered Horizon: Où est l'ennemi? Si ça se trouve il est au-dessus ou en-dessous...*

Mais en jeu, Shattered Horizon ennuit rapidement. Les batailles n'ont que peu de direction et de stratégie, et on se retrouve dans des fusillades désordonnées, il devient difficile de comprendre d'où le danger vient, et les adversaires qu'on arrive à toucher ne sont généralement pas conscients de notre position, et ne peuvent donc pas réagir en conséquence.
Un minimum de playtest, en se posant les bonnes questions, auraient peut-être suffi à remettre en question un design prometteur mais bancal.


#### 3. Exemple: Une bonne idée que personne ne comprend

Parfois une idée peut-être bonne, et offrir un gameplay intéressant, mais être un peu contre-intuitif et donc difficile à communiquer éfficacement au joueur.

Deux raisons peuvent éxister, soit le méchanisme est inhabituel ou en-dehors de la culture du joueur, soit le mechanisme est trop complexe et nécéssite un apprentissage pour être maîtrisable.

Pour résoudre ces problèmes, on peut soit fournir un tutoriel ou des explications, soit revoir les mechanismes afin de simplifier ou rapprocher d'un gameplay plus familier.

![Dwarf Fortress: Je vois pas le problème](http://www.pressxordie.com/wp-content/uploads/df-nogfx.jpg)  
*Dwarf Fortress: Par un dev hardcore, pour un joueur hardcore*  

![Rymdkapsel: Déjà c'est plus clair](https://lh3.ggpht.com/MK0sMPxnzvPFxE-YsW1GZeGKv6TJsyps9ucO-trna9n6xT_zrYgJocWYEB-AeADDkQ=h900)  
*Rymdkapsel: Le base-building pour tous*  

Dans ce cas, on a aussi une question de cible, un joueur "hardcore", qui sait dans quoi il s'engage, est prêt à faire l'effort de l'apprentissage d'une interface et un gameplay complexes, dans ce cas, simplifier les mechanismes est perçu comme une trahison. La niche visée par des jeux comme Dwarf Fortress apprécient la difficulté de l'interface.

La cible grand public appréciera plutôt un jeu qui introduit sa complexité plus doucement, ceci n'est pas une question de difficulté pure, mais simplement de compréhension de méchanismes. Rymdkapsel est un éxemple de cet état d'esprit, en réduisant le jeu de stratégie à ces éléments les plus simples, on obtient un jeu facile d'accès où les joueurs peu expérimentés commencent rapidement à developper leurs tactiques.

Être conscient de la cible et choisir des testeurs qui corréspondent est un élément indispensable de la phase de prototypage. Tous les jeux ne sont pas pour tout le monde, par contre plus la cible est réduite, plus il faut être certain que sa cible apprécie le concept, donc obtenir une réaction positive claire très tôt dans le prototypage


### 2/ Coûts du prototypage: Fatigue et sentiment d'inutilité

#### 1. Fatigue

L'activité de prototypage est particulièrement cérébral, et si on est dans des phases de prototypage rapide sous forme de jam, on peut facilement se sentir épuisé ou à court de motivation.
Continuer à prototyper dans cet état est rapidement contre-productif. Il faut prendre garde à éviter et detecter la situation d'épuisement.

##### Périodes de réflexion

Dans le processus de prototypage, on doit mettre en place des périodes ou scéances où on prend du temps pour avoir une activité différente.
Voici quelques choses qu'on peut faire pendant cette période:
+ Socialiser, rencontrer des gens et discuter du sujet en question
+ Tester d'autres jeux similaires (pas trop de temps à l'écran si possible)
+ Lire livres et bandes-déssinées
+ Se promener en écoutant de la musique
Cette période ne doit bien sûr pas prendre le dessus sur le travail, mais formaliser le besoin de réflechir à autre chose et changer d'air permet d'éviter d'arriver à court de motivation et d'inspiration.


#### 2. Sentiment d'inutilité

Pour qu'un prototype soit utile, il faut qu'il soit créé rapidement, c'est à dire souvent sans trop de considération pour un code réutilisable. Aussi, l'intérêt du prototypage étant de valider ou rejeter des idées, un prototype se retrouve souvent jeté à la poubelle. On se retrouve donc à écrire des programmes entier qui ne seront souvent jamais utilisés, et même s'ils sont réutilisées, ça ne sera qu'après un refactor, ou préférablement une réécriture.

###### *Pourquoi coder si c'est pour tout jeter?*

Des prototypes de jeux sont finalement quasiment des jeux complets, et ont consommés beaucoup d'effort à la création, on est donc facilement tenté de conserver le prototype tel quel et l'utiliser comme base de production. Le problème c'est que développer dans cet état d'esprit risque de ralentir le cycle de prototype, et devient problèmatique lorsqu'on s'attache à son code alors qu'il ne sera peut-être pas utilisé.
Pendant les cycles de prototypage, il faut donc encourager une culture de programmation rapide et ad-hoc. Il faut être dans l'idée que le code ne sera pas réutilisé sous cette forme. Dans tous les cas, le code n'est censé représenter au maximum qu'une semaine de travail, et donc devoir reprogrammer ne coûte que peu de temps.

###### *Pourquoi la plupart de mes idées finissent par être rejetées?*

Le meilleur prototype est celui qui rejette une idée, qui falsifie ses idées pré-conçues, et remet en question la direction qu'on comptait prendre.
Par conséquent, le meilleur prototype est celui qu'on jette à la poubelle dès qu'on l'a testé.
Ceci peut mener à un manque de motivation lorsqu'on se rend compte que certaines, voir parfois la plupart de ses idées et de son temps de développement sera simplement classé et rangé "sans suite". Pour qu'une période de prototypage se déroule agréablement et efficacement, il faut réduire cet état d'esprit, et promouvoir l'idée que ce temps "perdu" est réelement un gain. Cet effort se traduit à la longue à un gain de temps, d'argent et de qualité de produit final.
Il est donc important d'inclure dans la méthodologie des mechanismes qui permettent au developpeur de pouvoir constater rapidement l'intérêt du travail, et de se sentir valorisé quand l'idée testée est finalement rejetée.


### 3/ Optimiser la valeur, Diminuer le coût

#### 1. La Feuille de prototype

> Concept:   
> Proposition:   
> Restrictions:   
> Technologies à utiliser:   
> Temps de cycle:   
> Temps de test:   
> Nombre de testeurs:   
> Résultat:   
> Verdict:   

Exemple:

> Concept: *Voler et aller vite sont kinesthetiquement plaisants, et rendre ce gameplay simple et accessible peut être intéressant*   
> Proposition: *Le personnage-joueur avance en continu, le joueur peut contrôler la direction, le level design encourage le fait de passer près d'autres objets, et des bonus de vitesse accélèrent le joueur*   
> Restrictions: *Doit être jouable sur Kinect*   
> Technologies à utiliser: *Unity3D*   
> Temps de cycle: *Une semaine*   
> Temps de test: *Une journée*   
> Nombre de testeurs: *Quatre*   
> Résultat: *Les joueurs aiment la sensation de vitesse, mais perdent rapidement le contrôle, et n'arrivent pas à retrouver le chemin*   
> Verdict: *Reprototypage à faire: Auto-piloter le joueur en cas de sortie de chemin*      


#### 2. La feuille de questions

Les questions ne sont pas à poser aux testeurs, mais c'est au développeur de chercher à y répondre en observant le comportement des joueurs.

Les questions doivent être définies avant la création du prototype, puisque le prototype est conçu pour trouver des réponses à ces questions.

Dans l'example ci-dessus:

> ##### Est-ce que les joueurs comprennent le méchanisme?   
> Oui, c'est assez simple, il n'y a que deux axes à gérer    
> Cependant, les commandes Kinect ne sont pas intuitives

> ##### Est-ce que les joueurs arrivent à contrôler efficacement le personnage?   
> Non, les commandes Kinect ne sont pas adaptées
> Parfois les joueurs s'écartent de la piste et se perdent

> ##### Est-ce que les joueurs ont la sensation de vitesse?   
> Oui, quand ils arrivent à jouer, ils ont l'impression d'aller même trop vite, mais réussissent tout de même à continuer

> ##### Quel est le degré de difficulté?   
> Clairement trop difficile, quand les joueurs perdent le contrôle quelques instants, ils sont perdus.




#### 3. Assets neutres

![cp_orange_hideout](http://www.tbrmaps.com/pictures/tf2/cp_orange_hideout_v1/cp_orange_hideout_v10004.jpg)

Chez Valve, les maps sont créés avec des assets graphiques neutres, qui permettent de se focaliser sur le gameplay plutôt que le joli. Ces assets sont disponibles facilement, ont une texture quadrillée et éxistent en différents couleurs. Le quadrillage donne une texture à l'asset, qui permet de mieux distinguer les distances à la caméra, mais sans être distrayants. Les couleurs sont souvent utilisées de façons codéfiées, par éxemple pour TF2, gris pour les sols, orange pour les murs et autres impassibles, bleu et rouges pour désigner les parties de la map qui appartiennent à l'une équipe ou l'autre. Les seuls éléments "artistiques" sont les portes, packs de munition et de vie, et points de contrôles. D'une part parce que ces éléments sont communs à tous les maps, et les joueurs ont appris à les reconnaitre symboliquement, et d'autre part parce que le style différent permet d'identifier que ces objets sont "différents" et importants.

#### 4. Proposition - [25%|50%|25%]

##### Step wan: Prep (25%)
S'imbiber de références et noter des idées. Se promener en ville ou à la campagne, jouer à des jeux similaires en concept, noter les idées intéressantes sur papier libre.

##### Step too: Dev (50%)
Se mettre en mode "jam", trouver rapidement une idée à exploiter, et remplir la feuille de prototype ainsi que la feuille de questions.
+ Créer le prototype.
+ Le jeu doit être jouable et présenter clairement le concept.
+ Tout autre élément est à laisser si ça n'aide pas à comprendre et évaluer le concept.
+ Graphismes minimum (utiliser un pack d'asset standards)
+ Pas d'histoire
+ Compteur de score et de vies uniquement pour encourager le gameplay recherché

##### Step tree: Test (25%)
Faire jouer le prototype au maximum de gens:
+ Expliquer les règles
+ Expliquer que le joueur doit parler en jouant
+ Pendant que le joueur joue, ne pas répondre s'il pose des questions ou fait des remarques
+ Un court entretien, discuter des experiences de jeu avec le testeur
+ Guider la conversation vers les sujets abordées par les questions
+ Ecouter tout de même les remarques "hors sujet" du testeur et les noter
+ Pendant l'entretien, laisser le jeu lancé et disponible pour l'encourager à montrer ce qu'il veut expliquer
+ Noter s'il rejoue naturellement par lui-même
+ Ne pas lui prendre la manette
+ Après la session, répondre aux questions décidées sur la feuille de questions.

Après les tests, établir le verdict. Faut-il continuer à exploiter l'idée? Reste-t-il des éléments qui ont besoin d'être testés en prototype?
Décider des modalités de la prochaine étape (Nouveau cycle de prototypage ou passage en production)

#### 5. Durée

Ce cycle peut être sur un laps de temps allant de 4 jours (1 jour prep, 2 jours dev, 1 jour test) à deux semaines (fin de semaine prep, une semaine dev, début de la semaine test, à enchaîner derrière).

Les cycles courts peuvent être utilisés pour tester des gameplays simples ou des améliorations de produits éxistants. Les cycles longs sont plus utiles pour le développement de prototypes de jeu "complets".

La période prep est utile pour se vider l'esprit avant d'attaquer le prototype, ce n'est pas forcément éssentiel si on ne fait qu'un ou deux cycles.
Cependant, le prototypage étant un exercice assez intense, la fatigue peut rendre moins éfficace à terme, il faut donc prendre ses précautions en mettant du temps de prep de coté pour éviter l'épuisement et maintenir ses facultés.



