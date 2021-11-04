# Kafka Microservices

BashScript for Mac that clones, builds and runs different Kafka Microservices (Producers & Streams).


## Setup on MacOS

install homebrew: https://brew.sh/

# Install Java, Docker, k9s, ...

    brew install openjdk k9s kafka gradle kubernetes-cli micronaut
    brew install --cask docker

# Go to DockerHub and setup the following three repos:
     - number-merger-kafka-streams
     - number-gen-kafka
     - number-gen-kafka-2

# Edit your Docker Hub Credentials
Open your gradle.properties file. You will find it here:
    $HOME/.gradle/gradle.properties

Insert the following two lines:
    dockerHubUser=youDockerHubUserName
    dockerHubPassword=youDockerHubPassword

Make sure not to insert spaces before of after the equals "=" sign. 
