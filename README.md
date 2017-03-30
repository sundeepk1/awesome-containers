Everything about containers

### Openshift

#### Videos
https://www.youtube.com/channel/UCZKMj3YI0wP-kq4QYpaKdEA       -- Openshift Official Channel
https://www.youtube.com/playlist?list=PLS92o8LZHcPSGHxlK65EMMuaL4OUM2ded    --  Chakradhar Rao Jonagam Channel
https://www.youtube.com/channel/UCUMY5vAIUPlKzZm_LEtFUJA    -- Seth Jennings
https://www.youtube.com/watch?v=giFKMsIH4b0  -- Container Security  
https://www.youtube.com/watch?v=VIPonFvPlAs  -- Systemd  
https://www.youtube.com/watch?v=93VPog3EKbs  -- Systemd Vs Docker   
https://www.youtube.com/watch?v=kkbrs6YmjMo  -- NoOps -- Kelsey Hightower  
https://www.youtube.com/watch?v=IYcL0Un1io0  -- Custom Scheduler on k8s  -- Kelsey Hightower


#### Blogs
https://blog.openshift.com/     -- Openshift Blog, most recent updates on openshift

#### Examples
https://github.com/debianmaster/openshift-examples     -- Openshift Examples by Chakradhar Rao Jonagam


#### Colloboration
`#openshift-dev`     -- freenode     
openshiftcommons.slack.com   --slack    

#### Presentations
http://redhat.slides.com/cjonagam/ocp-story?token=xMmIKbOn    -- Story for Dev/Ops w/ Openshift



### Runtimes
#### rkt
https://www.youtube.com/watch?v=E9WVjxaRkKU  -- rkt -- Kelsey Hightower
> Start rkt runtime with k8s
```sh
minikube start \
    --network-plugin=cni \
    --container-runtime=rkt \
    --iso-url=http://storage.googleapis.com/minikube/iso/buildroot/minikube-v0.0.6.iso
```


