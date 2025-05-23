# JAVASCRIPT FRAMEWORKS CA
[view here](https://ecommerce-shopping-store.netlify.app/)

## List todo
- Process
- Create a new CRA app.
- Create a Header that has a Nav.
- Create a Cart Icon component and position this next to your Nav. This Cart Icon component will have an overlay that displays the number of items in the cart.
- Create a Footer component
- Create a Layout component that has your Header and Footer.
- Create the other pages:

## Pages

- [ /] Homepage
- [ /] SingleItem Page
- [ /] Product Page
- [ /] Checkout Success Page
- [ /] Cart Page
- [ /] Checkout Page
- [ / ] Contact Page
- [ /] Contact Success Page

## Details

- ### HomePage

  - [ /] List of all the Products
  - [ /] Search Bar with filters when typing the product name.
  - [ /] Upon clicking, it will go to the singleItem or individual products.

- Pages

  - [ /] Using a Layout component that contains a header and footer.
  - [ /] Header should contain a nav bar and cart icon component that acts as a button with many items increment and decrement.

- ### Individual/ Single Item Page

  - [ /] Display data of a single product
  - [ /] Have an add-to-cart button that adds and minus the product in the cart upon clicking.

- ### Product Page

  - [ /] Display the product title, description, and image.
  - [ /] Have reviews listed for the product.
  - [ /] Use discounted price property to display the product's price.
  - [ /] Display of the calculated discounted price and total Price.

- ### Cart Icon

  - [ /] Clicking the Cart icon will load cartPage, which shows the list of all the products chosen and the total price.
  - [ /] Have a checkout button.
  - [ /] Upon clicking the button, it will reach the checkout success page.

- ### Contact Page

  - [ /] Should have validations.
  - [ /] Full name (Minimum number of characters is 3, required)
  - [ /] Subject (Minimum number of characters is 3, required)
  - [ /] Email (Must be a valid email address, required)
  - [ /] Body (Minimum number of characters is 3, required)
  - [ /] Submit button

- ### Designs

  - [ /] Should be responsive
  - [ /] Welcome to use CSS Framework or do it from scratch or using CSS Modules.

## OTHER REQUIREMENTS

- [ /] You will be using React Router to switch between pages.
- [ /] You are not required to use TypeScript.
- [ /] Your code is expected to be clean and well-formatted.
- [ /] Add React Router and route to each of the pages. The ProductPage page will be using a dynamic segment.
- [ /] Fetch the list of products on the Homepage and store this as a state.
- [ /] On the homepage, loop through the products and display a Product component for each value.
- [ /] Each Product component will have a View product button that links to the product page.
- [ /] The homepage should have a lookahead Search bar component.
- [ /] Typing values in the search bar should display products whose title matches the search input.
- [ /] Clicking on an item should take the user to the product page.
- [ /] On the product page, use the product ID as the params for the dynamic segment.
- [ /] Add the product details as mentioned in brief.
- [ /] Create a cart state. When the Add to cart button on the product page is clicked, add the product to the cart.
- [ /] Clicking on the Cart Icon component will take the user to the checkout page.
- [ /] The CheckoutPage must list all the products in the cart, show a total at the bottom, and a Checkout button.
- [ /] Clicking the Checkout button will take the user to the CheckoutSuccessPage.
- [ /] The CheckoutSuccessPage should display the successful order and clear the cart.
- [ /] There should be a link to return to the store.
- [ /] Console.log the data from the form once validation requirements are met.
- [ /] Once your project is done, deploy it to Netlify.

## Marking Criteria

- [ /] Using React correctly
- [ /] The submission has well-structured and formatted code.
- [ /] Best practices are following, such as having a component in its own folder.
- [ /] There are no errors in the console.
- [ /] The App runs without any errors, rs and there are no errors in the console
  has knowledge of industry-relevant JavaScript frameworks and has knowledge of the difference between a library, framework, and run-time script engine.Has
  has knowledge of principles for software architecture and design patterns that frameworks are built on, such as MVCEvent-driven architecture etc.
- [ /] Is familiar with the possible risks of using less-known JavaScript frameworks.
- [ /] Using libraries and common design patterns
- [ /] The app uses React Router.
- [ /] The app uses a Layout component.
- [ /] The data is from the specified API.
- [ /] Dynamic segments are used for the Product page
  can explain his/her choice of JavaScript framework
  can explain the functionality of the JavaScript framework and the architecture behind the different frameworks, and the reasons for using these frameworks
  Can reflect on his/her own choices and use JavaScript frameworks in the development of digital solutions and adjust it under supervision with the overall development
  can find and refer to technical information about the JavaScript framework and assess its relevance for each specific project
- [ /] All features delivered
- [ /] The submission features a home page that contains a list of products and a lookahead search bar.
- [ /] The submission features an individual product page that fetches a particular item from the API.
- [ /] The submission features a cart icon that displays the number of items in the cart.
- [ /] The submission features a checkout page.
- [ /] The submission features a checkout success page.
- [ /] The submission features a contact page with the correct validation.
- [ /] The submission contains a shopping cart that can have products added to it.
- [ /] Look ahead and plan and carry out work with JavaScript frameworks and develop solutions based on specifications
  can exchange points of view with his/her peers and participate in discussions about the use of JavaScript frameworks in the development of digital solutions

## Technologies Used

The following libraries and tools were used in the development of this project:

### 1. **React** 
   - **Version**: `^19.0.0`
   - React is a popular JavaScript library for building user interfaces. It allows us to create reusable components and manage the state of our application efficiently.

### 2. **React DOM**
   - **Version**: `^19.0.0`
   - React DOM is used to render React components into the DOM and manage the web app's UI updates.

### 3. **Redux**
   - **Version**: `^5.0.1`
   - Redux is a state management library that helps us manage the application's state in a centralized store, making the state accessible from any component.

### 4. **React-Redux**
   - **Version**: `^9.2.0`
   - React-Redux is a set of bindings for using Redux with React. It allows us to interact with the Redux store from React components.

### 5. **React Router DOM**
   - **Version**: `^7.1.1`
   - React Router DOM enables us to handle routing in the application, allowing users to navigate between different pages.

### 6. **Axios**
   - **Version**: `^1.7.9`
   - Axios is a promise-based HTTP client that is used to make API calls to the backend and retrieve data asynchronously.

### 7. **Styled Components**
   - **Version**: `^6.1.13`
   - Styled Components is a library for styled components, allowing us to write plain CSS inside JavaScript files to style components in a modular and reusable way.

### 8. **Bootstrap**
   - **Version**: `^5.3.3`
   - Bootstrap is a front-end framework used for building responsive, mobile-first websites. It provides pre-built components and utilities for quickly styling the app.

### 9. **Font Awesome**
   - **Version**: `^6.7.2`
   - Font Awesome is a popular icon library used for adding scalable vector icons to the UI.

### 10. **React Toastify**
   - **Version**: `^11.0.2`
   - React Toastify is a library for displaying toast notifications in React applications, which is used here for showing messages to users.

### 11. **React Scripts**
   - **Version**: `^5.0.1`
   - React Scripts is used to provide the necessary build tools for React applications. It simplifies the setup and handling of Webpack, Babel, and other development tools.

### 12. **Web Vitals**
   - **Version**: `^4.2.4`
   - Web Vitals is a library used to measure essential web performance metrics like loading time, interactivity, and visual stability.

### 13. **Jest & React Testing Library**
   - **Jest**:
     - **Version**: `^26.6.3`
     - Jest is a testing framework used for writing unit and integration tests for React applications.
   - **React Testing Library**:
     - **Version**: `^16.1.0`
     - React Testing Library is used for testing React components in a way that simulates real user behavior, ensuring better test reliability.

### 14. **ESLint**
   - ESLint is a static code analysis tool used to identify and fix problems in the JavaScript codebase. The configuration is set up for React development and Jest testing.

