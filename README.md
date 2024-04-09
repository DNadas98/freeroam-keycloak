# freeroam-keycloak

Containerized KeyCloak Identity and Access Manager

### Setup & Run

- Copy `env.txt` and rename to `.env`, modify values
- Run `docker-compose up --build -d`
- Access KeyCloak at the specified URL in `.env`, at the specified port in the `docker-compose.yml`,
  by default `http://localhost:8090`
