# Test website to integrate firebase for a vanilla javascript code

The documentation here explains how to integrate google firebase authentication with a simple HTML web application which uses vanilla javascript.
Ref: https://firebase.google.com/products/auth 
     https://firebase.google.com/docs/auth/web/start

As an example we will be using google authentication here.

## STEP 1 - Sign in
 - Create an account with google, if you do not have one already. 
 - Login with Google account navigate to the link https://firebase.google.com/products/auth 

## STEP 2 - Add Project
 - Click on the Visit console button and navigate to the firebase console.
 - Add a new project.
 - Choose all the required sign-in providers here
![image](https://github.com/dheepak-rmn/test-website/assets/135533984/4aacec3f-79d0-4f04-984b-d881dc7f6c17)

E.g.
![image](https://github.com/dheepak-rmn/test-website/assets/135533984/4dacedd9-e92d-4224-94b7-bcf23cd14f8c)

- Add Authorized domain by clicking on settings and Authorized domains

## STEP 3 - Add Application
 - Click on the project created above and application by clicking on Add app
![image](https://github.com/dheepak-rmn/test-website/assets/135533984/b2241a2b-f200-4752-a0ed-e6024f34c9fd)
 - Click on the app and go to the app settings
![image](https://github.com/dheepak-rmn/test-website/assets/135533984/6321f095-de7c-41ac-b150-a7feed0a578b)

 - Copy the firebase config from the setting and replace it with the `firebaseConfig` in `init-firebase.js`
![image](https://github.com/dheepak-rmn/test-website/assets/135533984/5e896c1e-a004-40e0-9aa9-ce75107c3d8c)
