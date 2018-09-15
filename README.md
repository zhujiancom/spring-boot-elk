# spring-boot-elk

## step 1 
`git clone https://github.com/HelloMan/spring-boot-elk.git`

## step 2 build & run 

### build applications
`cd spring-boot-elk`

`mvn clean package`

`docker-compose build`

### run applications
`docker-compose up spring-boot`

`docker-compose up elasticsearch`

`docker-compose up logstash`

`docker-compose up kibana`

## step 3 
### generate log 
curl http://localhost:8080

### verify in kibana 
open browser and type   http://localhost:5601/



