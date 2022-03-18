# eShop (An eCommerce Platform)
to see the app in action,go to https://eshoppapp.herokuapp.com/
> eCommerce platform built with the MERN stack

![Homepage](https://user-images.githubusercontent.com/81861223/159056903-3af53b10-526a-40bc-8f03-c7e42e638c03.jpeg)
![product-page](https://user-images.githubusercontent.com/81861223/159056934-30f7aedc-2411-4723-8c41-2349ac83ea65.jpeg)
![cart-page](https://user-images.githubusercontent.com/81861223/159056950-0d0a6f7b-24de-41b2-a132-c30944cabd5e.jpeg)

## Features

- Full featured shopping cart
- Product reviews and ratings
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

### Libraries & Frameworks

- [mongoDB](https://www.mongodb.com/)
- [express](https://expressjs.com/)
- [react](https://reactjs.org/)
- [node](https://nodejs.org/en/)
- [react-router-dom](https://reactrouter.com/web/guides/quick-start)
- [jwt](https://jwt.io/)
- [mongoose](http://mongoosejs.com/)
- [Heroku](https://www.heroku.com/)

### Env Variables

Create a .env file in the root and add the following

```
NODE_ENV = development
PORT = 3005
MONGO_URI = your mongodb uri
JWT_SECRET = putYourSecret
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:3005)
npm run dev
# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

There is a Heroku postbuild script, so if you push to Heroku, no need to build manually for deployment to Heroku

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import
# Destroy data
npm run data:destroy
```
