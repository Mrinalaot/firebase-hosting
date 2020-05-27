### Firebase Hosting ###

pre: NodeJS installed
npm install -g firebase-tools

Create your App first
https://console.firebase.google.com/

firebase login --interactive

##### Static 

firebase init
firebase deploy
firebase serve

##### Dynamic

firebase init hosting
firebase init functions
* install dependencies
cd functions
npm i expess --save
Modify : index.js
Modify : firebase.json
cd ..
firebase serve --only functions,hosting
firebase deploy