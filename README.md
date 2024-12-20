# docker-postgres
Create docker images for PostgreSQL and PGAdmin

## usage

1. cd into the `compose` directory
2. run `docker-compose up -d` to start the containers in detached mode
3. launch PGAdmin in browser -> `http://localhost:8081`
4. Add a new server in PGAdmin and give it a name
5. add these connection properties:
     * Host: postgres
     * Port: 5432
     * Username: admin (as set in POSTGRES_USER).
     * Password: admin (as set in POSTGRES_PASSWORD).
7. 
