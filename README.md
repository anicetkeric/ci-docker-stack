# ci-docker-stack
Docker Compose builds Jenkins , Sonar, Portainer, mediawiki

Pre-Requisites
-------------
- Docker (for Mac OSX / Windows / Docker) => [Docker install documentation](https://docs.docker.com/install/)
- Docker Compose
- Clone the repository


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
| Portainer | http://localhost:8000/ | no login required |
| mediawiki | http://localhost:8001/ | no login required |

