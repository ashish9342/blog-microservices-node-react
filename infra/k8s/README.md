# Build image for the event bus
docker build -t daemonwolfdev/event-bus .

# Push image to Docker hub
docker push daemonwolfdev/event-bus

# Create a deployment
- create even-bus.depl file config as posts
- kubectl apply -f event-bus-depl.yaml 
- deployment created and creats the pods for us

# Create a cluster IP servicesfor event bus and posts
- 
==============================================
`kubectl get pods`
- gets all the pod