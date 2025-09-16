# basics_0

## Présentation

Ce dossier regroupe les scripts et fichiers d’apprentissage des bases du réseau informatique.  
Il est destiné à comprendre les principaux concepts utilisés dans la communication entre machines sur un réseau.

---

## Contenu des fichiers

- **0-OSI_model**  
  Présente le modèle OSI (Open Systems Interconnection), qui décrit les 7 couches de la communication réseau (physique, liaison, réseau, transport, session, présentation, application).

- **1-types_of_network**  
  Explique les différents types de réseaux (LAN, WAN, MAN, PAN, etc.), leurs usages et leurs différences.

- **2-MAC_and_IP_address**  
  Détaille la différence entre une adresse MAC (identifiant matériel unique d’une carte réseau) et une adresse IP (identifiant logique d’une machine sur un réseau).

- **3-UDP_and_TCP**  
  Compare les protocoles UDP et TCP, leurs avantages, inconvénients et cas d’utilisation (TCP pour la fiabilité, UDP pour la rapidité).

- **4-TCP_and_UDP_ports**  
  Script Bash qui affiche les ports TCP et UDP en écoute sur la machine, avec le PID et le nom du programme associé.  
  Permet de comprendre le rôle des ports dans la communication réseau.

- **5-is_the_host_on_the_network**  
  Script Bash qui vérifie si une adresse IP est joignable sur le réseau (utilisation de la commande `ping`).  
  Permet de diagnostiquer la connectivité réseau.

---

## Ce que l’on apprend

- Les fondamentaux du modèle OSI et la séparation des responsabilités dans la communication réseau.
- Les différents types de réseaux et leurs usages.
- La différence entre adresses MAC et IP, et leur rôle dans l’identification des machines.
- Les protocoles de transport TCP et UDP, leurs caractéristiques et leur impact sur la transmission des données.
- L’utilisation des ports pour permettre la communication entre différents services sur une même machine.
- Comment diagnostiquer la connectivité réseau avec des outils comme `ping`.
- L’utilisation de commandes Bash pour explorer et manipuler les informations réseau sur une machine Linux.

---

## Utilisation

Chaque fichier peut être exécuté ou consulté pour approfondir un aspect précis du réseau.  
Les scripts Bash doivent être rendus exécutables avec `chmod +x <nom_du_script>` avant utilisation.

---

## Auteur

Projet réalisé dans le cadre de la formation Holberton School.