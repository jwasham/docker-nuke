# docker-nuke

This bash script removes all Docker containers, volumes, and images.

It is useful when developing a new container or composition and you want to make sure there are no other artifacts from a previous run that are affecting your Docker environment.

To use:

    chmod +x docker-nuke.sh
    ./docker-nuke.sh
