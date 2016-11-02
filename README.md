Everything about containers

### Videos
https://www.youtube.com/watch?v=giFKMsIH4b0  -- Container Security  
https://www.youtube.com/watch?v=VIPonFvPlAs  -- Systemd  
https://www.youtube.com/watch?v=93VPog3EKbs  -- Systemd Vs Docker   
https://www.youtube.com/watch?v=kkbrs6YmjMo  -- NoOps -- Kelsey Hightower  
https://www.youtube.com/watch?v=IYcL0Un1io0  -- Custom Scheduler on k8s  -- Kelsey Hightower


### rkt 
https://www.youtube.com/watch?v=E9WVjxaRkKU  -- rkt -- Kelsey Hightower
> Start rkt runtime with k8s
```sh
minikube start \
    --network-plugin=cni \
    --container-runtime=rkt \
    --iso-url=http://storage.googleapis.com/minikube/iso/buildroot/minikube-v0.0.6.iso
```

