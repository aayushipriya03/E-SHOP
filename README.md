# MeShop (An eCommerce Platform)

> eCommerce platform built with the MERN stack

https://user-images.githubusercontent.com/76219383/158903493-9f8bc8e5-b82c-4605-8556-cfa87b92d697.mp4

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
