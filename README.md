# gh-pages

npx instal create-react-app my-app

cd my-app

npm install gh-pages --save-dev

//w  pliku package.json dodaj

"homepage": "https://armod.github.io/my-app",

"predeploy": "npm run bulid"

"deploy": "gh-pages -d build"

//w github stwórz repo

git init

git remote add origin git@github.com:armod/my-app.git

git push -u origin master

npm run deploy

