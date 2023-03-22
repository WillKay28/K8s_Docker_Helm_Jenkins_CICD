# K8s_Docker_Helm_Jenkins_CICD

In this project, I implement a CI/CD pipeline to deploy a docker image into a Kubernetes cluster using Helm Charts and Jenkins. I also push the image to DockerHub for storage.

In summary, I  

1. fetch code from GitHub using Jenkins
2. test and analyze the code using Checkstyle and Sonar Scanner
3. build the docker image using Docker
4. push the docker image to DockerHub
5. pull the image and deploy it onto Kubernetes clusters using Helm Charts.

