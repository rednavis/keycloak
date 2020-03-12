[![Codacy Badge](https://api.codacy.com/project/badge/Grade/98c823b8ddb6444ca52ad8b7177966c0)](https://app.codacy.com/gh/rednavis/keycloak?utm_source=github.com&utm_medium=referral&utm_content=rednavis/keycloak&utm_campaign=Badge_Grade_Dashboard)
[![Build Status](https://travis-ci.com/rednavis/keycloak.svg?branch=master)](https://travis-ci.com/rednavis/keycloak)
<!--[![Codacy Badge](https://api.codacy.com/project/badge/Grade/7d36295503574b40bb06bd4975dc40f6)](https://app.codacy.com/gh/rednavis/maas-shared?utm_source=github.com&utm_medium=referral&utm_content=rednavis/maas-shared&utm_campaign=Badge_Grade_Settings)-->
[![codecov](https://codecov.io/gh/rednavis/keycloak/branch/master/graph/badge.svg)](https://codecov.io/gh/rednavis/keycloak)

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
admin / admin
irma.pince / irma
sheldon.cooper / sheldon
```

## Run application
`./gradlew bootRun`

## Open web 
http://localhost:8080/index