# EriccsonChallenge
This repo contains the deploment.yaml file and service.yaml file

In hello-app-deployment.yaml, the hello-app base image is used. 
And, in the hello-app-service.yaml file, a load balancer serviceis created.

After creating these files, they are applied using the kubectl apply command

And finally using minikube service command, the service is run and an URL is received.

Upon running a cURL commmand for the URL, the following outputi s received:
![Screenshot 2023-03-15 at 9 39 09 AM](https://user-images.githubusercontent.com/64781077/225325803-278ce9d7-af14-44e4-9b29-f8fa439a3125.png)
