"# Run-Docker-File" 

"# Building docker file: docker build -t docker-file .
"# docker-file is the jar name"
"# docker run -p 9000:8080 docker-file"
"# here 9000 is the docker port or host port and 8080 is the container port"


"# create jar file name by <finalname>jar file name</finalname> in pom.xml file for maven project" 

"# push docker image to dockerHub(it's docker repository) first create a tag on the image. and the command is: docker tag docker-file nafiuli131/docker-file" 

"# now push it to the docker hub : docker push nafiuli131/docker-file"

"# now it from docker hub to localmachine command is : docker pull nafiuli131/docker-file"

"# now run it into the localmachine command is:  docker run -p 9000:8080 nafiuli131/docker-file"
