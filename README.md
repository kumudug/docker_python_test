# Docker Python Test

* Run the rng.py Python file using the official Python image from Docker hub

* `docker build .` - Builds the image
* `docker build . -t pythontest:first` - to give repo and tag

* `docker run -it [imageid]` or `docker run -it [repo:tag]`- Create and run an image with input and TTY

* `docker start -ai [id or name]` - To start the previously created container again with interactive mode to give input. 
   - `docker ps -a` can be used to find the id and/or name of the previously created container.

* Docker Hub image
   - [kumudug/python_test](https://hub.docker.com/repository/docker/kumudug/python_test)