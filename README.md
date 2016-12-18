# wordpress-docker-example

### build proxy image

     docker build -t example-proxy ./proxy/.

### build blog image

      docker build -t example-blog ./blog/.


### get local service up
     docker-compose -f docker-compose-blog.yml up
	 