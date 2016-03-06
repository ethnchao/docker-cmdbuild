# CMDBuild in Docker 

![cmdbuild_logo](http://www.cmdbuild.org/logo.png)


### CMDBuild

[CMDBuild](http://www.cmdbuild.org/en) is a web environment in which you can configure custom solutions for IT Governance, or more generally for asset management.

### Docker

[Docker](https://www.docker.com/) allows you to package an application with all of its dependencies into a standardized unit for software development.

More information : 

* [What is docker](https://www.docker.com/what-docker)
* [How to Create a Docker Business Case](https://www.brianchristner.io/how-to-create-a-docker-business-case/)

### Information

This is the unofficial (updated !) repository with all the versions of cmdbuild. You can choose wich version of tomcat you would like to use for your project.

I will update the repository every time there is a new version of cmdbuild available

### Demo

Here is 6 docker containers with some versions of cmdbuild !

[Version 1.4.0](http://91.121.64.81:8080)
[Version 1.5.0](http://91.121.64.81:8081)
[Version 2.0.0](http://91.121.64.81:8082)
[Version 2.1.0](http://91.121.64.81:8083)
[Version 2.2.0](http://91.121.64.81:8084)
[Version 2.3.0](http://91.121.64.81:8085/)
[Version 2.3.4 (latest)](http://91.121.64.81:8086/)

* **user** : demo
* **password** : demo

### Supported tags and respective Dockerfile links




#### Example

```bash
docker run --name cmdbuild -p 8080:8080 -d quentin/varquet:t6-2.1.4 
```

* **t6** : Version of tomcat
* **2.1.4** : Version of cmdbuild

#### Tags

**Tomcat 6 with java 8**

* [```t6-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-1.4.0.2/Dockerfile/Dockerfile) | [```t6-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-1.5.0/Dockerfile/Dockerfile) | [```t6-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.0.0/Dockerfile/Dockerfile) | [```t6-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.0.3/Dockerfile/Dockerfile) | [```t6-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.0/Dockerfile/Dockerfile) | [```t6-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.1/Dockerfile/Dockerfile) | [```t6-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.2/Dockerfile/Dockerfile) | [```t6-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.3/Dockerfile/Dockerfile)| [```t6-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.4/Dockerfile/Dockerfile) | [```t6-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.5/Dockerfile/Dockerfile) | [```t6-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.6/Dockerfile/Dockerfile) | [```t6-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.7/Dockerfile/Dockerfile) | [```t6-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.8/Dockerfile/Dockerfile) | [```t6-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.2.0/Dockerfile/Dockerfile) | [```t6-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.2.1/Dockerfile/Dockerfile) | [```t6-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.2.2/Dockerfile/Dockerfile) | [```t6-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.0/Dockerfile/Dockerfile) | [```t6-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.1/Dockerfile/Dockerfile) | [```t6-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.2/Dockerfile/Dockerfile) | [```t6-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.3/Dockerfile/Dockerfile) | [```t6-2.3.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.4/Dockerfile/Dockerfile)


**Tomcat 7 with java 8**

* [```t7-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.4.0.2/Dockerfile/Dockerfile) | [```t7-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.5.0/Dockerfile/Dockerfile) | [```t7-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.0/Dockerfile/Dockerfile) | [```t7-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.3/Dockerfile/Dockerfile) | [```t7-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.0/Dockerfile/Dockerfile) | [```t7-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.1/Dockerfile/Dockerfile) | [```t7-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.2/Dockerfile/Dockerfile) | [```t7-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.3/Dockerfile/Dockerfile)| [```t7-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.4/Dockerfile/Dockerfile) | [```t7-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.5/Dockerfile/Dockerfile) | [```t7-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.6/Dockerfile/Dockerfile) | [```t7-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.7/Dockerfile/Dockerfile) | [```t7-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.8/Dockerfile/Dockerfile) | [```t7-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.0/Dockerfile/Dockerfile) | [```t7-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.1/Dockerfile/Dockerfile) | [```t7-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.2/Dockerfile/Dockerfile) | [```t7-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.0/Dockerfile/Dockerfile) | [```t7-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.1/Dockerfile/Dockerfile) | [```t7-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.2/Dockerfile/Dockerfile) | [```t7-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.3/Dockerfile/Dockerfile) | [```t7-2.3.4(latest)```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.4/Dockerfile/Dockerfile)


### Docker Compose

I created a docker-compose.yml for every version of cmdbuild. (tomcat + postgresql). 

You can use the following : --link option **(deprecated)** or the network feature (since docker 1.10 and docker-compose 1.6).

#### Docker Compose files

##### Links (deprecated)

**Tomcat 6 with java 8**

* [```t6-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-1.4.0.2/Docker-Compose/Links/docker-compose.yml) | [```t6-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-1.5.0/Docker-Compose/Links/docker-compose.yml) | [```t6-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.0.0/Docker-Compose/Links/docker-compose.yml) | [```t6-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.0.3/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.0/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.1/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.2/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.3/Docker-Compose/Links/docker-compose.yml)| [```t6-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.4/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.5/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.6/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.7/Docker-Compose/Links/docker-compose.yml) | [```t6-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.8/Docker-Compose/Links/docker-compose.yml) | [```t6-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.2.0/Docker-Compose/Links/docker-compose.yml) | [```t6-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.2.1/Docker-Compose/Links/docker-compose.yml) | [```t6-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.2.2/Docker-Compose/Links/docker-compose.yml) | [```t6-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.0/Docker-Compose/Links/docker-compose.yml) | [```t6-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.1/Docker-Compose/Links/docker-compose.yml) | [```t6-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.2/Docker-Compose/Links/docker-compose.yml) | [```t6-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.3/Docker-Compose/Links/docker-compose.yml) | [```t6-2.3.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.4/Docker-Compose/Links/docker-compose.yml)


**Tomcat 7 with java 8**

* [```t7-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.4.0.2/Docker-Compose/Links/docker-compose.yml) | [```t7-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.5.0/Docker-Compose/Links/docker-compose.yml) | [```t7-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.0/Docker-Compose/Links/docker-compose.yml) | [```t7-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.3/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.0/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.1/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.2/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.3/Docker-Compose/Links/docker-compose.yml)| [```t7-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.4/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.5/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.6/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.7/Docker-Compose/Links/docker-compose.yml) | [```t7-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.8/Docker-Compose/Links/docker-compose.yml) | [```t7-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.0/Docker-Compose/Links/docker-compose.yml) | [```t7-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.1/Docker-Compose/Links/docker-compose.yml) | [```t7-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.2/Docker-Compose/Links/docker-compose.yml) | [```t7-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.0/Docker-Compose/Links/docker-compose.yml) | [```t7-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.1/Docker-Compose/Links/docker-compose.yml) | [```t7-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.2/Docker-Compose/Links/docker-compose.yml) | [```t7-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.3/Docker-Compose/Links/docker-compose.yml) | [```t7-2.3.4(latest)```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.4/Docker-Compose/Links/docker-compose.yml)


##### Network

**Tomcat 6 with java 8**

* [```t6-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-1.4.0.2/Docker-Compose/Network/docker-compose.yml) | [```t6-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-1.5.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.0.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.0.3/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.1/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.2/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.3/Docker-Compose/Network/docker-compose.yml)| [```t6-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.4/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.5/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.6/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.7/Docker-Compose/Network/docker-compose.yml) | [```t6-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.1.8/Docker-Compose/Network/docker-compose.yml) | [```t6-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.2.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.2.1/Docker-Compose/Network/docker-compose.yml) | [```t6-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.2.2/Docker-Compose/Network/docker-compose.yml) | [```t6-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.0/Docker-Compose/Network/docker-compose.yml) | [```t6-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.1/Docker-Compose/Network/docker-compose.yml) | [```t6-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.2/Docker-Compose/Network/docker-compose.yml) | [```t6-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.3/Docker-Compose/Network/docker-compose.yml) | [```t6-2.3.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat6/t6-2.3.4/Docker-Compose/Network/docker-compose.yml)


**Tomcat 7 with java 8**

* [```t7-1.4.0.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.4.0.2/Docker-Compose/Network/docker-compose.yml) | [```t7-1.5.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-1.5.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.0.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.0.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.0.3/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.1/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.2/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.3/Docker-Compose/Network/docker-compose.yml)| [```t7-2.1.4```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.4/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.5```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.5/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.6```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.6/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.7```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.7/Docker-Compose/Network/docker-compose.yml) | [```t7-2.1.8```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.1.8/Docker-Compose/Network/docker-compose.yml) | [```t7-2.2.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.2.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.1/Docker-Compose/Network/docker-compose.yml) | [```t7-2.2.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.2.2/Docker-Compose/Network/docker-compose.yml) | [```t7-2.3.0```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.0/Docker-Compose/Network/docker-compose.yml) | [```t7-2.3.1```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.1/Docker-Compose/Network/docker-compose.yml) | [```t7-2.3.2```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.2/Docker-Compose/Network/docker-compose.yml) | [```t7-2.3.3```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.3/Docker-Compose/Network/docker-compose.yml) | [```t7-2.3.4(latest)```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.3.4/Docker-Compose/Network/docker-compose.yml)


