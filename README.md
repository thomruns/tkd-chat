# tkd-chat

>A basic chat app using Vue.js and Firebase, based on Sean Pelling Udemy course. For simple styling, the app uses utility classes from Materialize, and Google icon fonts.

## Important
This app uses Firebase and Firestore. It assumes that you have set up a Firebase database for the project, and created a config file in src/firebase/initi.js, with API keys and other project-specific data from Firebase. Firebase must also be installed as a dependency, as shown in package.json. At the time of writing, Firestore was still in beta.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
