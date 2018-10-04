# node-docker-template
docker stuff needed build a barebones node express http server image 

### Dependencies
You need to install docker

### Build the image
docker build -t <image_name> .

### Run the container
docker run -p <pick_a_port_to_forward_to>:8080 -d
