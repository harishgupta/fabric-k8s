# Hyperledger Fabric network on Kubernetes cluster

This repository consists Hyperledge Fabric Artifacts to support the tutorial 
[Deploy Hyperledger Fabric network on Kubernetes cluster](https://medium.com/@harish_gupta/deploy-hyperledger-fabric-network-on-kubernetes-cluster-efee52947b17 "Medium")


# Pre-requisites
One should have a basic understanding on containerization tech and basic know how of Kubernetes works, plus the following 
* A Kubernetes cluster up and running with access to it via kubectl. If you wish to setup one from scratch please follow the tutorial here "[Setup a Kubernetes cluster from scratch](https://medium.com/@harish_gupta/setup-a-kubernetes-cluster-from-scratch-8ea9ee9e5655)" 
* An NFS server or equivalent. You can setup an NFS server using the tutorial [here](https://www.digitalocean.com/community/tutorials/how-to-set-up-an-nfs-mount-on-ubuntu-16-04). You only need server side setup as Kubernetes cluster will act as client
* Network artifacts (Crypto material and genesis block) generated for the network you wish to deploy. You can find the artifacts used in this repo.
* Knowledge of common operations using kubectl commands is highly recommended
