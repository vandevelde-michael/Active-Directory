# Active Directory - Présentation et Analyse

## Table des matières
1. [Description](#description)
2. [Documentation](#documentation)
3. [Installation](#installation)
4. [Utilisation](#utilisation)
5. [Cas pratiques](#cas-pratiques)
6. [Contact](#contact)

## Description
Active Directory est une solution de gestion des identités et des accès développée par Microsoft. Il permet d'organiser, sécuriser et administrer les ressources d'un réseau informatique de manière centralisée. Ce projet vise à fournir une analyse approfondie de son fonctionnement, ses avantages et ses limitations.

## Documentation
Pour une documentation détaillée, veuillez consulter notre [page Notion](https://drive.google.com/file/d/1cc19-IE14AXPkwu11QX33MjkltZCNyyF/view?usp=sharing)

## Installation

### Prérequis
- Un serveur ou une machine compatible avec Active Directory (Windows Server requis)
- Une image ISO de Windows Server avec les fonctionnalités AD DS (Active Directory Domain Services)
- Accès Internet pour télécharger les mises à jour

### Étapes d'installation

#### Étape 1 : Préparer l'environnement
1. Installer Windows Server sur le matériel ou une machine virtuelle
2. Configurer une adresse IP fixe
3. Renommer la machine pour correspondre aux conventions de nommage

#### Étape 2 : Installer le rôle Active Directory
1. Ouvrir le Gestionnaire de serveur
2. Ajouter un rôle et sélectionner "Services AD DS"
3. Suivre l'assistant d'installation et redémarrer la machine

#### Étape 3 : Promouvoir le serveur en contrôleur de domaine
1. Lancer l'outil "Configuration de l'Assistant Active Directory"
2. Sélectionner "Ajouter une nouvelle forêt" ou rejoindre un domaine existant
3. Configurer les paramètres de domaine (nom, mot de passe DSRM, etc.)
4. Redémarrer pour finaliser l'installation

## Utilisation
Active Directory permet :
✅ L'authentification et l'autorisation des utilisateurs
✅ La gestion centralisée des stratégies de groupe (GPO)
✅ Le contrôle d'accès aux ressources réseau
✅ L'intégration avec des services Cloud comme Azure AD

## Cas pratiques
### Exemple : Gestion des accès dans une entreprise
Un administrateur système utilise Active Directory pour :
- Créer et gérer les comptes utilisateurs et groupes
- Appliquer des stratégies de sécurité via GPO
- Automatiser le déploiement d’applications via AD
- Surveiller et auditer l'activité réseau

Résultat : Une infrastructure sécurisée et simplifiée pour la gestion des accès et des ressources.

## Contact
📧 michael.vandevelde@laplateforme.io  
📧 etienne.verschuere@laplateforme.io  
📧 bastien.llorca@laplateforme.io  
📧 frederic.perry@laplateforme.io
