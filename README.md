# Projet Web2

## Nom :

Test Game

## Description :

Le jeu est multijoueur et le joueur peut se déplacer à l'aide du clavier dans une zone.

## Règle du jeu :

Vous pouvez vous déplacer dans le jeu par les 4 flèches.

## Lancement du jeu :

 - npm install socket.io
 - node app.js
 - localhost:8080

## Liste de package :

Nous utilisons que le module socket.io pour communiquer entre le serveur et le client.

## Répartition serveur / client :

Le client :

  Nous gérons si les touches du clavier, sont appuyés ou non et pour dessinner le joueur.
  
Le serveur :

  Nous gérons la création, le déplacement du joueur, la collision entre le joueur et les bords de la zone.







