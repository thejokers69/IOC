### Contenu du fichier `README.md` :

```markdown
# Injection de Dépendances en Java

Ce projet montre différentes méthodes d'injection de dépendances en Java, incluant l'implémentation d'interfaces, des exemples de couplage faible, ainsi que l'utilisation du framework Spring.

## Fonctionnalités

- Création d'une interface `IDao` avec la méthode `getData()`.
- Création d'une implémentation de `IDao` (ex: `DaoImpl`).
- Création d'une interface `IMetier` avec la méthode `calcul()`.
- Implémentation de `IMetier` en utilisant le couplage faible (ex: `MetierImpl`).
- Injection de dépendances via trois méthodes :
  - Instanciation statique
  - Instanciation dynamique via réflexion
  - Utilisation du framework Spring (XML et annotations)

## Installation et Exécution

1. Cloner ce dépôt sur votre machine :
   ```bash
   git clone https://github.com/ton-repo/injection-dependances.git
   ```
2. Compiler et exécuter le projet en ligne de commande ou dans votre IDE.

### Exemple d'exécution

- Injection par instanciation statique :
  ```bash
  Résultat : 58.4
  ```
  
- Injection par Spring avec XML :
  ```bash
  Résultat : 63.2
  ```

## Structure du projet

- **src/main/java** : Contient les interfaces et classes d'implémentation (`IDao`, `IMetier`, `DaoImpl`, `MetierImpl`).
- **resources** : Contient les fichiers de configuration Spring (fichier XML pour la configuration des beans).

## Technologies

- **Java**
- **Spring Framework** (pour l'injection de dépendances)
- **Maven/Gradle** (pour la gestion des dépendances)

## Auteurs

Projet réalisé par : Mohamed Lakssir 2ACI Info 

```
