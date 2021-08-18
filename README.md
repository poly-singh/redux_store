# Redux Store

## Description
This is a ecommerce website application. There are different products, user can add products to the cart and checkout using stripe API. It has been refractored to use redux for Application state.

## Deployed link and Screenshots
https://redux-shopping-ps.herokuapp.com/ 

## Screenshot of the app
![Book_search](./assets/images/Book_search.png)

## User Story

```md
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
```

## Acceptance Criteria

```md
GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API
```

## Installation

```
clone the repo
npm install
npm run develop

```
## Usage

```
Go to the application and login or signup to the application.
Browse the products. Add or remove to the cart and checkout.

```

## Github

https://github.com/poly-singh/redux_store 

