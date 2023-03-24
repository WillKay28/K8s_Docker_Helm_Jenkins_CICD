# K8s_Docker_Helm_Jenkins_CICD

In this project, I implement a CI/CD pipeline to deploy a docker image into a Kubernetes cluster using Kops, Helm Charts and Jenkins. The state of the K8s cluster is also stored in an S3 bucket. An Amazon Route53 Hosted Zone sub-domain is also created to redirect traffic to a DNS. The docker image is pushed to DockerHub for storage.

In summary, 

1. fetch code from GitHub using Jenkins
2. test and analyze the code using Checkstyle and Sonar Scanner
3. build the docker image using Docker plugin
4. push the docker image to DockerHub
5. deploy the image onto Kubernetes clusters using Helm Charts.

