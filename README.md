Crear Read me para documentar 
# touch README.md 
Generar la carpeta assets
# mkdir assets
Entrar a la carpeta assets 
# cd assets
Generar la carpeta css
# mkdir css
Volver a la carpeta  contenedora
# cd ..
Mover el archivo css a la carpeta css creada dentro de assets
# mv style.css ./assets/css
Iniciar el repositorio (verificar este en main)
# git init
Agregar archivos al stage
# git add .
Realizar primer commit
# git commit -m “mi primer commit”
Crear una nueva rama llamada “development”
# git branch development
Entrar a la nueva rama
# git checkout development
Realizar los cambios en html 
Agregar archivos al stage
# git add .
Realizar un nuevo commit
# git commit -m "errores corregidos"
Crear el repositorio en GitHub para conectarlo al repositorio local
Conectar el repositorio local al remoto
# git remote add origin https://github.com/javmaldonado/desafiobranching.git
Pusheear las ramas 
# git push origin main
# git push origin development
# git -- all (pushear todas las ramas)
Activar github pages 