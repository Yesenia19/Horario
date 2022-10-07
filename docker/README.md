##instalar docker
    pip install docker

#Crear imagen
    docker build -t horarios:v1 .

#Crear contenedor
    docker run -it -v /workspace/Horario/frontend:/home/frontend --net=host --name horarios -h horarios horarios:v1

#instalar 
    apt install -y curl
    apt install sudo
#instalar node
    curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
    sudo apt install -y nodejs

#instalar npm
    apt install npm

#Agregar angular
    npm install -g @angular/cli

#iniciar docker 
    docker start -i horarios

#creamos un proyecto


    https://www.youtube.com/watch?v=MbA71IuYUhg