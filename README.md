//Comandos a introducir para empezar a trabajar:

npm init --yes
npm install typescript -D 
npx tsc --init 
npm install mongoose
npm install @types/mongoose
npx tsc -w

Se genera el tsconfig.json y en el hacemos las modificaciones de siempre: '"target": "es6",', '"outDir": "./dist",' 
y en la linea 68 ponemos lo siguiente: 
"exclude": [ "node_modules" ] 

En el .gitignore ponemos: 
dist 
node_modules

Creamos src y dentro index.ts, donde irán los programas

Para ejecutar lo que hemos compilado usamos: 
node dist 
-- o -- 
node dist/index

Para subirlo a GitHub:
git init 
git add . 
git commit -m "first commit" 
git remote add origin https://github.com/DanielMNpdv/02nodejs.git
git push -u origin master 

Creamos la carpeta view y metemos los archivos que hayamos creado.