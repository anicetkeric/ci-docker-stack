# ci-docker-stack
Docker Compose builds Jenkins , Sonar, Portainer, mediawiki, nginx

Pre-Requisites
-------------
- Install [Docker](https://docs.docker.com/install/) (for Mac OSX / Windows / Docker)
- Install [Docker Compose](https://docs.docker.com/compose/install/)
- Clone this repository


QuickStart
-----------
- To Start containers in the background

	`` 
	$ docker-compose up -d
	``
- Stoping all containers

	`` 
	$ docker-compose down
	``

Access Tools
-----------

| *services* | *Link* | *Credentials* |
| ------------- | ------------- | ------------- |
| Jenkins | http://localhost:8080/ | no login required |
| SonarQube | http://localhost:9000/ | admin/admin |
| Portainer | http://localhost:8000/ | admin/adminpassword@@ |
| mediawiki | http://localhost:8001/ | no login required |
| nginx  | http://localhost | no login required |
