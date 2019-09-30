# Piggyback Incentives

This repository helps with setting up Piggyback Incentives for a developer on their local machine.

## Project Status

1. Location Service: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-location.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-location.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-location&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-location)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-location/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-location)

2. User Service: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-user.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-user.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-user&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-user)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-user/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-user)

3. Partner Service: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-partner.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-partner.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-partner&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-partner)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-partner/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-partner)

4. Events Service: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-events.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-events.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-events&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-events)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-events/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-events)

5. Offers Service: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-offers.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-offers.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-offers&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-offers)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-offers/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-offers)

6. Invoice Service: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-invoice.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-invoice.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-invoice&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-invoice)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-invoice/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-invoice)

7. Notification Service: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-notification.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-notification.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-notification&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-notification)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-notification/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-notification)

8. Order Service: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-order.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-order.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-notification&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-notification)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-order/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-order)

9. Partner Portal: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-portal.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-portal.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-portal&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-portal)

10. Mobile Application: [![Build Status](https://app.bitrise.io/app/985561cda48896a5/status.svg?token=EB_R2a7l_eeE78wmQZGEUQ&branch=master)](https://app.bitrise.io/app/985561cda48896a5/status.svg?token=EB_R2a7l_eeE78wmQZGEUQ&branch=master)

11. Sample Merchant Application:  [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-sample.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-sample.svg?branch=master)

## Prerequisite Installations

1. Docker Desktop
2. IntelliJ/Eclipse IDE - for Java Microservices
3. Visual Studio Code - for React.JS Partner Portal
4. Android Studio (and mobile SDKs) - for the Android mobile app.
5. Mac - for the iOS app.
6. Git

## Local Setup Steps

1. Clone this git repository to your local machine.
2. Run the command in piggyback-dev-runner/scripts/git_pull.txt
2. Under piggyback-dev-runner folder, on a command line -

	**docker-compose up -d**
	
	This will start up all the microservices, databases and web interfaces in their respective docker containers. It may take a few minutes for the applications inside containers to finish initialization.

	**docker-compose down**
	
	This will stop and remove all containers started in the previous step.
	
## GCP Pub/Sub Dev Setup

Some of the microservices use GCP Pub/Sub to publish and subscribe for messages. In order to connect to GCP successfully, following settings should be made manually.

1. For docker container running locatlly, under piggyback-dev-runner, create a folder **gcp-secret-vol** (may already be created if docker-compose command is run) and place secret.json file (shared seperately) in this folder. This will allow microservices to connect to GCP when running inside a docker container.

2. For Windows machines - 
	
	a. Add a system environment variable: **GOOGLE_APPLICATION_CREDENTIALS**, and point it to the full path of the secret.json file (shared seperately).
	
	b. Comment the following lines from the application.properties to avoid overriding system environment variable -
	
~~~
spring.cloud.gcp.project-id=some-project-id
spring.cloud.gcp.credentials.location=file:/app/config/secret.json
~~~

## GCP Image Tagging for Production Deployment

For Java microservices, production docker images are built and pushed to GCR when a pull request is merged to develop. In order to ensure changes are deployed through the CD pipeline, please increment the tag for the production image in 4 files, as follows -

In Makefile_prod and Makefile_canary -

~~~
IMAGE_VERSION:=v5
~~~

In k8s/canary/<app>-deployment.yaml and k8s/production/<app>-deployment.yaml
	
~~~
containers:
      - image: gcr.io/absolute-text-251105/piggy1-user:v5
~~~

**NOTE: Do not merge pull requests to develop and master without incrementing the tag at all 4 positions, else changes will not be deployed to production.**

## Auto-Scaling Testing

**scripts/LocationService.jmx** can be imported to JMeter to perform load testing on Production instances of Location Service and test Kubernetes auto-scaling.
