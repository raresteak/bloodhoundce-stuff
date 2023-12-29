# Operational notes
### Vendor docs
```
https://support.bloodhoundenterprise.io/hc/en-us/articles/17715215791899-Getting-started-with-BloodHound-Community-Edition
```

### Console UI url
```
 http://localhost:8080/ui/login
```

### Starting containers after installation
From within the same folder as docker-compose.yml
```
docker-compose start
```
If any container fails to start, wait a minute or so then execute the command above again.

### Stopping containers
From within the same folder as docker-compose.yml
```
docker-compose stop
```

### Updating containers
From within the same folder as docker-compose.yml
```
docker-compose up
```

### Removing containers
From within the same folder as docker-compose.yml
```
docker-compose down
```

### Run a collection
https://support.bloodhoundenterprise.io/hc/en-us/articles/17715215791899-Getting-started-with-BloodHound-Community-Edition


### Uploading new data
https://support.bloodhoundenterprise.io/hc/en-us/articles/17715215791899-Getting-started-with-BloodHound-Community-Edition
1. Unzip ingestor zip file
2. Login to console UI
3. Click cog on right and select Administrator or go to http://localhost:8080/ui/administration/file-ingest
4. Click upload files
5. Wait for ingestion to complete.
6. Click Data Quality, select domain, inspect information.
7. Click Explore to work with data.
8. Click Cypher, then click the folder to open supplied searches.

