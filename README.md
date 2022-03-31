# Salinaka | E-commerce react app
Simple ecommerce react js app with firebase [typescript].
![Firebase Deploy](https://github.com/jgudo/ecommerce-react/workflows/Firebase%20Deploy/badge.svg)

### [Live demo](https://salinaka-ecommerce.web.app/)

![Salinaka screenshot](https://raw.githubusercontent.com/jgudo/ecommerce-react/master/static/screeny1.png)
![Salinaka screenshot](https://raw.githubusercontent.com/jgudo/ecommerce-react/master/static/screeny2.png)
![Salinaka screenshot](https://raw.githubusercontent.com/jgudo/ecommerce-react/master/static/screeny3.png)
![Salinaka screenshot](https://raw.githubusercontent.com/jgudo/ecommerce-react/master/static/screeny7.png)

## Run Locally
### 1. Install Dependencies
```sh
$ npm install
```

### 2. Create a new firebase project
Login to your google account and create a new firebase project [here](https://console.firebase.google.com/u/0/)

Create an `env` file - Set filename`.env.prod` file for production and `.env.dev`for development and save it in the root of your project folder
and add the following configuration details. You can either use the same configuration details for both development and production but it's best to make separate projects. It can be found on your firebase project settings.

```
// SAMPLE CONFIG .env.dev, you should put the actual config details found on your project settings

FIREBASE_API_KEY=AIzaSyBge81jgwZvfu769SOJSXr6mVuxiLYBB0U
FIREBASE_AUTH_DOMAIN=onlineglass-379bc.firebaseapp.com
FIREBASE_DB_URL=https://onlineglass-379bc-default-rtdb.firebaseio.com/
FIREBASE_PROJECT_ID=onlineglass-379bc
FIREBASE_STORAGE_BUCKET=gs://onlineglass-379bc.appspot.com
FIREBASE_MSG_SENDER_ID=615374682590
FIREBASE_APP_ID=1:615374682590:web:3812b09eb2f9fd0d08054f

``` 

After setting up necessary configuration,
create a **Database** and choose **Cloud Firestore** and start in test mode

### 3. Run development server
```sh 
$ npm run dev-server
```

---

## Build the project
```sh
$ npm run build
```

## How to add products or perform CRUD operations for Admin
1. Navigate to your site to `/signup`
2. Create an account for yourself
3. Go to your firestore collection `users collection` and edit the account you've just created. Change the role from `USER` to `ADMIN`.
4. Reload or sigin again to see the changes. 

**Firebase Admin to be integrated soon**

## Features

* Admin CRUD operations
* Firebase authentication
* Firebase auth provider authentication
* Account creation and edit

## sign in and sign up 
![Untitled2](https://user-images.githubusercontent.com/89033750/161114921-90397047-8502-4dcf-9c6b-52140f53d1db.png)


## firebase database
![Untitled4](https://user-images.githubusercontent.com/89033750/161115151-a7928fb4-6f2c-4a90-a904-5741c2526ec8.png)


