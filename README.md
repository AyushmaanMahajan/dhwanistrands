# Boyfriend Plan 💖

Single static page in `public/index.html`. State lives in the browser (localStorage); no backend.

## Deploy (Firebase Hosting)
```
npm i -g firebase-tools
firebase login
firebase projects:create my-boyfriend-plan   # pick any unique id; it becomes my-boyfriend-plan.web.app
# edit .firebaserc if you chose a different id
firebase deploy --only hosting
```
