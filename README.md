# PSICITLA
git init
git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
"homepage": "https://TU_USUARIO.github.io/TU_REPOSITORIO",
npm install --save-dev gh-pages
"scripts": {
  "start": "react-scripts start",
  "build": "react-scripts build",
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
npm run deploy
