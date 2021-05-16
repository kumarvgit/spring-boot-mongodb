#### Get logs of docker
> docker logs -f <container is>

#### Images are immutable and image is created by fs layers

#### get fs of container
> docker image inspect mongo:3.4.1

#### No Truncation on aoutput
> docker images  --no-trunc

#### Display only ids
> docker images -q --no-trunc

#### Docker tag names convention
> REGISTRYHOSTNAME/USERNAME:VERSION