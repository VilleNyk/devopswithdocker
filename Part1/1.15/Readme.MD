first, make sure that you have docker installed and then pull the Ubuntu image.
You can do it with
`docker image pull ubuntu`

pull the project image with
`docker pull villenyk/spacexpage`

then run the project with
`docker container run -d -p 5000:80 villenyk/spacexpage`

view the site at localhost:5000