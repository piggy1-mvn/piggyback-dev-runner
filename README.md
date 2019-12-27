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
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-order&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-order)
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

NOTE: 
1. Local machine setup does not support https.
2. This project runs Kafka and Zookeeper. It is recommended to allocate at least 8 GB RAM to Docker Desktop.

Steps:
1. Clone this git repository to your local machine.
2. Run the command in piggyback-dev-runner/scripts/git_pull.txt
3. Comment out the nginx and certbot services from docker-compose yml.
4. Under piggyback-dev-runner folder, on a command line -

	**docker-compose up -d**
	
	This will start up all the microservices, databases and web interfaces in their respective docker containers. It may take a few minutes for the applications inside containers to finish initialization.

	**docker-compose down**
	
	This will stop and remove all containers started in the previous step.
		
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

## Generating certificates for Dev Instance

In order to setup nginx and certbot services as a https to http reverse proxy, follow the below steps:

Pre-requisites: Ensure you own a domain name, with CNAME and NS registered properly and mapped to your Dev VM's public IP address correctly. Scripts in this repository refer to **test.piggyback.ga**

Steps:
1. Ensure all other services and databases are started.
2. Run the following command: **sudo ./init-letsencrypt.sh**

## Production Kubernetes Cluster Setup

The repository contains definition files for setting up all components in a kubernetes cluster in k8s/ folder. HTTPS setup can be performed using NGINX Ingress. The below URL can be refered to for high-level instructions to perform the setup.

~~~
https://www.digitalocean.com/community/tutorials/how-to-set-up-an-nginx-ingress-with-cert-manager-on-digitalocean-kubernetes
~~~