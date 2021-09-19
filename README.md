# Estudo de Docker

## Criado o Hello World
    chmod +x getting-started.sh
    ./getting-started.sh
> Acesse no browser localhost:80

- -d - run the container in detached mode (in the background)
- -p 80:80 - map port 80 of the host to port 80 in the container
- docker/getting-started - the image to use
## Configurado uma Aplicação para Docker
    cd app
    docker build -t getting-started .
    chmod +x app-getting-started.sh
    ./app-getting-started.sh
> Acesse no browser locahost:3000
