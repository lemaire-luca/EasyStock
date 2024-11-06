# EasyStock 📝

## Table des matières

1. [Présentation du projet](#présentation-du-projet)
2. [Étude de l’existant](#étude-de-lexistant)
3. [Public cible](#public-cible)
4. [Fonctionnalités principales](#fonctionnalités-principales)
5. [Guide de développement](#guide-de-développement)

---

## Présentation du projet

**EasyStock** est une application mobile simple et intuitive, conçue pour gérer facilement l’inventaire alimentaire du quotidien, seule ou bien à plusieurs.
Cette application vous permet d’ajouter rapidement des produits à des listes d'inventaire et à une liste de courses, ainsi que de suivre leurs dates d’expiration et la quantité restante. L’application envoie des alertes avant la péremption et des rappels pour faire les courses en fonction des quantités restantes dans l'inventaire. **EasyStock** aide ainsi à réduire le gaspillage alimentaire, à économiser du temps et de l'argent, tout en améliorant l'organisation au quotidien.


EasyStock permet, entre autres, de :
- Gérer un inventaire d'aliments dans un lieu de résidence.
- Recevoir des rappels pour une date de péremption ou bien une quantité insuffisante.
- Partager des listes d'inventaire avec d’autres utilisateurs.
---
```
## Structure du dépôt

Voici un aperçu des principaux dossiers et fichiers présents dans le dépôt :

- **/lib/** : Contient l'ensemble du code source de l'application. L’organisation des fichiers est pensée pour une lisibilité optimale et une modularité du code. Chaque fonctionnalité est séparée dans des sous-dossiers dédiés (ex: `/lib/models/`, `/lib/screens/`, `/lib/services/`).
  
- **/assets/** : Ce dossier contient toutes les ressources multimédia de l’application, comme les images et les icônes.
  
- **/designs/** : Vous trouverez ici les maquettes de l'application. Nous avons utilisé des outils comme Figma pour réaliser des maquettes interactives que vous pouvez consulter pour comprendre l’interface utilisateur (UI/UX).

- **/docs/** : Documentation technique supplémentaire, incluant une analyse plus poussée des choix technologiques et de la structure de base de données.

---
```

## Étude de l’existant

Avant de concevoir EasyStock, j'ai recherché des applications similaires déjà disponibles sur le marché, mais aucune application de gestion d'inventaire n'a été trouvée. Voici un résumé des principales concurrentes :

| Application  | Avantages                                          | Inconvénients                                        |
|--------------|----------------------------------------------------|------------------------------------------------------|
| Sortly       | Interface simple et intuitive                      | Fonctionnalités avancées payantes                    |

**Résumé** : Les applications existantes offrent de nombreuses fonctionnalités intéressantes, mais EasyStock se distingue par une interface plus personnalisable et des fonctionnalités de gestion avancée sans abonnement payant.

---

## Public cible

Mon application s’adresse à plusieurs segments de la population :

1. **Les étudiants**
2. **Les jeunes professionnels**
3. **Les parents**

J'ai pris en compte ces utilisateurs en développant une interface claire et intuitive, et en intégrant des options de personnalisation adaptées à leurs besoins spécifiques.

---

## Fonctionnalités principales

Voici quelques fonctionnalités phares de EasyStock, présentées sous forme de récits utilisateurs.

### 1. Gestion de l'inventaire

- Ajouter facilement des produits à votre inventaire en un seul geste.
- Retirer les aliments périmés ou utilisés pour maintenir un stock à jour et précis.
- Modifier aisément la quantité des produits disponibles afin de suivre en temps réel vos stocks.

---

### 2. Partage de listes

Il est possible de partager un groupe disposant d'une liste de courses ou d'un inventaire, permettant ainsi une gestion collaborative et optimisée des produits au sein de la famille ou entre amis.

---

### 3. Recevoir des rappels 

Vous recevrez des notifications dès qu'un produit approche de sa date de péremption ou lorsqu'il manque de quantité, vous permettant ainsi de mieux gérer vos stocks et d'éviter tout gaspillage.

---
```
## État d'avancement

| Fonctionnalité           | État            | GIF illustratif                                |
|--------------------------|-----------------|------------------------------------------------|
| Création de tâches        | Terminé         | ![GIF création tâche](./gifs/task_creation.gif) |
| Partage de listes         | En développement| En attente du GIF                              |
| Statistiques productivité | À implémenter   | En attente du GIF                              |
```
---

### Installation

1. Clonez le dépôt :  
   ```bash
   git clone https://github.com/lemaire-luca/EasyStock.git
   ```
2. Accédez au répertoire du projet :  
   ```bash
   cd EasyStock
   ```
3. Installez les dépendances :  
   ```bash
   flutter pub get
   ```
4. Lancez l'application sur un émulateur ou un appareil physique :  
   ```bash
   flutter run
   ```
   
### Clés API

Certaines fonctionnalités de MyApp, telles que la synchronisation en ligne, nécessitent des clés API. Ces dernières doivent être ajoutées dans le fichier `.env` que vous trouverez à la racine du projet. Voici un exemple :

```bash
API_KEY=your_api_key_here
```

---

## Remerciements

Merci à tous les contributeurs et aux testeurs qui ont permis de rendre cette application possible.
```
