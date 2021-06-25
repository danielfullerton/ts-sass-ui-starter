# Goal of the Project
This goal of this project is to give you a pre-made application already set up to use TypeScript, SASS and Bootstrap.

# Installing
Clone the repository and run
```shell
npm install
```

# Running the application
To run the app using the pre-configured webpack dev server, simply run
```shell
npm start
```

# Building the app for deployment
To build the app into a bundle that can be used in a non-local environment, run
```shell
npm run build
```

This will output your HTML and bundled JavaScript (`index.html` and `index.js`, respectively) to the `/dist` folder.

# Notes
- The project comes with Bootstrap 4 set up already. However, if you want to remove it, you can remove
this line from `index.html`:
```html
  <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.css">
```

- In order to have your `.scss` files compiled and included in your bundle, make sure import them in your
TypeScript code somewhere. For example, by default the file `styles.scss` is imported in `index.ts` as so:
```typescript
import './styles.scss';
```
