# Spring Cache with Redis Example

This project is a simple example of an application that uses a Redis database to cache the result from the API
endpoints. The example is based on the article by [JournalDev](https://www.journaldev.com/18141/spring-boot-redis-cache)
with some adjustments to fix some errors. Tests and a dockerfiler integrating the project and a Redis container will be
added later. 

## Important features used

* @EnableCaching annotation
* Redis configured through application properties
* @Cacheable annotation
* @CachePut annotation
* @CacheEvict annotation
* Repository pattern

## Features to be implemented

* Dockerfile
* Build & create docker image
* Docker compose to integrate the project with redis
 