#spring boot websphere liberty

##Build
docker build -t spring-boot-websphere-liberty -f Dockerfile .
## Run
docker run --name spring-boot-websphere-liberty -e LICENSE=accept -p 9888:9080 -p 9889:9443 spring-boot-websphere-liberty