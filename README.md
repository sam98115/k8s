# pull k8s from gcr

step 1: check available docker images from https://console.cloud.google.com/gcr/images/google-containers/GLOBAL 
step 2: create the docker fine in github, e.g.: kube-scheduler/v1.20.0-alpha.0.tag, content of the content:
        FROM gcr.io/google-containers/kube-scheduler:v1.20.0-alpha.0

step 3: connect docker hub to github

step 4: create docker repository in hub.docker.com, one docker repository for one k8s dockerfile
step 5: configure the build of the repository


