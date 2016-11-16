# keycloak
Docker version of Keycloak

This is an example of [Keycloak](http://www.keycloak.org/downloads.html).

# Usage

Try to execute 
```
docker run -d -p 8080:8080 celsoagra/keycloak
```
NOTE: This image provides a standalone wildfly profile for keycloak. Please, don't change the port of local host. When the port is changed (such as 8081:8080), an error occurs.

# Profile
```
Login: admin
Password: admin
```

# Urls
```
Wildfly 10 -> localhost:8080
Keycloak -> localhost:8080/auth
```

# Source
The source is available on [GitHub](https://github.com/celsoagra/keycloak).
