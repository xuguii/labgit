# GIT Lab

1. Instalación de los paquetes de dependecia del proyecto **(npm install)**
<img src="./content/Capture.JPG">
<hr>

2. Iniciando el script **(npm start)**
<img src="./content/Capture2.JPG">
<hr>

3. Iniciando el repositorio **(git init)**
<img src="./content/Capture3.JPG">
<hr>

4. Pasando todo a staging **(git add .)**
<img src="./content/Capture4.JPG">
<hr>

5. Haciendo el primer commit **(git commit)**
<img src="./content/Capture5.JPG">
<hr>

6. Ya creado el repositorio en GitHub, copio la URL del mismo para hacer la conexión local-remoto **(git remote add origin)**
<img src="./content/Capture6.JPG">
<hr>

7. Hago un cambio en el archivo index.js, lo paso a staging y hago commit con un mensaje descriptivo **(git commit -m "cambio en el console.log")**
<img src="./content/Capture7.JPG">
<hr>

8. Hago el push para subir los cambios al repositorio de GitHub **(git push)**
<img src="./content/Capture8.JPG">
<hr>

9. Cración de una nueva rama llamada "development" **(git branch development)**
<img src="./content/Capture9.JPG">
<hr>

10. Me cambio a la rama "development" y hago un cambio en el archivo index.html, lo paso a staging y hago commit **(git checkout development)**
<img src="./content/Capture10.JPG">
<hr>

11. Utilizo el comando de log para ver la bifurcación de las ramas **(git log --oneline --decorate --graph --all)**
<img src="./content/Capture11.JPG">
<hr>

12. Hago el push de la nueva rama "development" con los cambios a GitHub **(git push -f origin development)**
<img src="./content/Capture12.JPG">
<hr>

13. Cambiado a la rama master, hago el merge de la rama "development" a la rama master **(git merge development -m "merge de rama development a master)**
<img src="./content/Capture13.JPG">
<hr>

14.  Hago el push **(git push)**
<img src="./content/Capture14.JPG">
<hr>

15.  Vuelvo a utilizar el comando de log para visualizar la rama tras el merge **(git log --oneline --decorate --graph --all)**
<img src="./content/Capture15.JPG">






