# Instrucciones

## Instrucciones originales

~~~~
docker run -it -p 127.0.0.1:8080:8080 --name coursera-aml-1 zimovnov/coursera-aml-docker 

docker stopo coursera-aml-1

docker start -a coursera-aml-1
~~~~

## Adaptaciones para utilizar el Container

Para generarlo, compartiendo la carpeta con los notebooks y datos con el directorio **/root/data**:

~~~~
docker run -v C:/Users/trodriguez/src/coursera/intro-to-dl:/root/data -it -p 127.0.0.1:8080:8080 --name coursera-aml-1 zimovnov/coursera-aml-docker
~~~~


Hub Docker con instrucciones sobre el container: [https://hub.docker.com/r/zimovnov/coursera-aml-docker/](https://hub.docker.com/r/zimovnov/coursera-aml-docker/)

Github de Docker: [https://github.com/ZEMUSHKA/coursera-aml-docker](https://github.com/ZEMUSHKA/coursera-aml-docker)