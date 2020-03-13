# Docker-Linux-MVC-Application

When you run locally on your development-machine port 80 and 443 may already be occupied so:

**Production**

	docker-compose -f Docker-Compose.yml -f Docker-Compose.Release.yml up

**Development**

	docker-compose -f Docker-Compose.yml -f Docker-Compose.Development.yml up

You need to kill the process using port 443 if any.