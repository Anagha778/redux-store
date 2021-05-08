# Redux shopping store

## Description
This is a online shopping store build using MERN SPA, built using GraphQL API with Apollo Server. The app is built using the ```MERN stack```, with a ```React front end```, ```MongoDB database```, and ```Node.js/Express.js``` server and ```Grapgql API```. ```Redux``` is used to store global state of the store. ```Stripe``` library is used to test payments.

* Application allows users to add products in cart and make payment.  
* Users are able to create an account when providing user name, email and password.  
* Logged in users will be able to add items to cart, delete item from cart and make payment for items in the cart.  

### key parts of using React-Redux with React:  
```
* Call the useSelector hook to read data in React components  
* Call the useDispatch hook to dispatch actions in React components  
* Put <Provider store={store}> around your entire <App> component so that other components can talk to the store  
```
### Reference

https://redux.js.org/tutorials/fundamentals/part-5-ui-react

## Deployed application

https://tranquil-escarpment-13333.herokuapp.com/

## User story
```
AS a senior engineer working on an e-commerce platform  
I WANT my platform to use Redux to manage global state instead of the Context API  
SO THAT my website's state management is taken out of the React ecosystem  
```
## Acceptance Crieteria
```
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

## Mock up

###### SignUp

<div>
    <img src="./images/1.gif" width="500px"/> 
</div>

###### Add and Remove product from cart

<div>
    <img src="./images/2.gif" width="500px"/> 
</div>

###### Checkout items

<div>
    <img src="./images/3.gif" width="500px"/> 
</div>

## Built With
* HTML
* CSS
* JavaScript
* MongoDB
* Express js
* Node js
* React js
* React-redux
* Redux