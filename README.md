A bare bones [Docker](https://docker.io) [Compose](https://docs.docker.com/compose/) recipe, with [Docker Hub PHP Apache](https://hub.docker.com/_/php) and [MariaDB](https://mariadb.org) as the backend. Doesn't do anything by itself; is meant to be a launching off point for making PHP Docker apps.
 
Note: ```extras.yml``` is referred to in ```docker-compose.yml``` but is not checked into git, as it contains passwords. Copy ```extras-template.yml``` to ```extras.yml``` and edit that.

