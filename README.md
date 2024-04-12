# spring-cloud-gcp-starter-secretmanager silently crashed in docker

How to reproduce:

```bash
./gradlew bootBuildImage

docker run docker.io/library/spring-boot-gcp-secretmanager-native-image-crash:1.0-SNAPSHOT
```

The docker silently crashed without any log
