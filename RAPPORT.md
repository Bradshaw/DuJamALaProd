Protowiping
===========
  

## Ressources
[Jonathan Blow (Braid) on prototyping for indies](https://www.youtube.com/watch?v=ISutk1mauPM)   
[Brian van Bruggen on rapid prototyping for games](http://www.brianvanbruggen.com/?page=rapid_prototyping)   
[Map in creation for TF2](http://forums.tf2maps.net/showthread.php?t=5196)   
[The upside of failing](http://www.youtube.com/watch?v=ipbkRxIiWaM)   


## Protowiping

Au moment d'écrire ces lignes, je viens d'effectuer trois mois de stage à Natural Pad, une entreprise qui spécialise dans la conception de jeux sérieux pour la santé. Du fait du caractère innovant et original des demandes dans le milieu du jeu video thérapeutique, mon stage s'est surtout orienté sur des cycles de prototypage pour un nouveau jeu.

Pendant ces trois mois, j'ai pu identifier quelques-uns des difficultés qui peuvent survenir lors des travaux de prototypage, ainsi que formaliser les éléments qui permettent de mener à bien un prototype et d'en profiter au maximum.

### 1/ Pourquoi prototyper?

Un prototype ce n'est pas juste un projet rapidement terminé, c'est un projet qui teste rapidement un concept. Une idée a besoin d'être testée parce qu'elle peut être mauvaise, ou si elle est bonne, elle peut être mal définie, difficile à expliquer ou mal exploitée. Vérifier rapidement la validité d'une idée permet de ne pas perdre du temps, et de tirer le maximum des concepts proposés.

#### 1. Trouver une direction et éviter les pièges

L'esprit d'un développeur de jeu est une machine à travers laquelle filtrent des centaines ou des milliers d'idées. Terriblement efficace et polyvalent, il présente tout de même des désavantages.

##### Même celui qui n'est pas tout seul dans sa tête ne peut pas inviter tout le monde

Lorsqu'on pense à une idée ou un concept, il faut se rendre compte que cette idée est au moins en partie compréhensible seulement parce qu'on est celui qui l'a imaginé. A moins d'être capable de communiquer l'intégralité de sa culture et de ses connaissances, il y a la possibilité que les collègues et les joueurs ne comprennent tout simplement pas.

##### *"Mais dans ma tête ça marchait bien"*

L'imagination humaine est basée sur notre connaissance du monde réel, mais n'est finalement pas une bonne représentation de celle-ci. Par conséquent, il arrive qu'on imagine quelque chose qui paraît très intéressant, et tant qu'on reste dans le domaine de l'imaginaire, on n'en voit pas les limites.

##### Prototyper pour ne pas être victime de ses propres défauts

Le but du prototypage est de rapidement se confronter à la plupart des problèmes qui peuvent se mettre en travers du chemin d'un bon jeu. Que ce soit en écartant les fausses bonnes idées ou en repérant les limites du concept qu'on cherche à exploiter.
Aussi, prototyper une idée permet de mieux la communiquer à ses collègues et de s'assurer que chacun a compris la direction que le concepteur imagine.


#### 2. Exemple: Une bonne idée qui ne l'est pas

Un exemple de jeu basé sur une idée qui parait bonne mais qui ne l'est finalement pas est Shattered Horizon. Dans Shattered Horizon, les développeurs ont proposé un shooter proche de Call of Duty, mais en apesanteur. Les degrés de liberté supplémentaires sont censés offrir des possibilités tactiques et stratégiques supplémentaires. Dans l'esprit du concepteur, le champ de bataille devient plus dynamique, il a trouvé une solution à la stagnation qui a atteint le genre du FPS.

![Où est-il?](http://i882.photobucket.com/albums/ac26/Hayabusa85Screens/Shattered%20Horizon/shattered_horizon2009-12-0215-45-28.jpg)   
<sup>*Shattered Horizon: Où est l'ennemi? Si ça se trouve il est au-dessus ou en-dessous...*</sup>

Mais en jeu, Shattered Horizon ennuit rapidement. Les batailles n'ont que peu de direction et de stratégie, et on se retrouve dans des fusillades désordonnées, il devient difficile de comprendre d'où le danger vient, et les adversaires qu'on arrive à toucher ne sont généralement pas conscients de notre position, et ne peuvent donc pas réagir en conséquence.
Un minimum de playtest, en se posant les bonnes questions, auraient peut-être suffi à remettre en question un design prometteur mais bancal.


#### 3. Exemple: Une bonne idée que personne ne comprend

Parfois une idée peut-être bonne, et offrir un gameplay intéressant, mais être un peu contre-intuitive et donc difficile à communiquer efficacement au joueur.

Deux raisons peuvent exister, soit le mécanisme est inhabituel ou en-dehors de la culture du joueur, soit le mécanisme est trop complexe et nécessite un apprentissage pour être maîtrisable.

Il faut détecter ce problème rapidement, afin de déterminer une solution à appliquer pendant le développement, comme un tutorial, ou mieux, une refonte ou une simplification des mécanismes de jeu.

![Dwarf Fortress: Je vois pas le problème](http://www.pressxordie.com/wp-content/uploads/df-nogfx.jpg)   
<sup>*Dwarf Fortress: Par un dev hardcore, pour un joueur hardcore*</sup>   
    
    
![Rymdkapsel: Déjà c'est plus clair](https://lh3.ggpht.com/MK0sMPxnzvPFxE-YsW1GZeGKv6TJsyps9ucO-trna9n6xT_zrYgJocWYEB-AeADDkQ=h900)   
<sup>*Rymdkapsel: Le base-building pour tous*</sup>   

Dans ce cas, on a aussi une question de cible, un joueur "hardcore", qui sait dans quoi il s'engage, est prêt à faire l'effort de l'apprentissage d'une interface et un gameplay complexes, dans ce cas, simplifier les mécanismes est perçu comme une trahison. La niche visée par des jeux comme Dwarf Fortress apprécie la difficulté de l'interface.

La cible grand public appréciera plutôt un jeu qui introduit sa complexité plus doucement, ceci n'est pas une question de difficulté pure, mais simplement de compréhension de mécanismes. Rymdkapsel est un exemple de cet état d'esprit, en réduisant le jeu de stratégie à ses éléments les plus simples, on obtient un jeu facile d'accès où les joueurs peu expérimentés commencent rapidement à développer leurs tactiques.

Être conscient de la cible et choisir des testeurs qui correspondent est un élément indispensable de la phase de prototypage. Tous les jeux ne sont pas pour tout le monde, par contre plus la cible est réduite, plus il faut être certain que sa cible apprécie le concept, donc obtenir une réaction positive claire très tôt dans le prototypage


### 2/ Coûts du prototypage: Fatigue et sentiment d'inutilité

Si prototyper une idée propose des avantages considérables, il a aussi un coût. Si on veut pouvoir profiter au maximum de cette méthode, il faut être capable de comprendre ces coûts et leurs origines, et être capable de minimiser ou mitiger ces coûts.

#### 1. Fatigue

L'activité de prototypage est particulièrement cérébrale, et si on est dans des phases de prototypage rapide sous forme de jam, on peut facilement se sentir épuisé ou à court de motivation.
Continuer à prototyper dans cet état est rapidement contre-productif. Il faut prendre garde à éviter la situation d'épuisement. Une solution possible est d'entrecouper les cycles de prototypage avec des périodes de réflexion.

##### Périodes de réflexion

Dans le processus de prototypage, on doit mettre en place des périodes ou scéances où on prend du temps pour avoir une activité différente.
Voici quelques exemples de ce que l'on peut faire pendant cette période:
+ Socialiser, rencontrer des gens et discuter du sujet en question
+ Tester d'autres jeux similaires (pas trop de temps à l'écran si possible)
+ Lire livres et bandes-dessinées
+ Se promener en écoutant de la musique

Cette période ne doit bien sûr pas prendre le dessus sur le travail, mais formaliser le besoin de réflechir à autre chose et changer d'air permet d'éviter d'arriver à court de motivation et d'inspiration.


#### 2. Sentiment d'inutilité

Pour qu'un prototype soit utile, il faut qu'il soit créé rapidement, c'est à dire souvent sans trop de considération pour un code réutilisable. Aussi, l'intérêt du prototypage étant de valider ou rejeter des idées, un prototype se retrouve souvent jeté à la poubelle. On se retrouve donc à écrire des programmes entiers qui ne seront souvent jamais utilisés, et même s'ils sont réutilisés, ça ne sera qu'après un refactor, ou préférablement une réécriture.

###### *Pourquoi coder si c'est pour tout jeter?*

Des prototypes de jeux sont finalement quasiment des jeux complets, et ont consommé beaucoup d'effort à la création, on est donc facilement tenté de conserver le prototype tel quel et de l'utiliser comme base de production. Le problème c'est que développer dans cet état d'esprit risque de ralentir le cycle de prototype, et devient problématique lorsqu'on s'attache à son code alors qu'il ne sera peut-être pas utilisé.
Pendant les cycles de prototypage, il faut donc encourager une culture de programmation rapide et ad-hoc. Il faut être dans l'idée que le code ne sera pas réutilisé sous cette forme. Dans tous les cas, le code n'est censé représenter au maximum qu'une semaine de travail, et donc devoir reprogrammer ne coûte que peu de temps.

###### *Pourquoi la plupart de mes idées finissent par être rejetées?*

Le meilleur prototype est celui qui rejette une idée, qui falsifie ses idées pré-conçues, et remet en question la direction qu'on comptait prendre.
Par conséquent, le meilleur prototype est celui qu'on jette à la poubelle dès qu'on l'a testé.
Ceci peut mener à un manque de motivation lorsqu'on se rend compte que certaines, voir parfois la plupart de ses idées et de son temps de développement sera simplement classé "sans suite". Pour qu'une période de prototypage se déroule agréablement et efficacement, il faut réduire cet état d'esprit, et promouvoir l'idée que ce temps "perdu" est réellement un gain. Cet effort se traduit à la longue à un gain de temps, d'argent et de qualité de produit final.
Il est donc important d'inclure dans la méthodologie des mécanismes qui permettent au developpeur de pouvoir constater rapidement l'intérêt du travail, et de se sentir valorisé quand l'idée testée est finalement rejetée.


### 3/ Optimiser la valeur, Diminuer le coût

Voici donc quelques éléments et une méthodologie qui devraient aider à maximiser les avantages d'une session de prototypage tout en minimisant les effets négatifs que peuvent ressentir les développeurs.

#### 1. La feuille de contexte

La feuille de contexte sert essentiellement pour aider à définir le projet dans ces grandes lignes. Garder le contexte en tête pendant tout le processus est important pour être capable de créer les prototypes qui iront dans la bonne direction, et être capable des les évaluer correctement.

> Cible:   
> Plateformes:   
> Modes d'interaction:   
> Références:   



#### 2. La feuille de questions

Avant la création du prototype, une feuille de questions (3 à 6 questions environ) est créé. Ces questions seront posées lors de la phase de test, et permettront à la fois d'évaluer la pertinance du prototype vis-à-vis du concept, mais aussi la viabilité de ce même concept.

Exemple:

> ##### Est-ce que les joueurs comprennent le mécanisme?   
> Oui, c'est assez simple, il n'y a que deux axes à gérer    
> Cependant, les commandes Kinect ne sont pas intuitives

> ##### Est-ce que les joueurs arrivent à contrôler efficacement le personnage?   
> Non, les commandes Kinect ne sont pas adaptées
> Parfois les joueurs s'écartent de la piste et se perdent

> ##### Est-ce que les joueurs ont la sensation de vitesse?   
> Oui, quand ils arrivent à jouer, ils ont l'impression d'aller même trop vite, mais réussissent tout de même à continuer

> ##### Quel est le degré de difficulté?   
> Clairement trop difficile, quand les joueurs perdent le contrôle quelques instants, ils sont perdus.

#### 3. La Feuille de prototype

La feuille de prototype est un petit résumé du prototype, servant à condenser et classer les protoypes qui seront créés.

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

> Concept: *Voler et aller vite est plaisant du point de vue kinesthésique, et rendre ce gameplay simple et accessible peut être intéressant*   
> Proposition: *Le personnage-joueur avance en continu, le joueur peut contrôler la direction, le level design encourage le fait de passer près d'autres objets, et des bonus de vitesse accélèrent le joueur*   
> Restrictions: *Doit être jouable sur Kinect*   
> Technologies à utiliser: *Unity3D*   
> Temps de cycle: *Une semaine*   
> Temps de test: *Une journée*   
> Nombre de testeurs: *Quatre*   
> Résultat: *Les joueurs aiment la sensation de vitesse, mais perdent rapidement le contrôle, et n'arrivent pas à retrouver le chemin*   
> Verdict: *Reprototypage à faire: Auto-piloter le joueur en cas de sortie de chemin*      




#### 4. Assets neutres

![cp_orange_hideout](http://www.tbrmaps.com/pictures/tf2/cp_orange_hideout_v1/cp_orange_hideout_v10004.jpg)   
<sup>*Team Fortress 2: Une carte avec des assets neutres*</sup>

Chez Valve, les maps sont créés avec des assets graphiques neutres, qui permettent de se focaliser sur le gameplay plutôt que l'aspect visuel. Ces assets sont disponibles facilement, ont une texture quadrillée et existent en différentes couleurs. Le quadrillage donne une texture à l'asset, qui permet de mieux distinguer les distances à la caméra, mais sans être distrayants. Les couleurs sont souvent utilisées de façon codifiée, par exemple pour TF2, gris pour les sols, orange pour les murs et autres impassibles, bleu et rouge pour désigner les parties de la map qui appartiennent à l'une ou l'autre des équipes. Les seuls éléments "artistiques" sont les portes, packs de munitions et de vie, et points de contrôle. D'une part parce que ces éléments sont communs à toutes les maps, et les joueurs ont appris à les reconnaitre symboliquement, et d'autre part parce que le style différent permet d'identifier ces objets en tant qu'éléments spécifiques et importants.


![Red vs Blu](https://dl.dropboxusercontent.com/u/6549099/redvblu.gif)   
<sup>*Prototype en 4 heures, assets neutres abstraits*</sup>

Un asset "neutre" est un asset qui est facilement accéssible et qui parle immédiatement au joueur, sans impliquer forcément un univers. Il y a donc deux sortes d'assets neutres.
La première sorte est réellement neutre, une texture quadrillée et une couleur par exemple. Ce genre d'asset est utile pour créer un niveau global, des couleurs comme vert et rouges peuvent indiquer bien/pas bien. Ou deux couleurs pour indiquer l'appartenance à une équipe. Nous appellerons ce genre d'asset un "asset abstrait".


![Health Kit](http://farm7.static.flickr.com/6130/5958721116_c248a54de1_o.jpg)   
<sup>*Devinez ce que fait cet objet*</sup>

Une autre sorte d'asset est ce qu'on appellera "asset symbolique". Ce genre d'asset, par une culture "globale" indique clairement au joueur un rôle bien défini. On peut profiter de cette lecture universelle pour communiquer des éléments de gameplay sans avoir à les expliquer. Un fusil, un ballon et une cage de foot, ou le kit de premier soins, sont tous des objets qu'un joueur comprendra "intuitivement". Il est donc important de créer une banque d'assets de ce genre afin de pouvoir les utiliser dans un prototype.
Le "style" de ces assets symboliques n'est pas important, idéalement on utilise des assets qui sont suffisamment neutres pour ne pas indiquer un univers ou une histoire, ils servent uniquement à communiquer des fonctions de jeu.

#### 5. Proposition - [25%|50%|25%]

Voici donc la marche à suivre pour mener une session de prototypage grâce à la méthodologie Protowiping.

##### Step wan: Prep (25%)
S'imbiber de références et noter des idées. Se promener en ville ou à la campagne, jouer à des jeux similaires en concept, noter les idées intéressantes sur papier libre.

##### Step too: Dev (50%)
Se mettre en mode "jam", trouver rapidement une idée à exploiter, et remplir la feuille de prototype ainsi que la feuille de questions.
+ Créer le prototype.
+ Le jeu doit être jouable et présenter clairement le concept.
+ Tout autre élément est à laisser si ça n'aide pas à comprendre et évaluer le concept.
+ Graphismes minimum (utiliser un pack d'asset standards)
+ Pas d'histoire
+ Eviter les éléments de HUD qui ne sont pas essentiels au gameplay
+ De même, ne pas formaliser de mécanismes d'échec ou de réussite si ce n'est pas dans la problématique du prototype

##### Step tree: Test (25%)
Faire tester le proptotype par un maximum de personnes :
+ Expliquer les règles
+ Expliquer au joueur qu'il doit parler en jouant
+ Pendant que le joueur joue, ne pas répondre s'il pose des questions ou fait des remarques
+ Un court entretien, discuter des expériences de jeu avec le testeur
+ Guider la conversation vers les sujets abordés par les questions
+ Ecouter tout de même les remarques "hors sujet" du testeur et les noter
+ Pendant l'entretien, laisser le jeu lancé et disponible pour l'encourager à montrer ce qu'il veut expliquer
+ Noter s'il rejoue naturellement par lui-même
+ Ne jamais lui prendre la manette
+ Après la session, répondre aux questions choisies sur la feuille de questions.

Après les tests, établir le verdict. Faut-il continuer à exploiter l'idée? Reste-t-il des éléments qui ont besoin d'être testés en prototype?
Décider des modalités de la prochaine étape (Nouveau cycle de prototypage ou passage en production)

#### 6. Durée

Ce cycle peut être sur un laps de temps allant de 4 jours (1 jour prep, 2 jours dev, 1 jour test) à deux semaines (fin de semaine prep, une semaine dev, début de la semaine test, à enchaîner derrière).

Les cycles courts peuvent être utilisés pour tester des gameplays simples ou des améliorations de produits existants. Les cycles longs sont plus utiles pour le développement de prototypes de jeux "complets".

La période prep est utile pour se vider l'esprit avant d'attaquer le prototype, ce n'est pas forcément essentiel si on ne fait qu'un ou deux cycles.
Cependant, le prototypage étant un exercice assez intense, la fatigue peut rendre moins efficace à terme, il faut donc prendre ses précautions en mettant du temps de prep de coté pour éviter l'épuisement et maintenir ses facultés.
