Formattage :
    Questions en style heading3
    Réponses en style normal
    ctrl+shift+c pour effacer la coloration des lignes

###Pour la notation de question : A REVOIR, les notes sont normalisées
    10 points à répartir sur 3 question et 9 questions/réponses à évaluer pour 30 pts.

   * Donc au final ca fait une distrib en 3, 3, 4 que tu répètes 3x pour l'éval phase 3
#Partie 1:
###
###Sur quels raisonnement s'appuient les moteurs d'inférence ? Donnez des exemples    
Sur des raisonnements déductifs.
1. Si Allaite\_ses\_petits alors Mammifère
2. Si A\_des\_plumes alors Oiseau
3. Si Oiseau et non Vole alors Manchot
4. Si Marin et non Mammifère alors Poisson
5. Si Très\_lourd et Mammifère alors Baleine

###Qu'est le Loebner Prize ?
Le Loebner Prize est un prix qui donnera 100000 dollars à la première personne qui présentera un ordinateur passant le test de Turing.

###Dans quel chaînage est-il pertinent d'interagir avec l'utilisateur ? Pourquoi ? 

###Quels sont les problèmes essentiellement rencontrées par les Systèmes Experts ?
la phase de cognition: récupérer la connaissance d'un expert
- Problèmes de vocabulaire, de représentation des connaissances,
- la communication expert-informaticien-machine,
- très lent à mettre en oeuvre si le domaine est vaste

###Expliquer le fonctionnement d’un système expert en chainage arrière ?
Le Raisonnement est guidé par les buts, on part de ce que l'on cherche à établir, on cherche l'ensemble des règles concluant sur ce fait, et recommence de manière récursive de toutes les prémisses trouvées. Lors de chaque étape on remplace un but par une conjonction ou une disjonction de sous-buts. Ne marche que si l'on connaît le but et seulement si les buts sont finis. Si on tombe sur des fait connus on peut demander à l'utilisateur s'il les connaît.

###Qu'est-ce qu'un codage préfixe ?
page 9 du diapo dernier paragraphe.
###
**Dans un système expert, on peut faire du chaînage arrière de plusieurs façons différentes. Lesquelles ? **
Comme le chaînage arrière est un parcours d'arbre récursif, on peut parcourir l'arbre en profondeur ou en largeur.

**Qu'est-ce qui caractérise une explosion combinatoire ? Donnez un exemple.**
Une explosion combinatoire se caractérise par le fait qu'un changement du nombre de données, même minime, peut rendre le problème très difficile ou impossible a résoudre.
L'exemple du cours avec le calcul des chemins en est un bon.

###Quel est la différence entre un régime révocable et un régime irrévocable ?
révocable : chaînage arrière;  irrévocable : chaînage arrière impossible

###Quels sont les quatre éléments composant un système expert ?
La base de faits, la base de règles, le moteur d'inférence ainsi que l'interface reliée vers l'utilisateur.

###Expliquer pourquoi les systèmes experts ont besoin de cogniticien ?

###Comment appelle-t-on le raisonnement derrière la phrase suivante : "Si être un homme implique être mortel, alors si Socrate est un homme, alors Socrate est mortel"
Le Modus-Ponens
###
###Qu'est ce que la base de faits d'un système, et comment évolue t-elle ?
La base de faits est la mémoire du système. Au début, elle contient ce que l'on sait du cas examiné, puis elle est completée par les déductions du moteur d'inférence, ou par les questions posées à l'utilisateur.

###Quelle est la différence entre régime révocable et régime irrévocable ?
En régime révocable, on peut revenir sur la valeur des faits. En régime irrévocable, les fait changent l'état de manière irrévocable.

###À quoi servent les méta-connaissances dans un système expert ?
Elles lui permettent de "réfléchir" sur les faits et règles qu'il manipule.

###Que signifie "Chaînage Avant" dans les systèmes experts ?
Les moteurs a « *chaînage avant* »  partent des faits et règles de la base de connaissance, et tentent de s'approcher des faits recherchés par le problème.
Cela signifie qu'on va essayer de déduire un maximum de faits à partir des faits initiaux et de la base de règles, en espérant qu'un des faits que l'on va déduire sera celui qui nous intéresse.

###Expliquer le fonctionnement d'un système à base de règle
Un système à base de règle, ou système expert, est un logiciel capable de répondre à des questions, en effectuant un raisonnement à partir de faits et de règles connues. Il peut servir notamment comme outil d'aide à la décision.
Un système expert se compose de 3 parties :
- une base de faits
- une base de règles
- un moteur d'inférence.

###Donner un exemple de raisonnement Modus Ponens.
Si Socrate est un homme, alors Socrate est mortel.

###En ayant une base de règles et une base de faits, à l'aide de quoi peut-on générer de nouveaux faits ?
A l'aide d'un moteur d'inférence.

###Quel est en pratique le principal problème lors de l'apprentissage d'un SE ?
La transmission du savoir de l'expert.

###Comment est apparu le terme "Intelligence Artificielle" ?
C'était le titre d'une réunion de chercheurs invité par McCarthy à Dartmouth en 1956

###Quel est l'inconvénient d'un régime irrévocable dans une moteur d'inférence ?
L'inconvénient d'un régime irrévocable est qu'il convient que aux cas où la plupart des chemins mènent à la solution, ce qui est rare.

###Qu'est-ce que le langage LISP ?
LISP est un langage de programmation fonctionnel créé par Jon McCarthy.C'est l'un des langages les plus répandu en intelligence artificielle.
Qu'est ce que le méta-connaissance ?
le méta-connaissance est une connaissance sur une ou des connaissances.
#Partie 2:
        
###Quelle est l'astuce qui permet de coder de manière plus compacte des textes dont la fréquence d'apparition des lettres n'est pas équiprobable ?


###Quelle est l'entropie maximale d'un texte sur un alphabet de 4 lettres?
2 (00),(01),(11),(10)  4*(-1/4 * log2(1/4))

###Dans quel cas la fonction H (ou S pour les physiciens) est-elle maximale ? 
Lorsque les événements sont équiprobables.
Quand chaque état à la même probabilité d'apparition.

###Si le texte C est une compression du texte A, quel texte aura l'entropie la plus grande ? Dans ce cas, que fait un algorithme de compression de données en matière d'entropie ?
Le texte C a une entropie plus faible, car l'algorithme de compression réduit le nombre de bits nécessaire pour encoder un fichier. L'entropie en informatique représentant le nombre de bits minimal pour coder un fichier, le fichier compressé a bien une entropie inférieur. 

###Quel est le problème qui survient si un codage n'est pas préfixe ? Citer un exemple
Il devient impossible de distinger des lettres encodées des autres, car certaines lettres sont le préfixes d'autres.
Par exemple, le langage Morse de Samuel Morse.

###Soit l'alphabet {a,b} Calculer l'entropie de la chaîne "aabb"
E =-((1/2)*log2(1/2))-((1/2)*log2(1/2))
  = -2 * ((1/2)*log2(1/2)) = 1
vérification : il faut bien 1 bit pour codé un alphabet de taille 2.

###Soit le texte "abcbc", proposez en calculant l'entropie un code sur 2 bits pour chaque caractère du texte.
Code a:00,b:01,c:10,d:11 => 00 01 10 01 10(taille = 10) ,E=-(1/3*log2(1/3))-(2/3*log2(2/3))-(2/3*log2(2/3))=1.308

###Que permet de déterminer un tableau de contingence ?

   * Un tableau de contingence permet de déterminer  la dépendance entre 2 caractères
###Pourquoi l'encodage de l'alphabet en morse nous oblige-t-il à créer un code spécial pour séparer les lettres?
Quelques lettres de l'alphabet morse ont des préfixes d'autres lettres.Par exemple a=.\_ est préfixe de j=.\_ \_ \_ et r=.\_.
###
###Quel est le principe du codage de Huffman ? 
la création d'un arbre déséquilibré où les lettres apparaissent à une profondeur d'autant plus importante qu'elles sont peu fréquentes dans le texte analysé.

###De quel manière obtenons nous un codage préfixe ?
A l'aide d'un arbre binaire où les lettres sont en position terminale (feuilles)

###**Si l'entropie du texte A est supérieure à l'entropie du texte B et si les textes A et B ont la même longueur : quel est le texte qui contiendra le plus d'information ? Le texte A ou le texte B ? (justifiez)**
Le texte A contiendra plus d'informations, car il sera moins "creux" que le texte B. Je pourrai moins comprimer le texte A que le texte B.

###Que dit la deuxième loi de la thermodynamique ?

###Quelle est l'entropie d'un pile ou face ?
###
###Quel est le problème qui survient si un codage n'est pas préfixe ? Citer un exemple
Si un codage n'est pas préfixe, deux lettres différentes pourront commencer de la même manière, ce qui fait qu'il faudra séparer les lettres par des espaces. En Morse, "C" s'écrit "\_ . \_ .", mais "\_ ." est la lettre "N". Si l'on ne met pas d'espaces entre les lettres, "\_ . \_ ." peut se lire "NN" ou "C".

**Quelle idée peut-on imaginer pour créer un codage sur un nombre "non entier" de bits ? qui fut le premier à présenter cette idée en 1952 ?**
C'est David Huffman qui a imaginé cela : coder chaque élément avec un nombre de bit différent, en codant sur moins de bit les éléments les plus fréquents.

###**Comment peut-on obtenir facilement un codage préfixe ?**

###Par quoi Shannon remplace-t-il la constante de Boltzmann dans sa théorie de l'information ?
Par la probabilité d'apparition d'un état.

###Calculer l'entropie pour le texte "hello world".
###En déduire le nombre minimal de bits pour coder chaque caractère.
L'entropie est 2.84535, le nombre de bits minimal est donc de 3 par caractère.

#Partie 3:

**Que permet de déterminer un tableau de contingence ?**
La dépendance entre 2 caractères.

**Qu'est-ce qu'un noeud terminal ?**
Un noeud est dit terminal s'il arrive uniquement sur des feuilles parfaitement discriminées.

###Qu'est-ce que la règle delta ?


###L'utilisation d'un algorithme CART ou C4,5 donneront-ils les mêmes arbres (à partir de jeux de données identiques) ?


###A quoi sert le "t" de Tschuprow ?

Il indique le nombre de dégré de liberté par état.

###Comment peut-on comparer l'indice d'impureté de Gini à l'entropie ?


###En C4.5, comment choisir une variable discriminante ?
On choisit la variable avec le plus fort pouvoir discriminant.
Cette valeur est calculée en faisant la différence entre l'entropie maximale et l'entropie de la variable.  

**Que risque-t-on à créer des arbres trop précis / exacts ?**
on risque le surapprentissage

###Qu'est ce qu'une variable de segmentation ?
caractéristique qui va être utilisée pour diviser un segment de donnée en segments plus petits.

**En quoi les arbres de décision peuvent être utile en IA ?**
diapo 2 de la partie 3

**Est-il plus judicieux de mettre les variables à forte ou à faible entropie au plus proche de la racine, dans un arbre de décision ?**
L'entropie désigne le niveau de désordre dans un système. Si une entropie est forte, cela signifie que les éléments sont très mélangés. Au contraire, une entropie faible correspond a un système "ordonné". Ainsi, il vaut mieux choisir des variables à faible entropie, afin de mieux segmenter (séparer) les classes.


#Partie 4: Réseaux neuronaux
###
Qu'est-ce qu'une descente de gradient ? A quoi cela sert-il et quel en est le fonctionnement ?

Quel est le problème du Perceptron ?

###Quel est le modèle de réseau neuronal qui est booléen ?


###Comment se représente le résultat d'un modèle de Kohonen ?


###Expliquer l'existence d'optimums locaux et exposé une technique permettant de sortir d'un optimum local et de trouver l'optimum globale.
On est dans un optimum local si tout les candidats voisins à l'optimum local ont un résultat inférieur à l'optimum local. Pour sortir de l'optimum local et trouver l'optimum globale, il faut envisagées un nombre de voisins plus grand, voir l'intégralité du dataset.

###Quel est le problème des réseaux neuronaux en matière de résultat obtenu ?


**Qu'est-ce que la "Widrow's Rule of Thumb" ? Dans quel cas s'applique-t-elle et comment ? **
La règle dit N=W/e  N est le nombre de données en entrée, qui dépend de W, le nombre de paramètres à optimiser et e l'erreur qu'on juge acceptable. Pour une erreur de 10% et 10 paramètres à optimiser, il faut au minimum  10/0.1 = 100 données.

**Comment détermine-t-on le nombre de couches et le nombre de neurones sur les couches intermédiaire d'un réseau de neurones ?**


###Qu'elles sont les différence entre la perceptron et la règle Delta ?


###A quoi sert la fonction logistique / sigmoïde ?


**Pourquoi la règle delta est-elle floue ? Et est-ce bien ou non ?**


**Quel est le but des Réseaux de Hopfield ? Quelle est leur particularité par rapport aux autres réseaux neuronaux ?**
Leur but est d'implémenter une mémoire auto-associative, faisant correspondre des entrées à des sorties (identiques aux entrées).Les Réseaux de Hopfield sont plus proches de la mémoire humaine. Ils sont capables de mémoriser des données erronées, ou d'oublier des données.

###Qu'arrive-t-il à un neurone lorsqu'il est trop souvent soumis a un stimulus donné ?
Le mécanisme d'habituation va permettre au neurone de s'habituer au stimulus venu de la source en question.
Il faudra un stimulus de plus en plus fort pour continuer à déclencher le neurone. Jusqu'à disparition de la réaction si le mécanisme continu.

###Quel est le problème du Perceptron ?
Le Perceptron n'arrive pas à généraliser. Il a tendance à apprendre par coeur.

###Comment se représente le résultat d'un modèle de Kohonen ?
Sous forme d'une carte 2D, d'après les poids associés aux neurones.

**Quel est la particularité des réseaux de Hopfield ?**
Ils sont auto-associative et possedent  la capacité à reconnaître des données bruitées ou partielles,  à mémoriser des choses fausses, et aussi à Oublier.

###Quel est l’intérêt de normaliser les entrées ?
En normalisant, on favorise une meilleure convergence.
###
###Citez trois modèles de réseaux neuronaux ?
3 Modèles: 1/ McCulloch et Pitts
           2/ ADALINE
           3/ Perceptron


#Partie 5:

###A quoi sert l'algorithme K-means ?

###Comment est défini les clusters?
Les clusters sont des partitions ordonnées de données.
    
**Pourquoi l'évolution artificielle est-elle une technique très prometteuse pour l'informatique  moderne ?**
**   **
###Qu'est-ce qu'une méthode d'optimisation "non supervisée" ?
   ** **
**Quel est le principal problème de la méthode K-means ?**
Il faut dire au préalable combien de centroïdes on va utiliser.
###
###Que signifie le terme "épistasie" dans les algorithmes génétiques ?


###Dans un arbre pondéré, que fait-on aux probabilités le long d'une branche ? On les multiplie ou on les ajoute ?

###Quel est l'autre nom de la méthode K-means ?
La méthode K-means est aussi appellée l'algorithme de quantification de Lloyd-Max ou la méthode des plus proches voisins

###A quoi servent les réseaux Bayesien ?


###D'après le théorème de Bayes, sur une population de 100 000, avec une probabilité de 2% et une fiabilité de 97.2%. Quel est le taux de vrai positif dans la population positive ?
Les positifs sont au nombre de : 100 000 * .02 = 2 000.
Décomposés en 1944 vrai positifs (2 000 * .972) , 56 (2 000 * (1-.972) )sont des faux positifs.
Parmi les 98 000 (100 000 * (1-.02)) négatifs, 2 744 (98 000 * (1-.972)) seront déclarés faussement positifs.
Le total de positifs est de 2 000 + 2 744 = 4 744
Le taux de vrai positifs dans la population est de : 2 000 / 4 744 = .42
Soit 42%

###Dans le cadre du théorème de Bayes, qu'est-ce qu'une probabilité préalable et pourquoi est-elle importante ?
La probabilité préalable doit être connue à l'avance si l'on veut utiliser le théorème de Bayes pour inverser une proposition. 

###Quels sont les trois types de jeux de données utilisés en évolution artificielle?Quels sont leurs rôles?
- 1 jeu d'apprentissage, sur lequel on fait évoluer les individus
- 1 jeu de tests, pour détecter le sur-apprentissage
- 1 jeu d'évaluation, pour évaluer l'individu sur un jeu qui n'a pas participé à l'évolution de l'individu

###Pourquoi est il nécessaire d'utiliser 3 jeux de données pour les algorithmes d’Évolution Artificielle ?
Le premier jeu est le jeu d'apprentissage.Le deuxième jeu sert à détecter le surapprentissage.Le Troisième sert à l'évaluation.

###Combien de jeux de données différents doit-on avoir pour détecter le sur-apprentissage ?
Il faut 3 jeux de données :
    - 1 jeu d'apprentissage
    - 1 jeu de test
    - 1 jeu d'évaluation

###Qu'est-ce que l'épistasie ?
L'épistasie dénote la dépendance entre plusieurs gènes.

###De quoi est constitué le réseau bayésien ?
Un réseau bayésien représente des variables aléatoires sous la forme d'un graphe orienté acyclique. - Les nœuds sont des variables aléatoires- Les arcs sont des dépendances probabilistes dirigées entre les variables.

###Qu'est-ce qu'un diagramme de Voronoï ?
C'est un diagramme décrivant des cellules délimitées par les médiatrices entre centroïdes.

**le MIT a classé les réseaux bayésiens comme 4e technologie émergente du siècle à venir. Pourquoi selon-vous ? Quels sont les points importants à retenir sur ces types de réseaux ?**
- ils sont déterministes, parfaits et dynamiques;
- ils permettent de diagnostiquer et de prédire;
- mélange entre théorie des graphes et théorie des probabilités;
- permet de modéliser les connaissances dans des domaines incertains;

**Combien de jeux de données faut-il utiliser pour éviter le sur-apprentissage ? Citez-en au moins deux.**
Selon M. Schoenauer, il faut 3 jeux de données, : 
- jeu d'apprentissage, sert à instruire l'individu;
- jeu de test, empêche le sur-apprentissage;
- jeu de validation, permet de noter l'individu sur des données qu'il n'a pas encore vu.

