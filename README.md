# Alpine LAMP

Light weight LAMP server.  

## Build
`docker build -t ${USER}/alpine-lamp .`

## Run
`docker run -i -t -p "8080:80" --name alpine-lamp ${USER}/alpine-lamp`


Inspired from [this project](https://hub.docker.com/r/glats/alpine-lamp).