# docker-gradle-hello-world

# Run image
gradle run impks/docker-gradle-hello-world

# Create image
gradle buildDocker

# Publish your image to docker hub
gradle buildDocker -Ppush
