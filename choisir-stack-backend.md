domaine : backend

statut validité : 21/08/2026

choisir-stack-backend.md

Contexte
Pour le projet, il y a besoin d’une stack backend performant avec du calcul rapide et des réponses rapides. Les utilisateurs seront sur tablette et pc, il faut donc une bonne portabilité. La stack doit avoir une ORM pour traiter des bases de données assez conséquentes. L’affichage des données doit être instantanée et rapide.

 Décision
Nous utiliserons ASP.NET core API qui a l’avantage de pouvoir gérer de gros volumes de données, de la communication en temps réel et beaucoup de logique métier. Il est aussi adapté pour les logiciel industriel.

Alternative considéré
Nest.JS : stack intéressante car on utilise un seul langage dans tout le projet, mais c’est aussi un inconvénient car tout sera dans le même projet, gros repo + moins bons dans les calculs.

Conséquences :
Apprentissage de C#