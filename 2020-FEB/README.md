# Kubernetes Atlanta Meetup: February 2020

- Date: 02.26.2020 <!--date as MM.DD.YYYY>-->
- Location:
    - Salesloft HQ Atlanta
- Speakers:
    - Kubernetes Runtime Security with Falco
        - Gary Hutchins, Solutions Architect from Sysdig <!--<speaker name/company>-->
- Hosts:
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- Kubernetes 1.18 is in beta
    - Tracking 50 enhancements
    - Code freeze scheduled for Thursday, March 05, 2020 [sig-release/releases/release-1.18](https://github.com/kubernetes/sig-release/tree/master/releases/release-1.18)
    - Release scheduled for Tuesday, March 24
    - [Enhancement tracking sheet](http://bit.ly/k8s-1-18-enhancements)
        - [Sidecar Containers](https://github.com/kubernetes/enhancements/issues/753)
        - [Configurable scale velocity for HPA](https://github.com/kubernetes/enhancements/issues/853)
        - [Even pod spreading across failure domains](https://github.com/kubernetes/enhancements/issues/895)
        - [kubectl events](https://github.com/kubernetes/enhancements/issues/1440)
        - [kubectl debug](https://github.com/kubernetes/enhancements/issues/1441)
- [Architecting Kubernetes clusters — how many should you have?](https://learnk8s.io/how-many-clusters)
- [CPU limits and aggressive throttling in Kubernetes](https://medium.com/omio-engineering/cpu-limits-and-aggressive-throttling-in-kubernetes-c5b20bd8a718)
- [containerd implementation using firecracker microVM manager](https://github.com/firecracker-microvm/firecracker-containerd)
    - incorporating hypervisor capabilities as an additional security feature for workload isolation. Similar work has been done with rkt (now likely mothballed), and active projects including gVisor from google, and kata containers from openstack.
- Projects deprecating support for older k8s version
    - Knative: https://github.com/knative/serving/releases/tag/v0.12.1
    - Azure: https://github.com/Azure/AKS/blob/master/CHANGELOG.md
        - This is awkward, due to the fact that Amazon's EKS, a significant player in the space, [hasn't yet released 1.15](https://github.com/aws/containers-roadmap/issues/380)
- [Comparing managed kubernetes offerings: EKS vs GKE vs AKS](https://www.stackrox.com/post/2020/02/eks-vs-gke-vs-aks/)
- [AppProtocol on Service and Endpoints Ports merged to k/k master](https://github.com/kubernetes/kubernetes/pull/88503)
    - Associated [KEP](https://github.com/kubernetes/enhancements/blob/master/keps/sig-network/20191227-app-protocol.md)

## Docs / Guides 

-  [Troubleshooting Kubernetes deployments pdf file](https://github.com/nikhilgorantla/docs/blob/master/troubleshooting-kubernetes.pdf)
	-  [Credits - Learnk8s](https://learnk8s.io/troubleshooting-deployments)


## Meetup Links

## Meetup Slides
-  [Kubernetes Runtime Security
with Falco and Sysdig Slides](https://drive.google.com/file/d/1k-VNbKTdQIY6FCRI1NW7gPLZNHAIV13v/view)
## Meetup Recordings

###### tags: `meetup` `2020` `february`