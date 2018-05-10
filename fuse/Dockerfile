# dockerfile image Jboss Fuse Java 6

FROM registry.access.redhat.com/jboss-fuse-6/fis-java-openshift

# file author / maintainer
MAINTAINER "FirstName LastName" "emailaddress@gmail.com"

# Copy jar to deployments folder
COPY app.jar /deployments/

# Modify owners jar
USER root
RUN chown jboss:root /deployments/app.jar

# Run whit user 185
USER 185

