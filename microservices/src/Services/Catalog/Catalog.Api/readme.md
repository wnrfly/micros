docker run -d -p 27017:27017 --name shopping-mongo mongo

check logs
docker logs -f shopping-mongo

open iteractive command line
docker exec -it shopping-mongo /bin/bash

open shell mongo
mongosh

create database
use CatalogDb

