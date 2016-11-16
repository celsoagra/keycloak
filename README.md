# keycloak
Docker version of Keycloak

This is an example of [Keycloak](http://www.keycloak.org/downloads.html).

# Usage

Try to execute 
```
docker run -d -p 8080 celsoagra/keycloak
```
NOTE: This image provides a standalone wildfly profile for keycloak.

# Profile
```
Login: admin
Password: admin
```

# Urls
```
Wildfly 10 -> localhost:<port>
Keycloak -> localhost:<port>/auth
```

# Docker
The source is available on [Docker Hub](https://hub.docker.com/r/celsoagra/keycloak/).
