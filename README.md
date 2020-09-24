## Auto-Mirrored from Gitlab to Github and to My Registry

## Please make Pull/Merge Requests on my Gitlab, Issues can be raised anywhere 

### Available on my [Gitlab](https://gitlab.nyeprice.space/moby/docker-icingaweb2) 

### Available on [Github](https://github.com/aneurinprice/docker-icingaweb2) 

### Available on [My Registry](https://registry.nyeprice.space) 


## Docker Image ##
`registry.nyeprice.space/mariadb-docker-icinga2-ido/mariadb-docker-icinga2-ido:latest`

## Current Issues: ##
 
  

Is based on _mariadb:latest_

It's pretty self explanitory. This is a fork of the Official Maraidb Docker Image that comes pre-loaded with the Icinga2 Ido schema. This schemea is automatically imported into the generated database.

For Instructions how to use this image, please see [ The Official Mariadb Docker Documentation](https://hub.docker.com/_/mariadb)





## Example command: ##
  - `docker run -d -p 3306:3306 registry.nyeprice.space/mariadb-docker-icinga2-ido/mariadb-docker-icinga2-ido:latest`