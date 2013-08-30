# Notes

## Thèmes à explorer

### Prototyper pour valider ses idées

+ Faire des hypothèses c'est bien, les tester c'est mieux
  + On pense savoir ce qui fait un bon design
  + Parfois un bonne idée est difficile à communiquer
    + Aux autres devs
    + Aux joueurs
  + Parfois une bonne idée ne l'est pas tant que ça
+ Un prototype de validation doit répondre à des questions simples
  + Est-ce compréhensible?
  + Est-ce intuitif?
  + Est-ce trop facile / trop dur?
  + Est-ce amusant?
+ Une validation est un "OUI" à toutes ces questions
+ Un reprototypage est utile si on a des "OUI, mais..." ou quelques "NON"
  + Comment mieux communiquer l'idée aux devs?
  + Comment mieux communiquer l'idée aux joueurs?
  + Comment rendre plus accéssible ou construire des challenges?
  + Est-ce que le potentiel d'amusement est simplement mal exploité?
+ un prototype est rejeté s'il n'y a pas de réponses concrètes à ces questions.

### Prototyper pour trouver de nouvelles idées

+ Pendant des phases de prototypage, sortir si possible de ses habitudes.
  + Utiliser une technologie nouvelle
  + Imiter des éléments d'un autre jeu
  + Mélanger genres et concepts
+ Confronter son prototype aux regards
  + " Ce serait sympa si ... "
  + " Pourquoi ça fait ...? "
  + Tout noter, comment tester ces suggestions?
+ Reprototyper avec les suggestions

### Coûts du prototypage: Fatigue et sentiment d'inutilité

+ Fatigue
  + Prototyper c'est un travail "intense"
  + De la conception en continu
  + Peu de vision à l'avenir = difficulté de motivation
+ Sentiment d'inutilité
  + Un bon prototype est crée pour être jeté
    + Un proto qu'on ne jète pas souffre facilement de conception "spaghetti"
    + Avoir une vision d'avenir sur du proto ralentit son développement
  + Pourquoi coder si c'est pour tout jeter?
  + Pourquoi la plupart de mes idée finissent par être rejetées?

### Optimiser la valeur, Diminuer le coût

+ Formaliser le processus de prototypage
  + Feuille de prototype
    + Hypothèse à vérifier / Concept à explorer
    + Proposition de prototype
    + Création AdHoc d'un prototype
    + Phase de test
    + Rincer/Répéter ou passer en production?
  + Avoir des assets "neutres"
    + Un visuel propre et codifié
    + Resister à l'envie de faire du "beau"



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


Certaines idées fonctionnent tout simplement pas lorsqu'ils sont testés.

Un éxemple de jeu basé sur une idée qui parait bonne mais qui ne l'est finalement pas est Shattered Horizon. Dans Shattered Horizon, les développeurs ont proposé un shooter proche de Call of Duty, mais en apesanteur. Les degrés de liberté supplémentaires sont censés offrir des possibilités tactiques et stratégiques supplémentaires. Dans l'ésprit du concepteur, le champ de bataille devient plus dynamique, il a trouvé une solution à la stagnation qui a atteint le genre du FPS.
Mais en jeu, Shattered Horizon ennuit rapidement. Les batailles n'ont que peu de direction et de stratégie, et on se retrouve dans des 