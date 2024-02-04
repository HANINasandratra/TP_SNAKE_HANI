# TP_SNAKE_HANI
Une implémentation simple du classique jeu du serpent en Java utilisant JavaFX.

Comment Jouer
Utilisez les touches W, A, S, D pour contrôler le mouvement du serpent.
W : Monter
A : Aller à gauche
S : Descendre
D : Aller à droite
L'objectif est de manger la nourriture rouge (représentée par un carré rouge) pour faire grandir le serpent.
Le jeu se termine si le serpent entre en collision avec lui-même ou les limites.

Fonctionnalités
Serpent : Le serpent est représenté par une série de rectangles noirs sur le plateau de jeu. La tête est initialement rouge.
Nourriture : Carré rouge qui apparaît aléatoirement sur le plateau pour que le serpent puisse manger et grandir.
Fin du Jeu : Le jeu se termine si le serpent entre en collision avec lui-même ou les limites.

Comment Exécuter
Assurez-vous d'avoir Java installé sur votre machine.

Compilez et exécutez la classe SnakeApp.
bash
Copy code
javac SnakeApp.java
java SnakeApp
Utilisez les touches W, A, S, D pour contrôler le serpent et profitez du jeu!
Logique du Jeu
Le serpent se déplace dans la direction spécifiée à intervalles réguliers.
Manger de la nourriture augmente la longueur du serpent.
Le jeu se termine si le serpent entre en collision avec lui-même ou les limites.

Aperçu du Code
Le code utilise JavaFX pour l'interface graphique.
Le mouvement du serpent est géré par un thread séparé pour permettre un mouvement continu.
Les événements de touche sont utilisés pour changer la direction du serpent.
La détection de collision est mise en œuvre pour vérifier les collisions avec le corps du serpent, la nourriture et les limites.
