
# SHOPPLUSPLUS - ECOMMERCE App

Shopplusplus is an Ecommerce App app that allows users to Online Shopping  Buy mobiles, laptops, cameras, books, watches, apparel, shoes and e-Gift Cards. Free Shipping. This app is built using React for the frontend and Node.js for the backend. The app is deployed on Heroku for easy and scalable hosting.

![SHOPPLUSPLUS](https://res.cloudinary.com/dlhke10we/image/upload/v1701968027/ss_jkwucx.png)

## Features
Product Listing : Display a list of products with details (name, price, image, description).
Implement pagination for large product catalogs.

Product Details : Show detailed information about a product when clicked.Include options for quantity and an "Add to Cart" button.

Shopping Cart: Allow users to add/remove items from the cart,Show the total price and quantity in the cart.

User Authentication: Implement user registration and login,Secure user authentication and authorization.

User Profiles: Enable users to view and edit their profiles,Show order history and tracking information.

Admin Dashboard: Create an admin interface to create products, and manage products, orders, and users.

Reviews and Ratings: Allow users to leave reviews and ratings for products.

Payment Integration: Integrate with a payment gateway for secure transactions.



# Tech Stack

**Client:** React, Redux, Material UI

**Server:** Node, Express, Axios, Mongoose, Stripe

**Database:** MongoDB


## Run Locally

Clone the project

```bash
  git clone https://github.com/ashish123256/ShopPlusPlus-EcommerceMern.git
```

**For Client**
```bash
  cd ./SHOPPLUSPLUS/frontend
```
Start the server

```bash
  npm start
```
**For Server**
```bash
  cd ./SHOPPLUSPLUS/backend
```
Start the server

```bash
  npm run dev
```


# Install Dependencies

**For Backend** - `npm i`

**For Frontend** - `cd frontend` ` npm i`


## Heroku Deployment

To deploy this project run

```bash
  Heroku deploy
```


## Env Variables

Make Sure to Create a config.env file in backend/config directory and add appropriate variables in order to use the app.

**Essential Variables**
PORT=
,
DB_URL =
,
STRIPE_API_KEY=
,
STRIPE_SECRET_KEY=
,
JWT_SECRET=
,
JWT_EXPIRE=
,
COOKIE_EXPIRE=
,
SMTP_SERVICE =
,
SMTP_MAIL=
,
SMTP_PASSWORD=
,
SMTP_HOST=
,
SMTP_PORT=
,
CLOUDINARY_NAME=
,
CLOUDINARY_API_KEY=
,
CLOUDINARY_API_SECRET=
,

_fill each filed with your info respectively_



## Authors

- [Ashish Babu Rao](https://github.com/ashish123256)


