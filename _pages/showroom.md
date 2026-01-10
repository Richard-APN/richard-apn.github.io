---
permalink: /
title: "Démonstrateur APN AUTOMATION 2026"
author_profile: true
---

Ce site présente les applications liées à
l’automatisme industriel développées avec le démonstrateur.

-----

<img width="1063" height="532" alt="image" src="https://github.com/user-attachments/assets/19e961d6-792c-4afd-a659-3718825b4bb0" />

Le démonstrateur APN AUTOMATION a été réalisé en conformité avec 

+ La norme IEC 62443 : le référentiel pour la cybersécurité industrielle
+ La directive 2006/42/CE (qui sera prochainement remplacée par le règlement (UE) 2023/1230 du parlement européen) pour la Sécurité Machine.

Il a été pensé en 7 parties principales :

+ Industrie 4.0
+ Sécurité machine
+ IO Link
+ Motion control
+ Cybersécurité
+ Réalité augmentée
+ Vision.

Implémenté 

+ De la réalité virtuelle  associée au domaine industriel pour mettre en contexte les exemples d’automatismes proposés
+ D’intelligence Artificielle à partir de modèles  de Machine Learning utilisés dans le cas de tris de pièces.

Il met en œuvre

+ les bus de terrain : MODBUS TCP-IP et ETHERCAT 
+ Les technologies de sécurité Flexi Soft et Flexi Loop, (développées par SICK)
+ le protocole de communication IO Link
+ les langages de programmation conformes à la norme IEC 61131-3
+ l’outil de programmation Node-Red 
+ la supervision dans le cadre du dialogue homme machine.

Il comporte pour sa partie opérative (Motion Control)

+ Un contrôleur d’axe pour machines brushless
+ Deux contrôleurs d’axe pour machines Pas à Pas
+ Un variateur de vitesse pour machines asynchrones
+ Pilotés par un API, « maitre » pour la communication ETHERCAT et « serveur » pour la communication MODBUD TCP-IP.

Utilisation de la réalité virtuelle
Le logiciel Factory I/O complète l’installation. 

<img width="631" height="445" alt="image" src="https://github.com/user-attachments/assets/29b86eb6-5a91-4c92-b7f4-78f1d436e4d7" />


Il permet de visualiser le contexte industriel dans lequel les composants du showroom sont utilisés.
On pourra créer des scénarios pour simuler les commandes homme machine ; visualiser l’action de la reconnaissance de pièces par l’Intelligence Artificielle ; configurer une interface MODBUS.

Intérêts pédagogiques 

•	Sécurité Machine :

+ Description des modes de marche et d’arrêt
+ Choix des éléments de sécurité selon le règlement (UE) 2023/1230 du parlement européen) pour la Sécurité Machine :  Stratégie de réduction des risques en 9 étapes     
+ Connexion des éléments
+ Utilisation du logiciel Flexi Soft Designer (Sick) pour la programmation des séquences de sécurité
+ Communication ETHERCAT
+ Mise en œuvre de la technologie Flexi Loop (Sick).


•	Industrie 4.0 :

+ Mise en œuvre du protocole de communication IO LINK
+ Choix des participants : détection, passerelle, visualisation, collecte et transmission des données.

•	Réalité augmentée :

<img width="772" height="633" alt="image" src="https://github.com/user-attachments/assets/6600a257-0e7f-41ac-a1e1-2801510061fb" />


+ Mise en œuvre du logiciel SARA pour un usage standard : visualisation des données sur tablette des capteurs, automates, actionneurs pour la surveillance, le diagnostic, la mise en service de l’environnement.


•	Cybersécurité :

+ Mise en œuvre de  la norme IEC 62443 : le référentiel pour la cybersécurité industrielle.

•	Motion Control : 

+ Mise en œuvre des composants industriels :
* Automate + extension OMRON
* Contrôleur de broche OMRON
 * Variateur de fréquence pour MAS OMRON
* Contrôleur d’axe moteur pas à pas ETHERCAT SMC
* Contrôleur d’axe moteur pas à pas filaire SMC.

•	Bus de terrain MODBUS TCPIP :

Communication MODBUS TCP-IP entre les éléments suivants :

<img width="663" height="409" alt="image" src="https://github.com/user-attachments/assets/dfcc6b16-4c3b-4ca5-8736-1101d85306af" />

+ Le SERVEUR PLC NXP2 
+ Le CLIENT Factory I/O pour la partie réalité virtuelle
+ Le  CLIENT SARA pour la partie réalité augmentée.

•	Bus de terrain ETHERCAT :

Communication ETHERCAT entre les éléments suivants :

<img width="784" height="239" alt="image" src="https://github.com/user-attachments/assets/5e2b36f9-d5a9-4bc4-8e96-956e4109d7e8" />

+ Le MAITRE PLC NXP2
+ L’ESCLAVE R88D (Commande de broche)
+ L’ESCLAVE 3GAX-MX2-ECT (Variateur de fréquence pour moteur du plateau rotatif)
+ L’ESCLAVE JXCE1 (Commande de la table verticale)
+ L’ESCLAVE Flexi Soft (Remontée d’information de sécurité).

•	Intelligence Artificielle pour le triage automatique de pièces :

+ Triage  automatique de pièces. Du modèle réel au modèle simulé
+ Fonctionnement de la trieuse
*  Détection des pièces. Du modèle simulé au modèle réel
* Détection des pièces. Du modèle réel au modèle pédagogique
* Tri des pièces. Du modèle simulé au modèle  pédagogique
* Triage automatique de pièces. Modèle pédagogique complet
* Triage automatique de pièces. Modèle pédagogique virtuel
* Triage automatique de pièces. Modèle pédagogique sans réalité virtuelle
* Triage automatique de pièces. Modèle pédagogique avec composants industriels.

Publics concernés

Enseignements professionnels pré-baccalauréat :
+ Seconde professionnelle des métiers
+ Bac pro MELEC (Métiers de l’Electricité et de ses Environnements Connectés)
+ Bac pro CIEL (Cybersécurité, Informatique et réseaux, Electronique)
+ Bac pro MSPC (Maintenance des Systèmes de Production Connectés)
+ Bac pro PLP (Pilote de Ligne de Production).

Enseignements professionnels post-baccalauréat :
+ BTS ATI (Assistant technique d’ingénieur)
+ BTS Électrotechnique
+ BTS CIEL (Cybersécurité, Informatique et réseaux, Électronique)
+ BTS MS (Maintenance des Systèmes – option A)
+ BTS CRSA (Conception et Réalisation de Systèmes Automatiques)
+ BTS CIRA (Contrôle Industriel et Régulation Automatique)
+ BTS PP (Pilotage de procédés).
  
 Enseignements technologiques :
+ Bac STI2D, spécialité Énergie et Environnement
+ Bac spécialité SI.
  
Enseignements universitaires professionnalisés :
+ Génie Électrique et Informatique Industrielle.

<img width="531" height="156" alt="image" src="https://github.com/user-attachments/assets/ad432f36-521a-4830-8f87-ba8f483adb20" />

