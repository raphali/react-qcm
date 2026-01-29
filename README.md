# QCM ReactJS - Évaluation des fondamentaux

---

## Instructions
- Une seule réponse correcte par question
- Aucun document autorisé
- Cochez la case correspondant à votre réponse

---

### Question 1 - Introduction à React
React est :

- [ ] A) Un framework JavaScript complet  
- [ ] B) Une bibliothèque JavaScript développée par Google  
- [ ] C) Une bibliothèque JavaScript développée par Facebook (Meta)  
- [ ] D) Un langage de programmation

---

### Question 2 - Le DOM Virtuel
Quel est l'avantage principal du DOM virtuel ?

- [ ] A) Il remplace complètement le DOM réel  
- [ ] B) Il permet de ne mettre à jour que les éléments modifiés dans le DOM réel  
- [ ] C) Il supprime le besoin d'utiliser JavaScript  
- [ ] D) Il est obligatoire pour utiliser JSX

---

### Question 3 - JSX
Quelle affirmation concernant JSX est **fausse** ?

- [ ] A) JSX est transpilé en JavaScript  
- [ ] B) JSX permet d'inclure du JavaScript entre accolades `{}`  
- [ ] C) En JSX, on utilise `class` pour définir une classe CSS  
- [ ] D) JSX ne doit renvoyer qu'un seul élément parent

---

### Question 4 - JSX et JavaScript
Comment insère-t-on une variable JavaScript dans du JSX ?

- [ ] A) Avec des guillemets : `"maVariable"`  
- [ ] B) Avec des accolades : `{maVariable}`  
- [ ] C) Avec des parenthèses : `(maVariable)`  
- [ ] D) Avec le signe dollar : `$maVariable`

---

### Question 5 - Installation de React
Quelle commande permet de créer un nouveau projet React ?

- [ ] A) `npx create-react-app my-app`  
- [ ] B) `npm install react`  
- [ ] C) `npm start react`  
- [ ] D) `npm init react`

---

### Question 6 - Composants
Quelle convention de nommage est **obligatoire** pour les composants React ?

- [ ] A) Le nom doit être en minuscules  
- [ ] B) Le nom doit commencer par une majuscule  
- [ ] C) Le nom doit contenir "Component"  
- [ ] D) Le nom doit être en snake_case

---

### Question 7 - Props
Les props en React sont :

- [ ] A) Immuables et définies par le composant parent  
- [ ] B) Mutables et peuvent être modifiées par le composant enfant  
- [ ] C) Uniquement utilisables dans les composants de classe  
- [ ] D) Automatiquement synchronisées avec le state

---

### Question 8 - useState
Quel est le bon usage du hook `useState` ?

- [ ] A) `const firstname = useState('');`  
- [ ] B) `const [firstname, setFirstname] = useState('');`  
- [ ] C) `const {firstname, setFirstname} = useState('');`  
- [ ] D) `const firstname = useState('').value;`

---

### Question 9 - Mise à jour du state
Comment met-on à jour correctement un state `count` ?

- [ ] A) `count = count + 1`  
- [ ] B) `count++`  
- [ ] C) `setCount(count + 1)`  
- [ ] D) `this.count = count + 1`

---

### Question 10 - useEffect
Le hook `useEffect` est principalement utilisé pour :

- [ ] A) Déclarer des variables locales  
- [ ] B) Exécuter du code après le rendu (appels API, timers, abonnements...)  
- [ ] C) Créer des composants enfants  
- [ ] D) Définir le style des composants

---

### Question 11 - Dépendances de useEffect
Que se passe-t-il si on passe un tableau vide `[]` comme second argument de `useEffect` ?

- [ ] A) L'effet s'exécute à chaque rendu  
- [ ] B) L'effet ne s'exécute jamais  
- [ ] C) L'effet s'exécute uniquement au montage du composant  
- [ ] D) L'effet génère une erreur

---

### Question 12 - Événements
Par convention, comment nomme-t-on une fonction liée à un événement click ?

- [ ] A) `clickFunction`  
- [ ] B) `onClickFunction`  
- [ ] C) `handleClick`  
- [ ] D) `click_handler`

---

### Question 13 - Gestion des événements
Quelle syntaxe est correcte pour attacher un gestionnaire d'événement en JSX ?

- [ ] A) `<button onClick="handleClick()">Cliquer</button>`  
- [ ] B) `<button onclick={handleClick}>Cliquer</button>`  
- [ ] C) `<button onClick={handleClick}>Cliquer</button>`  
- [ ] D) `<button onClick={handleClick()}>Cliquer</button>`

---

### Question 14 - Rendu conditionnel
Quelle méthode **ne fonctionne pas** pour faire du rendu conditionnel en JSX ?

- [ ] A) L'opérateur `&&` : `condition && <A/>`  
- [ ] B) L'opérateur ternaire `condition ? <A/> : <B/>`  
- [ ] C) L'instruction `if` directement dans le JSX  
- [ ] D) Évaluer la condition en dehors du JSX

---

### Question 15 - Règles des hooks
Où peut-on déclarer un hook dans un composant React ?

- [ ] A) N'importe où dans le composant  
- [ ] B) Uniquement à la racine du composant (pas dans une condition ou boucle)  
- [ ] C) Uniquement dans le return du composant  
- [ ] D) Uniquement dans un useEffect

---

### Question 16 - Formulaires contrôlés
Dans un formulaire contrôlé, la valeur d'un input est :

- [ ] A) Gérée uniquement par le DOM  
- [ ] B) Liée à un state du composant React  
- [ ] C) Accessible uniquement via une ref  
- [ ] D) Définie une seule fois au montage

---

### Question 17 - React Router - BrowserRouter
Quel composant doit englober l'application pour utiliser React Router ?

- [ ] A) `<Router>`  
- [ ] B) `<BrowserRouter>`  
- [ ] C) `<RouteProvider>`  
- [ ] D) `<NavigationContainer>`

---

### Question 18 - React Router - Route
Quelle est la syntaxe correcte pour définir une route ?

- [ ] A) `<Route to="/about" element={<About />} />`  
- [ ] B) `<Route path="/about" component={About} />`  
- [ ] C) `<Route path="/about" element={<About />} />`  
- [ ] D) `<Route href="/about"><About /></Route>`

---

### Question 19 - React Router - Link
Pour créer un lien de navigation sans rechargement de page, on utilise :

- [ ] A) `<a href="/about">À propos</a>`  
- [ ] B) `<Link to="/about">À propos</Link>`  
- [ ] C) `<NavLink href="/about">À propos</NavLink>`  
- [ ] D) `<Route link="/about">À propos</Route>`

---

### Question 20 - Fragments
Quelle syntaxe permet d'encapsuler plusieurs éléments sans ajouter de nœud DOM supplémentaire ?

- [ ] A) `<div>...</div>`  
- [ ] B) `<span>...</span>`  
- [ ] C) `<>...</>` ou `<Fragment>...</Fragment>`  
- [ ] D) `<wrapper>...</wrapper>`
