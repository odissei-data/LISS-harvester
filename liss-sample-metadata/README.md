# LISS Data 

### OAI-PMH (DC only)
https://www.oai-pmh.centerdata.nl/lissdata/oai2.php?verb=ListRecords&metadataPrefix=oai_dc

### PHP XML
https://www.oai-pmh.centerdata.nl/lissdata/question_texts.php?id=24

### harvest LISS DC using OAI-PMH endpoint 
`docker-compose up`

`docker-compose up -d` if you want to keep the container running in the background

### reharvesting
remove the subfolders in `liss-data`

Then `docker-compose restart harvester` while the container is running

or simply `docker-compose up` when the container is not running

