##Build docker image
`docker image build -t netflix-eureka-naming-server:v1 .`

##Run docker
`docker container run -d --name netflix-eureka-naming-server -p 8761:8761 netflix-eureka-naming-server:v1`