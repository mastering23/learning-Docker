#Indiciamos la imagen que vamos a utilizar 
FROM ubuntu:latest

WORKDIR /app

#creamos un archivo de texto dentro de contenedor 
RUN echo "!Hola Docker!" > saludo.texto

#El puero donde va estar espuesto 
EXPOSE 80 

CMD ["echo","Este es un contenedor de ejemplo"]