# Piggyback Incentives

This repository helps with setting up Piggyback Incentives for a developer on their local machine.

## Status

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

7. Common Package: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-common.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-common.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-common&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-common)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-common/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-common)

8. Partner Portal: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-portal.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-portal.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-portal&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-portal)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-portal/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-portal)

9. Mobile App: [![TravisCI](https://travis-ci.org/piggy1-mvn/piggyback-mobile.svg?branch=master)](https://travis-ci.org/piggy1-mvn/piggyback-mobile.svg?branch=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=piggy1-mvn_piggyback-mobile&metric=alert_status)](https://sonarcloud.io/dashboard?id=piggy1-mvn_piggyback-mobile)
[![codecov](https://codecov.io/gh/piggy1-mvn/piggyback-mobile/branch/master/graph/badge.svg)](https://codecov.io/gh/piggy1-mvn/piggyback-mobile)

## Prerequisite Installations

1. Docker Desktop
2. IntelliJ/Eclipse IDE - for Java Microservices
3. Visual Studio Code - for React.JS Partner Portal
4. Android Studio (and mobile SDKs) - for the Android mobile app.
5. Mac - for the iOS app.
6. Git

## Steps

1. Clone git repositories.
2. Under piggyback-dev-runner folder, on a command line -

	**docker-compose up -d**
	
	This will start up all the microservices, databases and web interfaces in their respective docker containers. It may take a few minutes for the applications inside containers to finish initialization.

	**docker-compose down**
	
	This will stop and remove all containers started in the previous step.
	
## Building Locally

1. **piggyback-common**
	
	This is a maven project and deploys the package to packagecloud.io through TravisCI build. For building this project locally, please un-comment the maven-deploy-plugin in the pom.xml
	**NOTE** Do not push your changes with this plugin un-commented.
~~~
<plugins>
        <plugin>
            <artifactId>maven-deploy-plugin</artifactId>
            <version>2.8.1</version>
            <configuration>
                <altDeploymentRepository>internal.repo::default::file://${project.build.directory}/repo</altDeploymentRepository>
            </configuration>
        </plugin>
</plugins>
~~~
