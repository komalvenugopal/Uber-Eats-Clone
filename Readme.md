# Uber Eats Clone

<br/>

## 02. Frontend

<br/>

### 14.0 - Create React App

    $ npx create-react-app . --template=typescript

<br/>

### 14.1 - 14.2 - TailwindCSS

    $ yarn add tailwindcss postcss autoprefixer

    $ npx tailwindcss init
    $ npm run tailwind:build

<br/>

### 14.3 - Apollo Setup

    $ yarn add @apollo/client graphql

<br/>

### 14.4 - React Router Dom

    $ yarn add react-router-dom

<br/>

### 15.0 - Local-Only Fields

<br/>

### 15.1 - React Hook Form

https://react-hook-form.com/

    $ npm instl react-hook-form

<br/>

### 15.2 - React Hook Form (part 2)

<br/>

### 15.3 - Router and types

    $ npm instl @types/react-router-dom

<br/>

### 15.4 - Form Design

<br/>

![Application](/img/pic-part02-les15-pic01.png?raw=true)

<br/>

### 15.5 - Form Login

<br/>

![Application](/img/pic-part02-les15-pic02.png?raw=true)

<br/>

### 15.6 - Login Mutation (part 1)

<br/>

### 15.7 - Apollo Codegen

    $ yarn add -g apollo
    $ yarn add apollo

<br/>

    $ npm run apollo:codegen

<br/>

### 15.8 - 15.9 - Login Mutation

<br/>

### 15.10 - 15.11 - UI-Clonning

<br/>

![Application](/img/pic-part02-les15-pic03.png?raw=true)

<br/>

### 15.12 - Create Account Mutation

    $ yarn add react-helmet
    $ yarn add @types/react-helmet

<br/>

![Application](/img/pic-part02-les15-pic04.png?raw=true)

<br/>

### 15.13 - Create Account Mutation (part Two)

http://emailregex.com/

<br/>

### 15.14 - Saving the Token

    $ yarn add react-helmet-async

<br/>

### 15.15 - Using the Token

<br/>

![Application](/img/pic-part02-les15-pic05.png?raw=true)

<br/>

### 15.16 - Routers and 404s

<br/>

![Application](/img/pic-part02-les15-pic06.png?raw=true)

<br/>

### 15.17 - 15.18 - Header

https://github.com/FortAwesome/react-fontawesome#documentation

    $ yarn add @fortawesome/fontawesome-svg-core
    $ yarn add @fortawesome/free-solid-svg-icons
    $ yarn add @fortawesome/react-fontawesome

<br/>

![Application](/img/pic-part02-les15-pic07.png?raw=true)

<br/>

### 16.0 - 16.1 - Verifying Email

<br/>

![Application](/img/pic-part02-les16-pic01.png?raw=true)

<br/>

### 16.2 - 16.3 - Edit Profile

<br/>

![Application](/img/pic-part02-les16-pic02.png?raw=true)

<br/>

### 16.4 - writeFragment vs Refetch

<br/>

### 17.0 - Restaurants Query

<br/>

### 17.1 - Categories Style

**Images categories:**

```
https://d4p17acsd5wyj.cloudfront.net/shortcuts/cuisines/bbq.png
https://d4p17acsd5wyj.cloudfront.net/shortcuts/cuisines/dessert.png
https://d4p17acsd5wyj.cloudfront.net/shortcuts/cuisines/asian.png
https://d4p17acsd5wyj.cloudfront.net/shortcuts/cuisines/italian.png
```

```
// CREATE ACCOUNT OWNER
// LOGIN
// CREATE RESTAURANT OWNER
// CREATE RESTAURANT
// GET ALL CATEGORIES
```

I think need manually update id db category images.

<br/>

![Application](/img/pic-part02-les17-pic01.png?raw=true)

<br/>

### 17.2 - Restaurants List

**Images restaurants:**

```
https://d1ralsognjng37.cloudfront.net/b43e3aa8-ad1f-48d9-9109-6024f5ff7793.jpeg

https://d1ralsognjng37.cloudfront.net/8252b41b-1673-4975-91bc-5b609c27b205.jpeg

https://d1ralsognjng37.cloudfront.net/b0bf9b96-2e62-427e-9743-6229715efea1.jpeg

https://d1ralsognjng37.cloudfront.net/3ff8e534-94ec-4dc9-a467-433099e0561f.jpeg

https://d1ralsognjng37.cloudfront.net/32c7d67f-c36f-4471-9cf6-bb16e3b83028.jpeg

https://duyt4h9nfnj50.cloudfront.net/resized/1537291913826-w2880-3f.jpg

```

<br/>

![Application](/img/pic-part02-les17-pic02.png?raw=true)

<br/>

### 17.3 - Restaurants Pagination

<br/>

![Application](/img/pic-part02-les17-pic03.png?raw=true)

<br/>

### 17.4 - 17.5 - Search

Remove helmet package.
We will use react-helmet-async

<br/>

### 17.6 - Category

<br/>

### 17.7 - Code Challenge

<br/>

### 17.8 - 17.9 - Restaurant

<br/>

![Application](/img/pic-part02-les17-pic04.png?raw=true)

<br/>

### 18.0 - Tests Setup

<br/>

### 18.1 - App Tests

    $ npm run test:coverage

<br/>

### 18.2 - Button Tests

<br/>

### 18.3 - FormError and Restaurant Tests

<br/>

### 18.4 - Testing Header and 404

<br/>

### 18.5 - 18.7 Login Tests

    $ yarn add mock-apollo-client

<br/>

### 18.8 - 18.10 - CreateAccount Tests

https://testing-library.com/docs/react-testing-library/setup/

<br/>

### 18.11 - Conclusions

<br/>

![Application](/img/pic-part02-les18-pic01.png?raw=true)

<br/>

![Application](/img/pic-part02-les18-pic02.png?raw=true)

<br/>

### 19.0 - Installing Cypress

    $ yarn add cypress
    $ npx cypress open

<br/>

![Application](/img/pic-part02-les19-pic01.png?raw=true)

<br/>

### 19.1 - Our First Cypress Test

https://testing-library.com/docs/cypress-testing-library/intro/

    $ yarn add @testing-library/cypress

<br/>

### 19.2 - Login E2E

<br/>

### 19.3 - 19.4 - Create Account E2E

<br/>

### 19.5 - Custom Commands

<br/>

### 19.6 - 19.7 - EditProfile E2E

<br/>

![Application](/img/pic-part02-les19-pic02.png?raw=true)

<br/>

### 20.0 - Order Dashboard Routes

Need an Owner account

<br/>

![Application](/img/pic-part02-les20-pic01.png?raw=true)

<br/>

### 20.1 - Create Restaurant (part One)

<br/>

![Application](/img/pic-part02-les20-pic02.png?raw=true)

<br/>

### 20.2 - 20.3 - File Upload

    $ cd backend/
    $ nest generate module uploads

<br/>

**I wont store images in aws**

    $ yarn add aws-sdk

<br/>

### 20.4 - Create Restaurant (part Two)

<br/>

![Application](/img/pic-part02-les20-pic03.png?raw=true)

<br/>

### 20.5 - 20.5 - Cache Optimization

<br/>

![Application](/img/pic-part02-les20-pic04.png?raw=true)

<br/>

### 20.7 - Restaurant Dashboard (part One)

<br/>

![Application](/img/pic-part02-les20-pic05.png?raw=true)

<br/>

### 20.8 - 20.9 - Create Dish

<br/>

![Application](/img/pic-part02-les20-pic06.png?raw=true)

<br/>

### 20.10 - 20.11 - DishOptions

<br/>

![Application](/img/pic-part02-les20-pic07.png?raw=true)

<br/>

### 20.12 - Dish Component

<br/>

![Application](/img/pic-part02-les20-pic08.png?raw=true)

<br/>

### 20.13 - 20.15 - Victory Charts

https://formidable.com/open-source/victory/

    $ yarn addictory

```
// CREATE DISH (AS OWNER)


// CREATE OR USE ACCOUNT CLIENT
// LOGIN
// GET RESTAURANT BY ID: V3

// CREATE ORDER (5-10)
// GET ORDERS
```

<br/>

![Application](/img/pic-part02-les20-pic09.png?raw=true)

<br/>

### 20.16 - Conclusions

<br/>

### 21.0 - Introduction [Skipped]

https://paddle.com/

**I wont use paddle account for now and skip this part**

<br/>

### 21.1 - Paddle Product Test

    $ npx ngrok
    $ npx ngrok http 4000

<br/>

### 21.2 - 21.3 - Paddle Integration

<br/>

### 22.0 - Extending the Dish Component

<br/>

http://localhost:3000/restaurants/27

<br/>

![Application](/img/pic-part02-les22-pic01.png?raw=true)

<br/>

### 22.1 - 22.6 - Making Order

<br/>

![Application](/img/pic-part02-les22-pic02.png?raw=true)

<br/>

### 23.0 - Order Component

<br/>

http://localhost:3000/orders/20

<br/>

![Application](/img/pic-part02-les23-pic01.png?raw=true)

<br/>

### 23.1 - Subscription Setup

<br/>

    $ yarn add subscriptions-transport-ws

<br/>

https://www.apollographql.com/docs/react/api/link/apollo-link-ws/

https://www.apollographql.com/docs/react/data/subscriptions/

<br/>

![Application](/img/pic-part02-les23-pic02.png?raw=true)

<br/>

### 23.2 - subscribeToMore

```
// LOGIN AS OWNER
```

```
// EDIT ORDER
status: Cooking
```

<br/>

### 23.3 - Restaurant Orders

<br/>

### 23.4 - Edit Order

<br/>

### 23.5 - 23.7 - Driver Dashboard (I am not planning to use Google API)

    $ yarn add google-map-react
    $ yarn add @types/google-map-react

<br/>

console.cloud.google.com -> API Library -> Maps JavaScript API -> Enable

<br/>

Create credentials

<br/>

Login as driver

<br/>

![Application](/img/pic-part02-les23-pic03.png?raw=true)

<br/>

### 23.8 - Address Geocoding

    $ yarn add --dev @types/googlemaps

<br/>

console.cloud.google.com -> API Library -> Directions API -> Enable

<br/>

### 23.9 - Painting Directions

<br/>

### 23.10 - Coocked Order Subscription

<br/>

### 23.11 - Final Test

<br/>

### 23.12 - Conclusions

<br/>

### 24.0 - Heroku Setup [Skipped]
