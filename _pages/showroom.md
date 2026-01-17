---
permalink: /presentation_demonstrateur/
title: "Présentation générale"
author_profile: true
---

<img width="1063" height="532" alt="image" src="https://github.com/user-attachments/assets/19e961d6-792c-4afd-a659-3718825b4bb0" />

# Le démonstrateur APN AUTOMATION

Le démonstrateur APN AUTOMATION a été conçu pour respecter :

- La norme **IEC 62443** : référentiel pour la cybersécurité industrielle  
- La directive **2006/42/CE** (bientôt remplacée par le règlement UE 2023/1230) pour la sécurité machine

Il est organisé en **7 parties principales** :

1. Industrie 4.0  
2. Sécurité machine  
3. IO Link  
4. Motion control  
5. Cybersécurité  
6. Réalité augmentée  
7. Vision

## Technologies et mise en œuvre

Le démonstrateur intègre :

- **Réalité virtuelle** pour contextualiser les automatismes (Factory I/O)  
- **Intelligence artificielle** via des modèles de Machine Learning pour le tri de pièces  
- **Réalité augmentée** pour la maintenance et la surveillance (logiciel SARA)

Il met en œuvre les technologies suivantes :

- Bus de terrain : **MODBUS TCP-IP** et **ETHERCAT**  
- Technologies de sécurité : **Flexi Soft** et **Flexi Loop** (SICK)  
- Protocole de communication **IO Link**  
- Langages de programmation conformes à la norme **IEC 61131-3**  
- Outil de programmation **Node-RED**  
- Supervision dans le cadre du dialogue homme-machine  

### Motion Control

- Contrôleur d’axe pour machines brushless  
- Deux contrôleurs d’axe pour machines pas à pas  
- Variateur de vitesse pour machines asynchrones  
- Pilotage via un API maître/serveur pour communication ETHERCAT et MODBUS TCP-IP

---

## Utilisation de la réalité virtuelle

<img width="631" height="445" alt="image" src="https://github.com/user-attachments/assets/29b86eb6-5a91-4c92-b7f4-78f1d436e4d7" />

La réalité virtuelle permet de :

- Visualiser le contexte industriel  
- Créer des scénarios simulant les commandes homme-machine  
- Observer l’action de l’intelligence artificielle sur la reconnaissance de pièces  
- Configurer une interface MODBUS

---

## Intérêts techniques et pédagogiques

### Sécurité machine

- Description des modes de marche et d’arrêt  
- Choix des éléments de sécurité selon le règlement UE 2023/1230 : stratégie de réduction des risques en 9 étapes  
- Programmation avec **Flexi Soft Designer** (SICK)  
- Communication **ETHERCAT** et mise en œuvre de **Flexi Loop**

### Industrie 4.0

- Mise en œuvre du protocole **IO Link**  
- Détection, passerelle, visualisation et transmission des données

### Réalité augmentée

<img width="772" height="633" alt="image" src="https://github.com/user-attachments/assets/6600a257-0e7f-41ac-a1e1-2801510061fb" />

- Logiciel **SARA** : visualisation des données sur tablette des capteurs, automates et actionneurs pour surveillance et mise en service

### Cybersécurité

- Mise en œuvre de la norme **IEC 62443**

### Motion Control

- Automates et contrôleurs OMRON, variateurs, axes moteurs pas à pas  
- Contrôle des mouvements et coordination via **API maître/serveur**

### Bus de terrain

**MODBUS TCP-IP** : communication entre serveur PLC NXP2, Factory I/O (VR) et SARA (RA)  
**ETHERCAT** : communication entre maître PLC NXP2 et esclaves pour commandes broche, variateur, table verticale et sécurité

### Intelligence artificielle

- Tri automatique de pièces : du modèle réel au modèle pédagogique et virtuel  
- Simulation des scénarios industriels

---

## Publics concernés

- **Enseignements professionnels pré-bac** : Seconde professionnelle, Bac Pro MELEC, CIEL, MSPC, PLP  
- **Post-bac** : BTS ATI, Électrotechnique, CIEL, MS, CRSA, CIRA, PP  
- **Enseignements technologiques** : Bac STI2D, spécialité Énergie et Environnement, Bac SI  
- **Universitaires professionnalisés** : Génie électrique et informatique industrielle

---

## Logiciels utilisés

- Node-RED  
- Sysmac Studio (OMRON)  
- Flexi Soft Designer (SICK)  
- Sopas Engineering Tools (SICK)  
- Safety Designer (SICK)  
- ACT Controller 2 (SMC)  
- Factory I/O version Modbus  
- Wireshark

---
