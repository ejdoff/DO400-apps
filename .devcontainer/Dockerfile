FROM fedora:31

RUN dnf -y install git java-11-openjdk-devel
RUN dnf -y module enable nodejs:14 && dnf -y install nodejs

# Install OC command
RUN mkdir /opt/oc
COPY oc /opt/oc/
ENV PATH="/opt/oc:${PATH}"
ENV JAVA_HOME="/usr/lib/jvm/java-11-openjdk"
