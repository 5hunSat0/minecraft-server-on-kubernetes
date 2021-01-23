# minecraft-server-on-kubernetes

This repository is for deploying container version minecraft-server in a local kubernetes environment.

- base image : [itzg/minecraft-server:multiarch](https://hub.docker.com/r/itzg/minecraft-server)
- kubernetes version : 1.20.1

 I deploy this deployment and pod on my on-premises kubernetes environment. In my environment, I use ingress to publish the server to the outside. Whitelist and Admin settings are described in secret and read it. Server data and plugins are stored on persistent volumes. Set the pv configuration according to your environment.

