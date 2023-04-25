# spring-boot-flyio

Deploy Springboot application on fly.io

mvn clean spring-boot:build-image

fly launch --image docker.io/library/demo:0.0.1-SNAPSHOT

fly deploy --local-only --image demo:0.0.1-SNAPSHOT
