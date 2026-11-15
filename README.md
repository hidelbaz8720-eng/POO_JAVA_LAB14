# TP 14 – CRUD avec DAO Générique en Java

##  Fondamentaux et Concepts Avancés de la Programmation Java

**Plateforme :** MLIAEdu  
**Module :** Programmation Orientée Objet en Java  
**TP :** 14 – CRUD avec DAO Générique  
**Étudiant :** Hamza ID EL BAZ  
**Année universitaire :** 2025–2026

---

## Objectifs du TP

L'objectif de ce TP est de développer une application Java organisée en plusieurs couches, en appliquant les principes de la programmation orientée objet.

Ce travail permet de comprendre et de mettre en œuvre :

- L'architecture logicielle en couches.
- Les interfaces et les classes génériques.
- Le modèle DAO (Data Access Object).
- La séparation entre les données et la logique métier.
- Les opérations CRUD (Create, Read, Update, Delete).
- La gestion des relations entre entités.

##  Architecture du projet

Le projet utilise une architecture organisée en trois couches principales :




##  Entités principales

### 1. Identifiable

Interface commune permettant d'identifier les objets à travers un identifiant unique.

### 2. Salle

Représente une salle contenant plusieurs machines.

### 3. Machine

Représente une machine associée à une salle.

##  Interfaces génériques

| Interface / Classe | Rôle |
|---|---|
| `Identifiable` | Gestion des identifiants |
| `IDao<T>` | Définition des opérations CRUD génériques |
| `ListeDao<T>` | Implémentation du DAO avec une liste |
| `IService<T>` | Définition des services génériques |
| `SalleService` | Gestion métier des salles |
| `MachineService` | Gestion métier des machines |


##  Notions Java étudiées

- Programmation Orientée Objet (POO).
- Interfaces Java.
- Généricité (`<T>`).
- Collections (`ArrayList`).
- Encapsulation.
- Architecture en couches.
- Pattern DAO.
- Séparation des responsabilités.
- Relations entre objets.

**Remarque :** Ce TP est réalisé sans expressions lambda ni Streams, conformément aux consignes pédagogiques.

##  Travail pratique

Le TP est organisé en 14 étapes :

1. Introduction et prérequis.
2. Architecture en couches et modélisation.
3. Création de l'interface `Identifiable`.
4. Création de l'entité `Salle`.
5. Création de l'entité `Machine`.
6. Définition de l'interface `IDao` générique.
7. Implémentation du DAO en mémoire (`ListeDao`).
8. Définition de l'interface `IService` générique.
9. Création du service `SalleService`.
10. Création du service `MachineService`.
11. Implémentation des méthodes métiers avancées.
12. Création du programme principal (`Main`).
13. Test des opérations de mise à jour et de suppression.
14. Résumé et conclusion.

## Technologies utilisées

- **Langage :** Java
- **Version :** JDK 8 ou supérieure
- **IDE :** Eclipse / IntelliJ IDEA / NetBeans
- **Collections :** Java Collections Framework
- **Stockage :** Mémoire vive (ArrayList)

##  Exécution du projet

1. Cloner le dépôt GitHub :

```bash
git clone URL_DU_DEPOT
```

2. Ouvrir le projet dans Eclipse ou un autre IDE Java.
3. Vérifier la configuration du JDK.
4. Exécuter la classe `Main`.
5. Tester les différentes opérations CRUD.

## Captures d'écran

Ajouter ici les captures d'écran de l'exécution du programme :

- [ ] Ajout d'une salle.
- [ ] Ajout d'une machine.
- [ ] Affichage des salles et machines.
- [ ] Modification d'un élément.
- [ ] Suppression d'un élément.
- [ ] Test des méthodes métiers.
<img width="1366" height="768" alt="Capture d&#39;écran 2026-11-15 221841" src="https://github.com/user-attachments/assets/3f4ba7b5-5ae9-4566-8124-36623b1e2261" />

##  Conclusion

Ce TP permet de comprendre l'intérêt de la généricité et de l'architecture en couches dans le développement d'applications Java.

La création d'un DAO générique facilite la réutilisation du code et évite de répéter les mêmes opérations pour chaque entité.

La séparation entre les couches Model, DAO et Service rend l'application plus organisée, évolutive et facile à maintenir.

---

**Auteur : Hamza ID EL BAZ**  
Étudiant – ENS Marrakech  
Université Cadi Ayyad

⭐ *Learning Java through practice and object-oriented programming.*
