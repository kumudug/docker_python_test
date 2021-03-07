# Docker Python Test

* Run the rng.py Python file using the official Python image from Docker hub

* `docker build .` - Builds the image

* `docker run -it [imageid]` - Create and run an image with input and TTY

* `docker start -ai [id or name]` - To start the previously created container again with interactive mode to give input. 
   - `docker ps -a` can be used to find the id and/or name of the previously created container.