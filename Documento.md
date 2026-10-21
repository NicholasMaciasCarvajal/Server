Documento Guia

127.0.0.1 es la ip de localHost

docker ps -a >> para ver los contenedores apagados sin "-a" para ver los encendidos
docker rm Conteiner >> para borrar el contenedor que quieres poniendo el nombre
docker build -t nombre . >> docker build sirve para builder "-t" es para darle un nombre "." es para darle el contexto
docker compose up -d >> sirve para si no tienes la imagen se buildea sola y se crea todo lo que se puso en el compose.ymal, "-d" para detachear
docker commit contenedor imagen:version >> para guardar un contenedor y que deje de ser desechable y transformarlo en una imagen.
docker save -o ruta.tar imagen:version >> para exportar la imagen
docker load -i ruta.tar >> para importar una imagen 

None - No se conecta a Red nunca ni por nada
Bridge - Es un tunel de que usar el cifrado NAT
Host - Acceso total a internet
OverLay - Lo mismo que Bridge pero a nivel masivo y sirve para procesamiento distribuido