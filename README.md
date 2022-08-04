# Fredderick 

# Paso1 : Para crear la carpeta utilizamos el siguiente comando MKDIR 
 mkdir "nueva_carpeta".
# Crea un archivo en este directorio y llámalo archivo_nuevo.txt
  nano archivo_nuevo.txt
# Cámbiale el nombre a este último archivo que has creado y llámalo archivo_viejo.txt.
    El cambio se realizo dentro del nano cuando se fue a guardar
# Cambia los permisos de este archivo para que todos los usuarios puedan leer, escribir y ejecutarlo
   chmod 777 nombre del archivo
# Sube un nivel de directorio, es decir, vuelve al directorio anterior.
     cd ..
# Crea un enlace al archivo que creaste en esta carpeta llamado "enlace.ln".
  ln s /home/fredderick/Documentos/Fredderick/nueva_carpeta/archivo_viejo.txt enlace.ln
# Elimina el directorio "nueva_carpeta" y los archivos que contenga
  rm -f con el nombre del archivo 