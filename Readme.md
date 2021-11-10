Soy juan esteban osorio lopera

coamndos

*mkdir practica1
*cd practica1
\*git init
Initialized empty Git repository in C:/Users/juanc/Desktop/sofka/proyectos_java/tutoria2/practica1/.git/

\*git branch

- master

git branch prueba1
git branch prueba2
git branch prueba3

git branch

- master
  prueba1
  prueba2
  prueba3

////////se hacen cambios a la rama master

\*git commit -m "agreta carpeta de imagenes"
[master 9ac4217] agreta carpeta de imagenes
1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 imagenes/texto.txt

\*git add .
[master dcd8c62] agreta titulo master
1 file changed, 2 insertions(+), 1 deletion(-)

\*checkout prueba1

///////se hacen cambios a la rama prueba1

\*git add .

\*git commit -m "agreta carpeta y archivos js"
[prueba1 a9a690a] agreta carpeta y archivos js
1 file changed, 1 insertion(+)
create mode 100644 Javascript/index.js
Switched to branch 'prueba3'

\*checkout prueba2

////////se hacen cambios a la rama prueba2

\*git add .

\*git commit -m "agreta carpetay archivo css"
[prueba2 8be5d91] agreta carpetay archivo css
2 files changed, 3 insertions(+), 2 deletions(-)
create mode 100644 Css/index.css

\*checkout prueba3

/////////se hacen cambios a la rama prueba3

\*git add .

\*git commit -m "agreta carpeta y archivos h[prueba3 3340555] agreta carpeta y archivos html
create mode 100644 html/index.html

git merge prueba1
Auto-merging index.html
CONFLICT (content): Merge conflict in index.html
Automatic merge failed; fix conflicts and then commit the result.

\*git merge prueba2  
Auto-merging index.html
CONFLICT (content): Merge conflict in index.html
Automatic merge failed; fix conflicts and then commit the result.

\*git merge prueba3  
Merge made by the 'recursive' strategy.
html/index.html | 1 +
1 file changed, 1 insertion(+)
create mode 100644 html/index.html

al repositorio

git remote add origin https://github.com/JuanesOsorioL/Practica_github_sofka.git
git branch -M main
git push -u origin main
