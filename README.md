#  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Shop-Shop

[Summary](#Summary) &nbsp; &nbsp; [Introduction](#Introduction) &nbsp; &nbsp; [Mock-Up](#Mock-up) &nbsp; &nbsp; [Built With](#Built-With) &nbsp; &nbsp; [User Story](#User-Story) &nbsp; &nbsp; [Acceptance Criteria](#Acceptance-Criteria)  &nbsp; &nbsp; [Code Review](#Code-Review)   

 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [***Live Project***](#Live-Project)

## Summary

 Shop-Shop is an e-commerce web application.

## Introduction
 
 This website is e-commerce app built with a GraphQL API built with Apollo Server and Redux. The app is built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API.    

## Live Project

Visit [website](https://aqueous-eyrie-25049.herokuapp.com/) and enjoy shopping!

## Mock-Up
The following image shows the web application's appearance and functionality.  

![Mock-up image](client/public/mock-up.png "Mock-up image")

## Built With
* [MongoDB](https://www.mongodb.com/)
* [Express.js](https://expressjs.com/)
* [React](https://reactjs.org/)
* [Node.js](https://nodejs.org/en/)
* [JavaScript](https://www.javascript.com/) ES5 ES6  
* [React Router](https://reactrouter.com/)
    * [React Router DOM](https://www.npmjs.com/package/react-router-dom)
* [GraphQL](https://graphql.org/)
    * [graphql](https://www.npmjs.com/package/graphql)
    * [graphql-tag](https://www.npmjs.com/package/graphql-tag)
* [JWT:JSON web Token](https://www.npmjs.com/package/jsonwebtoken)
    * [JWT Decode](https://www.npmjs.com/package/jwt-decode)
* [Appolo Server](https://www.apollographql.com/docs/apollo-server/)
    * [Appolo Client](https://www.apollographql.com/docs/react/)
    * [Appolo Server Express](https://www.npmjs.com/package/apollo-server-express)
    * [Appolo Boost](https://www.npmjs.com/package/apollo-boost)
    * [Appolo React Hooks](https://www.npmjs.com/package/@apollo/react-hooks)
* [if-env](https://www.npmjs.com/package/if-env)
* [concurrently](https://www.npmjs.com/package/concurrently)
* [Faker.js](https://www.npmjs.com/package/faker)
* [nodemon](https://www.npmjs.com/package/nodemon)
* [bcrypt](https://www.npmjs.com/package/bcrypt)
* [Mongoose](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/mongoose)
* [Heroku](https://www.heroku.com/)
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas2)
* [Indexed DB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
* [Redux](https://redux.js.org/)
* [Stripe](https://www.npmjs.com/package/stripe)
* [stripe.js](https://www.npmjs.com/package/@stripe/stripe-js)


## User Story
<details>
<summary>Expand</summary>  

    AS AN online shopper
    I WANT to search for categorised items
    SO THAT I can shop in this website

    User Stories to convert into Redux State Management System

    AS a senior engineer working on an e-commerce platform
    I WANT my platform to use Redux to manage global state instead of the Context API
    SO THAT my website's state management is taken out of the React ecosystem
</details>

## Acceptance Criteria
<details>
<summary>Expand</summary>

    GIVEN an e-commerce website
    WHEN I open the home page
    THEN I am presented with options of category of items to shop from , shopping cart and options to login or signup
    WHEN I choose a category of product
    THEN I am presented with all the items of that category, its price and an option to add it to cart
    WHEN I view one product
    THEN I am presented with a brief description of the product, its price and options to add and remove to/from the cart
    WHEN I open the shopping cart
    THEN it shows the list of items added and their inidiviadual and total price, ability to change the quantity and delete the item
    WHEN I login
    THEN I am able to checkout the items added to the cart and able to see my order histories
    WHEN I checkout
    THEN I am able to pay with card and message is shown and automatically returned to homepage after three seconds

    Acceptance criteria to convert to Redux State Management System

    GIVEN an e-commerce platform that uses Redux to manage global state
    WHEN I review the app???s store
    THEN I find that the app uses a Redux store instead of the Context API
    WHEN I review the way the React front end accesses the store
    THEN I find that the app uses a Redux provider
    WHEN I review the way the app determines changes to its global state
    THEN I find that the app passes reducers to a Redux store instead of using the Context API
    WHEN I review the way the app extracts state data from the store
    THEN I find that the app uses Redux instead of the Context API
    WHEN I review the way the app dispatches actions
    THEN I find that the app uses Redux instead of the Context API
  
</details>

## Code Review

The completed project is uploaded in *** Github ***.  
Repository link:  [GitHub](https://github.com/rosefrancis-tech/shop-shop)  