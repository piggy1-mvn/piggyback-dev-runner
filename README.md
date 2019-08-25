# Piggyback Incentives

This repository helps with setting up Piggyback Incentives for a developer on their local machine.

## Prerequisite

1. Docker Desktop https://www.docker.com/products/docker-desktop
2. IntelliJ/Eclipse IDE - for Java Microservices
3. Visual Studio Code - for React.JS Partner Web Interface
4. Android Studio - for the mobile app.
5. Git

## Steps

1. Clone 10 git repositories hosted on Bitbucket.
2. Under piggyback-dev-runner folder, on a command line -
	- docker-compose up -d
	This will start up all the microservices, databases and web interfaces in their respective docker containers. It may take a few minutes for the applications inside containers to finish initialization.
	- docker-compose down
	This will stop and remove all containers started in the previous step.