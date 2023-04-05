FROM OpenJDK:11
EXPOSE 8083
ADD target/Kubernetes-0.0.1-SNAPSHOT.jar Kubernetes-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/Kubernetes-0.0.1-SNAPSHOT.jar"]