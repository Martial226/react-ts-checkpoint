#  Point de Contrôle : Création d'applications React avec TypeScript

Ce projet est une conversion de composants React écrits en JavaScript vers TypeScript, dans le cadre du point de contrôle "Créer des applications React avec TypeScript".

##  Objectif

- Comprendre et utiliser TypeScript avec React.
- Convertir des composants fonctionnels et des classes en TypeScript.
- Utiliser les interfaces pour typer les props et le state.

##  Étapes de conversion

1. **Initialisation du projet avec Vite** :
   - Commande : `npm create vite@latest react-ts-checkpoint --template react-ts`
   - On choisit le variant `react-ts` pour avoir directement le support TypeScript.

2. **Création de deux composants dans le dossier `components`** :
   - `Greeting.tsx` (fonctionnel avec props typées)
   - `Counter.tsx` (classe avec props et state typés)

3. **Ajout d’interfaces TypeScript** :
   - `GreetingProps` pour les props de `Greeting`
   - `CounterProps` et `CounterState` pour `Counter`

4. **Remplacement du type `any` par des types explicites** :
   - `string`, `number`, etc.

5. **Ajout de commentaires dans le code pour expliquer chaque modification.**

##  Structure du projet

