### Initial firebase functions project

``$ npm install -g firebase-tools``  
``$ firebase login``  
``$ mkdir firebase_sendmail``  
``$ cd firebase_sendmail``  
``$ firebase init functions``  

### Install npm libs
``$ cd functions``  
``$ npm install``  

### Set config parameters and deploy
``$ firebase functions:config:set gmail.email="icemilk0122@gmail.com" gmail.password="xxxx"``  
``$ cd ..``  
``$ firebase deploy --only functions``  

