# forkify Project

A live demo of the app can be found here: [Forkify](https://forkify-app-roma.netlify.app/)

Forkify Recipe Application

1. Project Description

Forkify is a modern recipe application that allows users to search for recipes, view detailed recipe information, bookmark their favorite recipes, and upload new recipes. The application leverages the Forkify API to fetch and display recipe data in a user-friendly interface. It is designed to provide a seamless and interactive experience for users who love cooking and exploring new recipes.

2. Features

- Recipe Search: Users can search for recipes by entering keywords.
- Recipe Details: View detailed information about a selected recipe, including ingredients, cooking time, and servings.
- Bookmarking: Users can bookmark their favorite recipes for quick access.
- Recipe Upload: Users can upload their own recipes to the application.
- Pagination: Search results are paginated for better navigation.
- Servings Update: Users can dynamically update the number of servings and the corresponding ingredient quantities.

3. Technologies and Languages

- JavaScript (ES6+): The primary programming language used for the application logic.
- HTML5: Markup language used for structuring the web pages.
- CSS3: Styling language used for designing the user interface.
- Sass: CSS preprocessor used for writing more maintainable and scalable styles.
- Webpack: Module bundler used for bundling JavaScript files and other assets.
- Babel: JavaScript compiler used to convert ES6+ code into a backward-compatible version of JavaScript.
- Forkify API: External API used to fetch recipe data.

4. Packages and Libraries

- Axios: Promise-based HTTP client used for making API requests.
- Core-js: Modular standard library for JavaScript, used for polyfilling.
- Regenerator-runtime: Runtime for using async functions and generators.
- Fraction.js: Library used for handling fractional numbers in recipes.

5. Project Structure

- src/js: Contains JavaScript files for the application logic.
  - controller.js: Main controller that coordinates the interaction between the model, views, and the API.
  - model.js: Manages the application state and handles data fetching from the API.
  - views: Contains view classes responsible for rendering the UI components.
- src/sass: Contains Sass files for styling the application.
- public: Contains static assets like images and the HTML file.

Have fun!!
