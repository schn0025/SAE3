# Modules Réseaux : SAÉ S2.03

## Schneider Arthur schn0025

## BOURGASSER Léo bourg0341

## MAROC Mohamed-Nour Maro0040

## 1. Gestion des services : systemd

### Installation

Pas d'installation

### Configuration

Pas de configuration

### Travail effectué

Vérification du bon fonctionnement du service sshd

### Problèmes rencontrés

Aucun problème rencontré

## 2. Serveur Web apache2

### Installation

Apache2

### Configuration

Serveur Web

### Travail effectué

Création d'une page d'accueil
Affectation de droits à l'utilisateur www-data
Vérification du bon accès au serveur depuis un navigateur externe

### Problèmes rencontrés

Difficulté à accorder les droits à l'utilisateur www-data
Incompréhension suite au changement du nom du DNS
Serveurdeleo -> 2a4v2-31uvm148

## 3. Serveur Web sécurisé https

### Installation

Pas d'installation

### Configuration

Serveur Web sécurisé

### Travail effectué

Mise en place d'un certificat pour une connexion Web sécurisée

### Problèmes rencontrés

Aucun problème rencontré, mis à part le problème évoqué dans la partie 2

## 4. Langage de programmation PHP 

### Installation

Paquets php et libapache2-mod-php

### Configuration

Autorisation d'exécution de PHP pour les pages Web des utilisateurs

### Travail effectué

Création du fichier index.php

## 5. Serveur de base de données MySQL

### Installation

Paquet MySQL

### Configuration

Configuration de la sérurité du serveur MySQL

### Travail effectué

Création de l'utilisateur admin  
Attribution des privilèges à un utilisateur admin

### Problèmes rencontrés 

sudo mysql_secure_installation ne fonctionne pas si le mot de passe de l'utilisateur root n'est pas défini, il a donc fallut le définir au préalable  
sudo mysql ne fonctionne pas pour se connecter au serveur MySQL, il faut taper la ligne mysql -u root quand le mot de passe n'est pas défini et mysql -u root -p quand il l'est

## 6. Outil d'administration de bases de données phpMyAdmin

### Installation

Paquet phpmyadmin

### Configuration

mise en place des elements nesesaires a l'installation de Phpmyadmin

### Travail effectué

mise ne place pas de Phpmyadmin, création de l'utilisateur mysqltest (a pour mot de passe teste)

### Problèmes rencontrés 

pas de problème rencontré