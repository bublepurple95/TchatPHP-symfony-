# Contexte 

Un projet de tchat PHP basé sur le frimework symfony. Fait en 5 semaines, le but est de créer une API de chat entre étudiant d'HETIC (école d'internet). 

# Team 
Notre team est composé d'un cdp, de deux developpeurs, d'un developpeur front-end et d'un copy-writer. 

# Structure de base de donnée  
 
### Utilisateur
1. id 
1. Nom 
1. Prénom 
1. Promotion 
1. Classe
1. Groupe de chat
1. Url Photo 
1. Groupe de discussion 

### Message 
1. id 
1. Contenu 
1. Type 
1. Auteur
1. Timestamp

### Groupe de discussion 
1. id
1. Auteur
1. Nom
1. Messages
1. Privé / Public
1. Membres 

#Details de l'application 

## Fonctionnalités 

* Créer une discussion privé entre deux personnes 
* Créer une discussion de groupe où tout le monde peut inviter et se barrer de la conv
* Nommer une conversation
* Envoyer des messages
* L’auteur de la conv peut terminer cette dernière
* Indication des messages vu et pas vu

