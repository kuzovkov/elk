`sudo cp -r /var/lib/docker/volumes/xrankingapi_esdata/_data /var/lib/docker/volumes/elk_esdata/`

`sudo chmod -R a+w /var/lib/docker/volumes/elk_esdata/`

`sudo chmod -R a+x /var/lib/docker/volumes/elk_esdata/`

`sudo docker-compose up -d`


http://localhost:9200/
http://localhost:5601/