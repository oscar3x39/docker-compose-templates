# Examples files

## Drone
Drone is a self-service Continuous Delivery platform for busy development teams.

See https://docs.drone.io/server/provider/github

```
- drone:latest
- agent:latest
```

## Laravel
`Laravel is a php web framework.`
```
- nginx:stable
- mysql:5.7
- php7.2-fpm
```

Usage:
```
cd src
laravel new
cd ..
make up
```

## Harbor
Harbor is an open source container image registry that secures images with role-based access control.

Usage:
```
make up
make down -v
```


## RocketChat
The ultimate Free Open Source Solution for team communications.

```
- rocket.chat:latest
- mongo:4.0
- hubot:latest
```

## Jenkins
an open source automation server which enables developers around the world to reliably build, test, and deploy their software.
