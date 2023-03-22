# Shop Shop-Redux

Shop Shop is an e-commerce site in which you can purchase products and checkout using stripe. This application is refactor of the original [Shop-Shop](https://github.com/MAsuamah/shop-shop) which used React’s Context API to handle global state. Shop Shop Redux uses the [Redux](https://redux.js.org/) library to handle global state.

![screencapture-masuamah-shop-shop-herokuapp-2021-07-04-15_35_51](https://user-images.githubusercontent.com/77217156/124397556-7a70df00-dcde-11eb-9c76-df584e77ee6a.png)

## User Story

`AS a senior engineer working on an e-commerce platform`<br/>
`I WANT my platform to use Redux to manage global state instead of the Context API`<br/>
`SO THAT my website's state management is taken out of the React ecosystem`

### Acceptance Criteria

`GIVEN an e-commerce platform that uses Redux to manage global state` <br/>
`WHEN I review the app’s store` <br/>
`THEN I find that the app uses a Redux store instead of the Context API` <br/>
`WHEN I review the way the React front end accesses the store` <br/>
`THEN I find that the app uses a Redux provider` <br/>
`WHEN I review the way the app determines changes to its global state` <br/>
`THEN I find that the app passes reducers to a Redux store instead of using the Context API` <br/>
`WHEN I review the way the app extracts state data from the store`<br/>
`THEN I find that the app uses Redux instead of the Context API`<br/>
`WHEN I review the way the app dispatches actions`<br/>
`THEN I find that the app uses Redux instead of the Context API`<br/>

## Features

### Sorting by Category

Sort by categories such as Food, Household Supplies, Electronics, Books, and Toys (as pictured below) while you shop.

![screencapture-masuamah-shop-shop-herokuapp-2021-07-04-15_36_18](https://user-images.githubusercontent.com/77217156/124397602-d63b6800-dcde-11eb-8d43-73ae81888e92.png)

### Login/Signup

Login or sign up in order to checkout your purchase.

![screencapture-masuamah-shop-shop-herokuapp-signup-2021-07-04-15_38_36](https://user-images.githubusercontent.com/77217156/124397735-b0fb2980-dcdf-11eb-99a9-6aade1f9fc23.png)

### Shopping Cart

Easy access to your shopping cart as you add items. You can adjust product quantity and remove items. 
The checkout option is only available when you are signed in.

![screencapture-masuamah-shop-shop-herokuapp-2021-07-04-15_39_12](https://user-images.githubusercontent.com/77217156/124397666-49dd7500-dcdf-11eb-89a9-1459e95f1015.png)

### Stripe/Checkout

The Shop Shop uses stripe as a simple and secure way to complete order payments. You can test out the functionality by using a fake 
credit card number `4242 4242 4242 4242`. The rest of the payment info can be anything.

![screencapture-checkout-stripe-pay-cs-test-b1gOvhbzcuGlgppOsh1uKJ11GnvuFdqWZYJgKDUpmQS8jEERHJkVvtd10H-2021-07-04-16_02_36](https://user-images.githubusercontent.com/77217156/124398010-70041480-dce1-11eb-8f24-c47289e318c0.png)


## Built With
* MongoDB
* Express.js
* React.js
* Node.js
* Stripe
* Redux

## Website
https://masuamah-shop-shop-redux.herokuapp.com/

## Contributors
Michelle Asuamah

## Contact
If you would like to contact me you can reach me at michey.asmah21@gmail.com.
