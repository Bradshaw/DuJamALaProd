Le prototypage en phases de design
==================================


## Ressources
[Brian van Bruggen on rapid prototyping for games](http://www.brianvanbruggen.com/?page=rapid_prototyping)   
[Map in creation for TF2](http://forums.tf2maps.net/showthread.php?t=5196)



## Segments

### Formalisation du prototypage

#### La Feuille de prototype

> Concept:   
> Proposition:   
> Restrictions:   
> Technologies à utiliser:   
> Temps de developement:   
> Temps de test:   
> Nombre de testeurs:   
> Résultat:   
> Verdict:   

Exemple:

> Concept: *Voler et aller vite sont kinesthetiquement plaisants, et rendre ce gameplay simple et accessible peut être intéressant*   
> Proposition: *Le personnage-joueur avance en continu, le joueur peut contrôler la direction, le level design encourage le fait de passer près d'autres objets, et des bonus de vitesse accélèrent le joueur*   
> Restrictions: Doit être jouable sur Kinect   
> Technologies à utiliser: *Unity3D*   
> Temps de developement: *Une semaine*   
> Temps de test: *Une journée*   
> Nombre de testeurs: *Quatre*   
> Résultat: *Les joueurs aiment la sensation de vitesse, mais perdent rapidement le contrôle, et n'arrivent pas à retrouver le chemin*   
> Verdict: *Reprototypage à faire: Auto-piloter le joueur en cas de sortie de chemin*      


#### La feuille de questions

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




#### Assets neutres

![cp_orange_hideout](http://www.tbrmaps.com/pictures/tf2/cp_orange_hideout_v1/cp_orange_hideout_v10004.jpg)

Chez Valve, les maps sont créés avec des assets graphiques neutres, qui permettent de se focaliser sur le gameplay plutôt que le joli. Ces assets sont disponibles facilement, ont une texture quadrillée et éxistent en différents couleurs. Le quadrillage donne une texture à l'asset, qui permet de mieux distinguer les distances à la caméra, mais sans être distrayants. Les couleurs sont souvent utilisées de façons codéfiées, par éxemple pour TF2, gris pour les sols, orange pour les murs et autres impassibles, bleu et rouges pour désigner les parties de la map qui appartiennent à l'une équipe ou l'autre. Les seuls éléments "artistiques" sont les portes, packs de munition et de vie, et points de contrôles. D'une part parce que ces éléments sont communs à tous les maps, et les joueurs ont appris à les reconnaitre symboliquement, et d'autre part parce que le style différent permet d'identifier que ces objets sont "différents" et importants.




### Pourquoi une idée peut ne pas marcher, et comment réagir...


#### Certaines idées fonctionnent tout simplement pas lorsqu'ils sont testés.

Un éxemple de jeu basé sur une idée qui parait bonne mais qui ne l'est finalement pas est Shattered Horizon. Dans Shattered Horizon, les développeurs ont proposé un shooter proche de Call of Duty, mais en apesanteur. Les degrés de liberté supplémentaires sont censés offrir des possibilités tactiques et stratégiques supplémentaires. Dans l'ésprit du concepteur, le champ de bataille devient plus dynamique, il a trouvé une solution à la stagnation qui a atteint le genre du FPS.

![Où est-il?](http://i882.photobucket.com/albums/ac26/Hayabusa85Screens/Shattered%20Horizon/shattered_horizon2009-12-0215-45-28.jpg)
*Où est l'ennemi? Si ça se trouve il est au-dessus ou en-dessous...*

Mais en jeu, Shattered Horizon ennuit rapidement. Les batailles n'ont que peu de direction et de stratégie, et on se retrouve dans des fusillades désordonnées, il devient difficile de comprendre d'où le danger vient, et les adversaires qu'on arrive à toucher ne sont généralement pas conscients de notre position, et ne peuvent donc pas réagir en conséquence.
Un minimum de playtest, en se posant les bonnes questions, auraient peut-être suffi à remettre en question un design prometteur mais bancal.


#### Il est difficile de communiquer certains concepts

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