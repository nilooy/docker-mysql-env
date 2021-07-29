## Setup `Mysql` (mariadb) and `PhpMyAdmin` with docker
> Useful for MacOs with M1 chip

** Please setup docker first following official doc: https://docs.docker.com/get-started/

## Commands

## Run mysql and phpmyadmin

- as background process: (Can be started from Docker GUI as well, but necessary for the first time)
```bash 
npm run mysql:up
```
- as terminal process: 
```bash 
npm run mysql:up:process
```

## Kill containers and clean cache: You can use docker gui as well
```bash 
npm run mysql:kill
```

### Credentials
> #### Mysql
  - Port: 3306
  - Host: `localhost`
  - Username: `root`
  - Password:  `password`

> #### Phpmyadmin
  - Url: http://localhost:8080
  - Username: `root`
  - Password:  `password`

