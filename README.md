npm install -g @angular/cli

ng new ng03 --prefix custom
ng serve
ng serve --port=4201
ng build
ng build --prod
ng test
ng e2e
ng help
ng add @angular/elements
ng g component button --inline-style --inline-template -v Native

npm install --save-dev http-server

1. Init Repo (VSCode)

2. Commit Repo (VSCode)

3. Create Repo (GitHub REST API)
-> curl -u 'kwokhung' https://api.github.com/user/repos -d '{"name":"ng03"}'

4. Remote Add Origin
-> git remote add origin https://github.com/kwokhung/ng03

5. Push Origin Master
-> git push -u origin master

npm install --save @types/facebook-js-sdk
npm install --save @capacitor/core @capacitor/cli
npx cap init
npx cap init ng03 com.mblinus.test
npx cap add android
npx cap open android
