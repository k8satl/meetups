# Kubernetes Atlanta Meetup: January 2021<!--Month Year-->

- **Date:** 01.27.2021<!--date as MM.DD.YYYY-->
- **Location:**
    - [Virtual via Zoom](https://www.meetup.com/Kubernetes-Atlanta-Meetup/events/275682440/)
- **Speakers:**
    - **Cluster API With a Bit of PXE Dust:** `bringing cloud-native declarative management of Kubernetes clusters into the datacenter`<!--presentation title-->
        
        **Jason DeTiberus** @ **Packet (an Equinix company)**<!--speaker name/company-->
    
        Jason is a Senior Staff Engineer at Packet (an Equinix company), where he brings cloud-native infrastructure management into the datacenter.

        Jason lives in Eastern North Carolina and enjoys collecting various hobbies and projects that rarely see completion. He can often be found daydreaming what hobby to start next, watching the Geese fly by, or honking at people on Twitter.

- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- Kubernetes Release Info
    - 1.21.0-alpha.1 has been released
    - Make sure you add your enahncements in the [tracking sheet](http://bit.ly/k8s121-enhancements)
    - Enhancements Freeze, Feb. 9
    - 1.20.2, 1.19.7, 1.18.15, and 1.17.17 patch releases have dropped
- PR's of Note
    - Kubernetes Interface Definition Label (IDL)
        - [KEP](https://github.com/kubernetes/enhancements/pull/2310)
- Deprecations
    - Pod Security Policies
        - Deprecated in k8s 1.21, marked for removal in 1.25
        - [PR (includes links to meeting minutes, docs, and presentation)](https://github.com/kubernetes/kubernetes/pull/97171)
        - [Some further discussions](https://groups.google.com/g/kubernetes-sig-auth/c/a7zPYU-IRAA)
- Community News
    - [aledbf stepped down as maintainer of ingress-nginx](https://github.com/kubernetes/ingress-nginx/pull/6729)
        - We want to take a moment to echo a lot of the community sentiments in how much of an impact aledbf has had on the nginx-ingress project and the overall Kubernetes ecosystem. Thank you for all that you've done!
        - Project is looking for new Maintainers
    - [kube-state-metrics](https://github.com/kubernetes/kube-state-metrics/) Project is looking for new Maintainers
    - COSI (Container Object Storage Interface)
        - KEP: https://github.com/kubernetes/enhancements/tree/master/keps/sig-storage/1979-object-storage-support
        - Controller: https://github.com/kubernetes-sigs/container-object-storage-interface-controller
    - Kubebuilder Declarative Pattern - https://github.com/kubernetes-sigs/kubebuilder-declarative-pattern
        - Can define GitResource/HTTPResource to pull from
        - Discover and Filter manifests
        - Define subscriptable channels for versions
        - A number of primitive operations like adding labels on all resources
        - The ability to perform raw substitution or use kustomize
        - Essentially kubectl apply inside a controller
    - Cluster API Provider Nested - https://github.com/kubernetes-sigs/cluster-api-provider-nested/blob/master/proposals/20201026-creating-control-plane-components.md
        - Has a super cluster that hosts multiple control plane instances that run as pods.
        - Makes use of Kubebuilder declarative pattern
    - Envoy 1.17.0 released
        - [Release Notes](https://www.envoyproxy.io/docs/envoy/v1.17.0/version_history/current)
    - [The Anatomy of Kubernetes ListWatch(): Prologue](https://www.mgasch.com/2021/01/listwatch-prologue/)
    - [https://www.k8sref.io](https://www.k8sref.io)
        - [Blog](https://kubernetes.io/blog/2020/12/04/gsod-2020-improving-api-reference-experience/)
    - [Kubernetes Global Balancer](https://www.k8gb.io)
        - [GitHub](https://github.com/AbsaOSS/k8gb)

## Meetup Links

## Meetup Slides

## Meetup Recordings

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup`, `2021`, `january`, `packet`, `equinix`, `clusterapi`, `capi` <!--Add additional tags for `year`, `month` and anything else pertinent-->