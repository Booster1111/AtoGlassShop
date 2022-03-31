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
![sign up](https://user-images.githubusercontent.com/61457979/127736344-b6ad0fab-1888-4274-b4dd-322519f9ff68.PNG)


## Admin panel
![admin](https://user-images.githubusercontent.com/61457979/127736531-43dbf070-7698-4b8c-8b02-2bc02a65eee7.PNG)
![admin panel product list](https://user-images.githubusercontent.com/61457979/127736536-52e02a06-5236-4bc2-8e78-968a2ed59f0d.PNG)
![add new product](https://user-images.githubusercontent.com/61457979/127736538-c804a2a4-d3e9-4894-abf8-9ec9c5821878.PNG)

## firebase database screen shots
![firebase](https://user-images.githubusercontent.com/61457979/127737661-79f5a6e5-5ec1-4dab-89f2-33d0acf63cd9.PNG)
![fir2](https://user-images.githubusercontent.com/61457979/127737663-0b9f7cb3-ec18-412a-b1c5-54334580cf4f.PNG)

