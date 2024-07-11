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

# Load balancer
- get traffic in to a single pod

# Ingress
- a pod with a set of routing rules to distribute traffice to other services


==============================================
`kubectl get pods`
- gets all the pod

 `kubectl apply -f .`

 `kubectl rollout restart deployment event-bus-depl`
 - gets the new code deployed