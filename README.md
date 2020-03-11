# keycloak

## Install Keycloak
https://www.keycloak.org/downloads.html

## Copy database
Copy **keycloak.mv.db** to **keycloak/standalone/data/**

## Make standalone.sh executable 
`chmod +x standalone.sh`

## Run KeyClock
`sh standalone.sh -Djboss.socket.binding.port-offset=100`

## User pages
http://localhost:8180/auth/realms/public-library/account/
```
irma.pince / irma
sheldon.cooper / sheldon
```

## Run application
`./gradlew bootRun`

## Open web 
http://localhost:8080/index