1. npm init -y
2. npm i tailwindcss @tailwindcss/cli
3. apres faire dossier src puis input.css et .gitignore
4. npx @tailwindcss/cli -i ./src/input.css -o ./dist/output.css --watch
5. dans le html - link rel="stylesheet" href="dist/output.css"
6. dans input.css mettre " @import "tailwindcss"; " cette ligne importe tout tailwind
   c'est le reset (aussi appelé Préflight)
7. "dev": "tailwindcss -i ./src/input.css -o ./dist/output.css --watch" a la place de test
8. puis dans le terminal tapez npm run dev
9. puis ajouter la commande "build": "tailwindcss -i ./src/input.css -o ./dist/output.css --minify"