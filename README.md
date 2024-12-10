# Projet : Processeur 4 bits

Ce dépôt GitHub contient les fichiers et ressources nécessaires au développement d'un processeur rudimentaire de 4 bits dans le cadre du cours **Bases d'électronique numérique**.

## Objectif du projet

L'objectif est de modéliser et simuler un processeur 4 bits à l'aide de Simulink. Ce projet permet de consolider les notions clés d'électronique numérique, notamment :

- Logiques combinatoires (Unité Arithmétique et Logique - UAL),
- Logiques séquentielles (Registres),
- Machines à états finis (Unité de contrôle).

## Fonctionnalités principales

Le processeur sera capable d'exécuter les opérations suivantes grâce à son Unité Arithmétique et Logique (UAL) :

- `A OR B` : Opération logique OU,
- `A AND B` : Opération logique ET,
- `NOT B` : Négation de l'opérande B,
- `A + B` : Addition,
- `A - B` : Soustraction,
- Compteur personnalisé.

Les instructions seront codées sur **11 bits**, divisées comme suit :
- `ImmA` (4 bits) : Valeur immédiate de l'opérande A.
- `ImmB` (4 bits) : Valeur immédiate de l'opérande B.
- `CodOp` (3 bits) : Code de l'opération à exécuter.

## Structure du projet

Le projet se décompose en plusieurs modules, chacun représentant une composante du processeur :

1. **Registre PIPO 4 bits** : Stockage des opérandes et du résultat.
2. **UAL (Unité Arithmétique et Logique)** : Exécution des opérations arithmétiques et logiques.
3. **Multiplexeur** : Sélection du résultat de l'UAL en fonction de la commande.
4. **Unité de contrôle (Machine à états)** : Décodage des instructions et contrôle des signaux.
5. **Processeur complet** : Intégration de tous les modules pour simuler un processeur 4 bits fonctionnel.

## Organisation du travail

Le projet est réalisé en équipes de 3 à 4 personnes avec :
- Un chef de projet responsable de la coordination et de la gestion du travail.
- Une répartition claire des tâches entre les membres.

## Livrables

Les livrables attendus sont :
1. **Code source** : Modèles Simulink pour chaque composant et le processeur final.
2. **Rapport** : Documentation détaillant les démarches, les tables de vérité, les équations et les logigrammes.
3. **Soutenance orale** : Présentation finale du projet.

## Utilisation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/processeur-4-bits.git
