npx instal create-react-app my-app\
cd my-app\
npm install gh-pages --save-dev\
//w  pliku package.json dodaj\
"homepage": "https://armod.github.io/my-app",\
"predeploy": "npm run build",\
"deploy": "gh-pages -d build",\
//w github stwórz repo\
git init\
git remote add origin https://github.com/armod/my-app.git\
git push -u origin master\
npm run deploy\

//dla ikon\
npm install react-icons --save\

