# Kubernetes Atlanta Meetup: February 2021<!--Month Year-->

- **Date:** 02-24-2021<!--date as MM.DD.YYYY-->
- **Location:**
    - [Virtual via Zoom](https://www.meetup.com/Kubernetes-Atlanta-Meetup/events/276201050/)
- **Speakers:**
    - **Modern Networking in Kubernetes through an Edge Gateway**

        Edge Gateways are the first stop from the outside world before reaching your application services, meaning that they have the ability to control all of the traffic. In this talk we'll use Istio, Web Assembly, Envoy andGloo Edge community edition to cover:
        - What the difference is between Gateways vs Ingress vs Service Mesh Ingress Gateways
        - High level Architecture of the API Gateway (Control Plane/Data Plane)
        - How to rate limit services
        - How to transform header information before it gets to your application
        - How to provide authentication using Oauth2 OIDC with Google as the identity provider
        - How to filter network requests to a Kubernetes service by hostname for added security
        - How to rewrite your application routes
        - How to encrypt cluster traffic with mutual TLS
        - How to apply these principles in a demo

        **Casey Wylie** @ **Solo.io**

        Casey is a Field Engineer at Solo.io, and generalist software engineer with a special interest in Cloud Native computing. As a former senior consultant and current field engineer, he is customer obsessed. He is friendly, and loves to chat all things dev so feel free to shoot him a message!
    - **Kubernetes and eBPF**
        
        One of our organizers will be doing a short talk showing the power of BPF tracing and how it can be used with Kubernetes

        **Alex Barnes** @ **DataDog**

- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- Kubernetes Release Info
    - 1.21.0-beta.0 released
    - Next Deadline: March 1 - [Feature Blog Inclusion](https://docs.google.com/spreadsheets/d/1-rFkGmpyDN39gY2M_RX6Ugs_AIig9GXw1FkRLWWmWfw/edit?ts=6023741c#gid=0)
    - Fix Releases (Bug fix only, no CVE's)
        - v1.20.4
        - v1.19.8
        - v1.18.16
    - PR's of Note
        - ["kubectl get" says bye bye managed fields!!!](https://github.com/kubernetes/kubernetes/pull/96878)
        - [NUMA memory manager for Kubelet](https://github.com/kubernetes/kubernetes/pull/95479)
    - Promotions
        - [PDB's hopefully moving to GA in v1.21](https://github.com/kubernetes/enhancements/pull/2114)
    - Deprecations
        - [Many v1beta1 API's going away in v1.22 (ie. CRD's, webhooks, etc.)](https://groups.google.com/g/kubernetes-dev/c/z_AE1EHhZF4)
- Community News
    - [Persistnt Memory CSI Driver](https://github.com/intel/pmem-csi)
    - [Gatekeeper Community Policy Library](https://github.com/open-policy-agent/gatekeeper-library)
    - [Kubernetes Resource Filter](https://github.com/ryane/kfilt)
    - [KinD multi-cluster routing](https://gist.github.com/aojea/00bca6390f5f67c0a30db6acacf3ea91#multiple-clusters)
    - [Network Policy Visualizer/Editor](https://editor.cilium.io)
    - [Controller Rate Limiting](https://danielmangum.com/posts/controller-runtime-client-go-rate-limiting/)

## Meetup Links

- [Sample Code from Casey](https://github.com/cmwylie19/envoy-kube-talk)
- [Frontend Code from Casey](https://github.com/cmwylie19/envoy-kube-talk-frontend)

## Meetup Slides

## Meetup Recordings

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` <!--Add additional tags for `year`, `month` and anything else pertinent-->