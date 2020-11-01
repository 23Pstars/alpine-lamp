# Alpine LAMP

Light weight LAMP server.  

## Configuration

Workdir = `/www`  
PHP Info = `/www/___info.php`  
DB Name = `db`  
DB User = `root`  
DB Pass = ` `

## Build
`docker build -t ${USER}/alpine-lamp .`

## Run
`docker run -i -t -p "8080:80" --name alpine-lamp ${USER}/alpine-lamp`


Inspired from [this project](https://hub.docker.com/r/janes/alpine-lamp/dockerfile).