# Kubernetes Atlanta Meetup: June 2020

- Date: 06.24.2020<!--date as MM.DD.YYYY-->
- Location:
    - Virtual via Zoom
- Speakers:
    - Multi-Cluster Service Mesh with Linkerd 
      - Charles Pretzer (Buoyant.io)<!--presentation title-->
- Hosts:
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- **Kubernetes Release Info**
    - The [1.19 schedule has been changed](https://github.com/kubernetes/sig-release/tree/master/releases/release-1.19), with Code Freeze now on July 9, and Cherry Pick and Test Freeze deadlines on August 6th. [Beta 2](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.19.md/#v1190-beta2) is available.
- **Kubernetes Enhancement PR's of note**
    - [Ingress moving to GA!!!](https://github.com/kubernetes/kubernetes/pull/89778)
        - [KEP](https://github.com/kubernetes/enhancements/blob/master/keps/sig-network/20190125-ingress-api-group.md)
        - [Blog on Ingress updates for K8s 1.18](https://kubernetes.io/blog/2020/06/05/supporting-the-evolving-ingress-specification-in-kubernetes-1.18/)
- **General Community News**
    - [Kubernetes Docs get a facelift](https://kubernetes.io/blog/2020/06/better-docs-ux-with-docsy/)
    - New project making use of Virtual Kubelet
        - There is an interesting effort to implement non-standard kubelets put forward by a consortium at (https://github.com/virtual-kubelet). The idea seems to be around running pods as things like fargate instances, but one new project, [elotl](https://github.com/elotl/kip), actually launches right-sized
	ec2 instances on a per-pod level, based on the pod memory/instance request
    - [Analysis of Kubernetes history with Data Science and Machine Learning](https://kubernetes.io/blog/2020/05/my-exciting-journey-into-kubernetes-history/)
    - [Kubernetes Secret Store CSI Driver](https://github.com/kubernetes-sigs/secrets-store-csi-driver)
    - [GKE Cluster scaled to 15,000 nodes](https://cloud.google.com/blog/products/containers-kubernetes/google-kubernetes-engine-clusters-can-have-up-to-15000-nodes)
      - [Kubernetes Scalability Threshholds](https://github.com/kubernetes/community/blob/master/sig-scalability/configs-and-limits/thresholds.md)
      - [GKE Scalability Guidelines](https://cloud.google.com/kubernetes-engine/docs/concepts/scalability) 

## Meetup Links

## Meetup Slides

## Meetup Recordings

###### tags: `meetup` `2020` `june` `linkerd` `service mesh`