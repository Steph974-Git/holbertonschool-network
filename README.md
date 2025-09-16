# holbertonschool-network

## Présentation

Ce dépôt regroupe des scripts et fichiers pour apprendre et pratiquer les bases du réseau informatique sur Linux.  
Il est organisé en plusieurs dossiers thématiques, chacun couvrant des aspects essentiels du fonctionnement des réseaux et de l’administration système.

---

## Structure du dépôt

- **basics_0/**  
  Découverte des concepts fondamentaux du réseau, du modèle OSI aux adresses MAC/IP et aux protocoles de transport.

- **basics_1/**  
  Mise en pratique avec des scripts Bash pour manipuler la configuration réseau locale, afficher les IPs actives et tester l’écoute sur des ports.

---

## Détail des dossiers et apprentissages

### basics_0

- **0-OSI_model**  
  Présentation du modèle OSI et de ses 7 couches, pour comprendre la séparation des responsabilités dans la communication réseau.

- **1-types_of_network**  
  Explication des différents types de réseaux (LAN, WAN, MAN, PAN), leurs usages et leurs différences.

- **2-MAC_and_IP_address**  
  Différence entre une adresse MAC (identifiant matériel) et une adresse IP (identifiant logique sur le réseau).

- **3-UDP_and_TCP**  
  Comparaison des protocoles UDP et TCP, leurs avantages, inconvénients et cas d’utilisation.

- **4-TCP_and_UDP_ports**  
  Script Bash pour afficher les ports TCP et UDP en écoute, avec le PID et le nom du programme associé.  
  Permet de comprendre le rôle des ports dans la communication réseau.

- **5-is_the_host_on_the_network**  
  Script Bash pour vérifier la connectivité d’une adresse IP via la commande `ping`.  
  Utile pour diagnostiquer les problèmes de réseau.

---

### basics_1

- **0-change_your_home_IP**  
  Script Bash pour modifier le fichier `/etc/hosts` :  
  - Change l’adresse de `localhost` vers `127.0.0.2`
  - Fait pointer `facebook.com` vers `8.8.8.8`  
  Permet de comprendre l’impact de la résolution des noms localement.

- **1-show_attached_IPs**  
  Script Bash pour afficher toutes les adresses IPv4 actives sur la machine, y compris l’adresse de loopback (`127.0.0.1`).  
  Permet d’identifier rapidement les interfaces réseau.

- **2-port_listening_on_localhost**  
  Script Bash qui écoute sur le port 98 de localhost et affiche tout texte reçu.  
  Utile pour tester la communication locale et comprendre le fonctionnement des ports.

---

## Ce que l’on apprend

- Les bases du modèle OSI et la séparation des couches réseau.
- Les différents types de réseaux et leurs usages.
- La différence entre adresses MAC et IP, et leur rôle dans l’identification des machines.
- Les protocoles TCP et UDP, leurs caractéristiques et leur impact sur la transmission des données.
- L’utilisation des ports pour permettre la communication entre différents services sur une même machine.
- Comment diagnostiquer la connectivité réseau avec des outils comme `ping`.
- Comment modifier la résolution des noms locaux via `/etc/hosts`.
- Comment afficher les adresses IP actives d’une machine Linux.
- Comment utiliser des outils comme `nc` (netcat) pour écouter sur un port et recevoir des données.
- L’utilisation de scripts Bash pour automatiser des tâches d’administration réseau.

---

## Utilisation

- Rendez chaque script Bash exécutable avec :  
  `chmod +x <nom_du_script>`
- Exécutez les scripts en ligne de commande pour observer leur effet ou tester des fonctionnalités réseau.
- Certains scripts nécessitent les droits administrateur (`sudo`) pour modifier des fichiers système comme `/etc/hosts`.

---

## Auteur

Projet réalisé dans le cadre de la formation Holberton School.