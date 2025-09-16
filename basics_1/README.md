# basics_1

## Présentation

Ce dossier regroupe des scripts Bash pour explorer et manipuler des notions fondamentales du réseau sur une machine Linux.  
Il permet de mettre en pratique des concepts essentiels pour comprendre le fonctionnement des réseaux et l’administration système.

---

## Contenu des fichiers

- **0-change_your_home_IP**  
  Script Bash qui modifie le fichier `/etc/hosts` pour :
  - Faire que `localhost` pointe vers `127.0.0.2` au lieu de `127.0.0.1`
  - Faire que `facebook.com` pointe vers `8.8.8.8` (Google DNS)
  Ce script montre comment la résolution des noms peut être modifiée localement et l’impact sur les commandes réseau.

- **1-show_attached_IPs**  
  Script Bash qui affiche toutes les adresses IPv4 actives sur la machine.  
  Permet d’identifier rapidement les interfaces réseau et leurs adresses IP, y compris l’adresse de loopback (`127.0.0.1`).

- **2-port_listening_on_localhost**  
  Script Bash qui écoute sur le port 98 de localhost et affiche tout texte reçu.  
  Utile pour tester la communication locale, comprendre le fonctionnement des ports et diagnostiquer des problèmes de connexion.

---

## Ce que l’on apprend

- Comment modifier la résolution des noms locaux via le fichier `/etc/hosts`.
- Comment afficher les adresses IP actives d’une machine Linux.
- Comment utiliser des outils comme `nc` (netcat) pour écouter sur un port et recevoir des données.
- Les bases de la communication réseau locale (loopback).
- L’importance des ports dans la gestion des services réseau.
- L’utilisation de scripts Bash pour automatiser des tâches d’administration réseau.

---

## Utilisation

- Rendez chaque script exécutable avec :  
  `chmod +x <nom_du_script>`
- Exécutez les scripts en ligne de commande pour observer leur effet ou tester des fonctionnalités réseau.
- Certains scripts nécessitent les droits administrateur (`sudo`) pour modifier des fichiers système comme `/etc/hosts`.

---

## Auteur

Projet réalisé dans le cadre de la formation Holberton School.