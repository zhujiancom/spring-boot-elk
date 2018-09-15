# spring-boot-elk

## step 1 clone repository
`git clone https://github.com/HelloMan/spring-boot-elk.git`

## step 2 build & run 

### build spring boot application
`cd spring-boot-elk`

`mvn clean package`

### build application through docker-compose
`docker-compose build`

### run applications through docker-compose
`docker-compose up spring-boot`

`docker-compose up elasticsearch`

`docker-compose up logstash`

`docker-compose up kibana`

## step 3 
### run spring boot to generate log 
curl http://localhost:8080

### verify in kibana 
open browser and type   http://localhost:5601/



