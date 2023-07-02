# Projet-Arduino
# Objectif de projet :
Conception et réalisation d’un système de radar détecteur d'objets en utilisant la carte Arduino , et une interface MATLAB pour afficher le champ de détection.
# Introduction :
Système embarqué de radar et de porte automatique pour une prison sécurisée.

Le présent projet vise à concevoir et à mettre en œuvre un système embarqué novateur intégrant un radar et une porte automatique, destiné à être installé dans un établissement pénitentiaire. Le système proposé vise à renforcer la sécurité de la prison en fournissant un contrôle automatisé des accès tout en permettant une détection avancée des mouvements suspects.

Dans le contexte actuel où la sécurité et la surveillance des prisons sont devenues des préoccupations primordiales, l'utilisation de systèmes avancés et intelligents est essentielle pour maintenir l'ordre et prévenir les incidents. Ce projet se concentre spécifiquement sur l'intégration d'un radar et d'une porte automatique pour offrir une solution complète et efficace.

Le radar, en tant que composant clé du système, permettra une détection précise et en temps réel des objets et des personnes se trouvant dans une zone prédéfinie. Il sera capable de distinguer entre différents types de mouvements, tels que les intrusions ou les comportements suspects, et de les signaler immédiatement au personnel de surveillance.

La porte automatique, quant à elle, sera intégrée au système de façon à répondre aux informations fournies par le radar. Lorsqu'une détection anormale est signalée, la porte se fermera automatiquement pour empêcher l'accès non autorisé à certaines zones sensibles de la prison. De plus, la porte pourra également être programmée pour s'ouvrir et se fermer selon des horaires prédéfinis, contribuant ainsi à la gestion efficace des flux de personnes.

L'objectif ultime de ce projet est d'améliorer la sécurité et la surveillance des prisons en utilisant des technologies de pointe. En mettant en place un système embarqué fiable et performant, nous espérons non seulement réduire les risques d'évasion et d'incidents, mais aussi faciliter le travail des agents de sécurité en leur fournissant des outils efficaces pour surveiller les mouvements et contrôler les accès.

Ce rapport présentera les différentes étapes du développement du système embarqué, notamment la conception, la sélection des composants, la programmation et les tests. Il abordera également les défis potentiels liés à la mise en œuvre de ce projet et proposera des recommandations pour optimiser son efficacité et sa sécurité.

En conclusion, ce projet vise à intégrer un radar et une porte automatique dans un système embarqué pour renforcer la sécurité et la surveillance dans les prisons. Grâce à cette solution innovante, nous espérons contribuer à un environnement carcéral plus sécurisé et offrir aux agents pénitentiaires des outils avancés pour faire face aux défis croissants liés à la gestion des établissements pénitentiaires.

# Image pour le projet :

![image](https://github.com/yousseflaamari/Projet-Arduino/assets/96209336/22bfc6d9-4e31-4d36-a4e0-45d13a59c32a)

![image](https://github.com/yousseflaamari/Projet-Arduino/assets/96209336/9eca9294-5a7b-4555-8635-cd268035667b)

# Composant et matériels utiliser :
1)Carte Arduino .
2)Deux Servo Moteur .
3)Capteur Ultrasonique HC-SR04.
4)Capteur infrarouge .
5)Sonor .
6)Files.
7)Porte .
8)Maquette Carton.
# Architucture  :
On fait une sumilation avec Proteus :
![image](https://github.com/yousseflaamari/Projet-Arduino/assets/96209336/ec07222c-c838-4193-93d8-29e09a8cc9e2)

# Fonctionement de Projet :
Le capteur ultrasonique est utilisé pour estimer la distance entre les objets en émettant une onde sonore et en calculant le temps nécessaire à l'onde pour revenir après avoir heurté l'objet. Le servomoteur permet de faire pivoter le capteur ultrasonique sur un angle allant de 1 à 180 degrés, et inversement. À chaque position du servomoteur, la distance est mesurée et affichée sur le moniteur série à des fins de débogage.  
Un système sonar lié à un radar doté d'une fonction de notification sonore est conçu pour détecter des objets et émettre un signal sonore lorsqu'il en repère un. Le sonar utilise des ondes sonores pour détecter les objets environnants, en émettant des signaux acoustiques et en écoutant les échos résultants. Le radar, quant à lui, utilise des ondes radio pour détecter les objets en mesurant les échos des signaux radio réfléchis par ces objets.
Une porte automatisée équipée d'un capteur infrarouge est conçue pour s'ouvrir et se fermer automatiquement en détectant la présence de personnes ou d'objets à proximité à l'aide d'un faisceau infrarouge. Lorsqu'une personne ou un objet traverse le faisceau infrarouge, le capteur détecte ce changement et envoie un signal pour déclencher l'ouverture de la porte.

 # Interface Matlab  :
On fait une sumilation avec Matlab :
![image](https://github.com/yousseflaamari/Projet-Arduino/assets/96209336/874a9fb9-afa8-49ff-91ca-c0ca4693a157)

# les Logiciels utiliser :
1) Matlab .
2) proteus .
3) Arduino Uno .
   



