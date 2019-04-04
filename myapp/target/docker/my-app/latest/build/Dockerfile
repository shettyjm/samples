FROM registry.access.redhat.com/redhat-openjdk-18/openjdk18-openshift:latest
ENV JAVA_APP_DIR=/deployments JAVA_MAIN_CLASS=com.example.MyApp
EXPOSE 8080 8778 9779
COPY maven /deployments/
