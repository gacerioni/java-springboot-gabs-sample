# java11-sprintboot-gabs

## From the project root:
  mvn package

  docker build -t java-springboot-gabs-sample:0.1 -f infra/Dockerfile .


## And...
docker run -p 8080:8080 java-springboot-gabs-sample:0.1
