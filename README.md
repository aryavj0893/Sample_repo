# liquibase-chinook
presentation of liquibase, using the fantastic project https://github.com/lerocha/chinook-database to show the multi-db capabilities

# Postgresql
## Pre requisite
schema: "liquibase" is mandatory

# Launch liquibase update 
mvn clean liquibase:update -Ppostgresql