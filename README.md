# Angular 6 Quick Start App

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

Angular 6 app with Firebase role-based authentication, Material, routing, and some other essentials already set up.

## Get started

1. Clone repo
2. Run `npm install`
3. Run `ng serve` for a dev server
4. Navigate to `http://localhost:4200/`

## Firebase

1. Go to [Firebase](https://firebase.google.com/)
2. Select project or create new project
3. Copy the contents of the config item from 'Add Firebase to your web app'.  It should look like this:
```
    apiKey: "LA5...",
    authDomain: "yourproject.firebaseapp.com",
    databaseURL: "https://yourproject.firebaseio.com",
    projectId: "yourproject",
    storageBucket: "yourproject.appspot.com",
    messagingSenderId: "555..."
```
4. Paste into `src/environments/environment.ts`
6. Enable Google authentication (from Firebase Console)
7. Activate Firestore (also from Firebase Console) 

## Material

### Components
Most of the [AngularMaterial](https://material.angular.io/) components are ready to be used.  To add additional components, add them to `src/app/mat/mat.module.ts`.  They can then be used in any other component.

### Theming
Change the colors of the Material theme in src/mat-theme.scss. [Material Palette](https://www.materialpalette.com/) is useful for theming.
