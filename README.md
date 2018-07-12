# fluentd-elasticsearch

docker-compose -f docker-compose.yml -f example/httpd.yml up

Then, go to your browser and access http://localhost:80 (httpd) and http://localhost:5601 (kibana). 

After you are done, just run:
docker-compose -f docker-compose.yml -f example/httpd.yml rm -f

And all services will be reclaimed.
