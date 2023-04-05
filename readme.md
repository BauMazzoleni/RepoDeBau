primero debemos descargar git para luego instalarlo en nuestra pc
Recordar tildar la opcion de: git bash here y seleccionar la opcion de use vsc as git default editor
podemos abrir el git bash o una consola o una temrinal de vsc
Para abrir la temrinal desde vsc tenemos que abrir el root en el IDE, luego tocamos sobre el boton temrinal y luego tocamos sobre el select que esta al lado del "+" y seleccionamos la opcion "git bash". Al tocarlo se nos abre el bash en la terminal
Paso seguido necesiatmos configurar nuestro usuario por unica vez con los siguientes comandos:
git config --global user.name "BauMazzoleni"
git config --global user.email bmazzoleni00@gmail.com
Luego de esto podemos corroborar si la configuracion quedo impactada con los siguientes comandos:
git config user.name
git config user.email

---

Luego de tener todo instalado y configurado necesito pararme sobre el root y decirle que vamosa trabajar con git
Para esto debemos posicionarnos sobre root y usar el comando (por primera y unica vez):
git init
Lueog de ejecutar el git init ya estamos parados sobre el estado "working directory" que es donde generamos todas las lineas de codigo
Cuando completo mi tarea paso todo lo trabajado del working directory al staging area
Como lo hago? Utilizando el comando:
git add
git add nombreArchivo (manual archivo o directorio)
Luego de pasar todo el staging area instantaneamente pasamos tood el repositorio con el comando:
git commit -m "comentario describiendo brevemente el trabajo"
Al terminar de comitear, se nos genera una version nueva y no posicionamos en el working directory automaticamente
Como controla los estados de mis archivos/directorios? Con el siguiente comando:
git status
