# Component Map

In this activity we will map over a list of data and render components from each piece of data.

## Instructions

* Replace your React application's `src` folder with [src](Unsolved/src). Stop the dev server if it is already running. Start the app in dev mode by running `npm start`.

* This activity uses Bootstrap. Be sure to add the Bootstrap CDN to your React app's `index.html` file:

  ```html
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.0.0/css/bootstrap.min.css"/>
  ```

* Open the application in your web browser and study the rendered application. Then take a minute to study the included components:

  * **App**: Our Application's root component.

  * **List**: Responsible for rendering an unordered list from `props.data`.

* Modify the `List` component so that inside of its `ul` tags, it renders one `li` tag for each item in array of grocery objects being passed via props. Each `li` tag should display the `text` property of each grocery object. The array map method should be used for this.

* For styling purposes, give each `li` tag a class of `list-group-item`.

### Hints

* You should definitely look at [React's documentation for lists and keys](https://facebook.github.io/react/docs/lists-and-keys.html)

* See MDN Documentation for [Array.prototype.map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map).

* You will only need to modify the `List` component.

### Bonus

* Inside of the `List` component, render a list of **only** the groceries which **have not** been purchased. Use the [Array.prototype.filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) to filter the array before mapping.




# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
"# practice mapping through a components properties it pulls from a json file with data" 
