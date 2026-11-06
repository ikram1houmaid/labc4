# TP – Programmation Orientée Objet en C++

## Présentation du projet

Ce projet contient deux exercices réalisés en **langage C++** dans le cadre de la programmation orientée objet (POO).

Les deux exercices permettent de comprendre et de pratiquer les attributs statiques, les méthodes statiques, les constructeurs, les classes et les associations entre objets.

**Langage utilisé : C++**

**Environnement de développement : Eclipse IDE**

---

## Exercice 1 : Suivi des Livres dans une Bibliothèque

### Objectif
Créer une classe `Livre` permettant de gérer les informations des livres et de compter automatiquement le nombre total de livres créés.

### Description
La classe `Livre` contient les attributs suivants :
- `titre` : titre du livre.
- `auteur` : nom de l'auteur.
- `annee` : année de publication.
- `nbLivres` : attribut statique qui compte le nombre total de livres créés.

### Méthodes implémentées
- **Constructeur :** initialise les informations du livre et incrémente le compteur statique.
- **afficher() :** affiche les informations de chaque livre.
- **afficherTotal() :** méthode statique qui affiche le nombre total de livres créés.

### Test
Trois objets sont créés dans la fonction `main()` :
- 1984 – George Orwell (1949).
- Le Petit Prince – Antoine de Saint-Exupéry (1943).
- L'Étranger – Albert Camus (1942).

La méthode `Livre::afficherTotal()` affiche le nombre total de livres, qui est égal à **3**.

---

## Exercice 2 : Gestion des Étudiants et de l'Université

### Objectif
Créer deux classes associées `Etudiant` et `Universite` pour gérer les étudiants d'une université en utilisant les attributs statiques et les pointeurs.

### Description

**Classe Universite :**
- `nom` : nom de l'université.
- `afficherNom()` : affiche le nom de l'université.

**Classe Etudiant :**
- `nom` : nom de l'étudiant.
- `age` : âge de l'étudiant.
- `universite` : pointeur vers un objet de type `Universite`.
- `nbEtudiants` : attribut statique qui compte le nombre total d'étudiants créés.

### Méthodes implémentées
- **Constructeur :** initialise les informations de l'étudiant et incrémente le compteur statique.
- **afficher() :** affiche le nom, l'âge et l'université de l'étudiant.
- **afficherTotal() :** méthode statique qui affiche le nombre total d'étudiants créés.

### Test
Dans la fonction `main()` :
- Création d'une université : Université de Casablanca.
- Création de deux étudiants : Amine (20 ans) et Sara (21 ans).
- Association des deux étudiants à la même université à l'aide d'un pointeur.
- Affichage des informations des étudiants.
- Appel de `Etudiant::afficherTotal()` pour afficher le nombre total d'étudiants : **2**.

---

## Notions abordées

- Programmation orientée objet (POO) en C++.
- Définition et utilisation des classes et des objets.
- Attributs et méthodes.
- Constructeurs.
- Attributs statiques (`static`).
- Méthodes statiques.
- Association entre classes.
- Pointeurs d'objets.
- Utilisation de `nullptr`.
- Fonction principale `main()` et tests des programmes.

---

## Technologies utilisées

| Technologie | Utilisation |
|---|---|
| C++ | Langage de programmation utilisé pour les deux exercices |
| Eclipse IDE | Environnement de développement |
| Git / GitHub | Gestion et partage du code source |

---

## Conclusion

Ces deux exercices ont permis de mettre en pratique les concepts fondamentaux de la programmation orientée objet en **C++**.

Le premier exercice illustre l'utilisation des attributs et méthodes statiques pour compter les livres créés.

Le deuxième exercice renforce ces notions à travers une association entre deux classes, l'utilisation des pointeurs et le comptage du nombre total d'étudiants.

Les deux programmes contiennent une fonction `main()` permettant de tester le fonctionnement des classes et des méthodes statiques.
lab5cc/
│
├── README.md
│
├── Exercice1/
│   └── Livre.cpp
│
└── Exercice2/
    └── Etudiant.cpp
    <img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/66a61689-5080-4903-8a7d-064edf1ec2de" />
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/3c672c78-5983-4610-8cfd-d63633116375" />



