#
# OpenJDK 8 Dockerfile
#

# Pull base image.
FROM ubuntu:16.04

# Install Java.
RUN \
  apt-get update && \
  apt-get install -y openjdk-8-jdk-headless=8u131-b11-2ubuntu1.16.04.3 && \
  rm -rf /var/lib/apt/lists/*


# Define working directory.
WORKDIR /data

# Define commonly used JAVA_HOME variable
ENV JAVA_HOME /usr/lib/jvm/java-8-openjdk-amd64

# Define default command.
CMD ["bash"]
