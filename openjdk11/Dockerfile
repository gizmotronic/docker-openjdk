#
# OpenJDK 11 Dockerfile
#

# Pull base image.
FROM ubuntu:18.04

ARG version=11.0.2+9-3ubuntu1~18.04.3

# Install Java.
RUN \
  apt-get update && \
  apt-get install -y openjdk-11-jdk-headless=${version} && \
  rm -rf /var/lib/apt/lists/*


# Define working directory.
WORKDIR /data

# Define commonly used JAVA_HOME variable
ENV JAVA_HOME /usr/lib/jvm/java-11-openjdk-amd64

# Define default command.
CMD ["bash"]
