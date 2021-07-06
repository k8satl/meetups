# Kubernetes Atlanta Meetup: June 2021<!--Month Year-->

- **Date:** 06.30.2021<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **Adrien Trouillaud @ Datadog**
    
        Adrien Trouillaud is the creator of the Admiralty open source project. He is also a Senior Software Engineer at Datadog, working remotely from Seattle. Adrien was a speaker at KubeCon Europe 2019 and KubeCon North America 2020. He started using Kubernetes in 2017 while he was a Senior Data Science Engineer at PayScale. In his early career, Adrien developed high-performance numerical simulators at Total, a French multinational oil and gas company. He holds a Master of Science in Engineering from Ecole Centrale Paris.
        
        - **Intro to Admiralty**<!--presentation title-->

            Admiralty is a system of Kubernetes controllers that intelligently schedules pods and their dependencies/dependents across clusters. It is useful in a wide range of multi-cluster applications. As opposed to kubefed and other solutions with their custom APIs and limited scheduling capabilities, Admiralty embraces the familiar Kubernetes API and its powerful scheduler, and decouples them from actual nodes, which can now be in different clusters. It does so by leveraging Virtual Kubelet and the Scheduler Framework. Admiralty is simple to use and integrate with existing tools. As a demonstration, Adrien will deploy a multi-cluster service with Argo CD and run a multi-cluster workflow with Argo Workflows, both integrated with Admiralty.
            
    - **Eldon Stegall**

        Eldon has been bouncing around the Atlanta startup scene for more years than he'd like to admit. His favorite pastimes are reading, hiking, biking, and packet networking analysis, though not necessarily in that order. Opinionated and always interested in getting under the hood of things, Eldon is currently engaged with a low-key physical security IOT startup, and cooking up some infrastructure SaaS products of his own devising.

        - **Intro to Container Network Interface tooling**<!--presentation title-->

            Since the introduction of the Container Network Interface strategy in Kubernetes, the choices available to implement container networking have exploded, but with that choice comes additional complexity. While some of the choices are enabling application observability to improve daily, many of the tools that historically enabled security teams are stumped by the added network layers. We'll take a broad look at some of the tooling that can bridge the gap, and look at the nuts-and-bolts of one such open source example.



- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- v1.22 Release Cycle
    - [v1.22.0-beta.0 Released](https://github.com/kubernetes/kubernetes/releases/tag/v1.22.0-beta.0)
    - [One open critical/urgent bug left](https://github.com/kubernetes/kubernetes/issues/100914)
    - Next Deadline: 
        -  Code Freeze, July 8th
    - Fix Releases
        - v1.21.2
        - v1.20.8
        - v1.19.12
        - v1.18.20
- Promotions
    - [cronjob v2 to GA](https://github.com/kubernetes/kubernetes/pull/102529)
- Deprecations
    - [kubectl --record](https://github.com/kubernetes/kubernetes/pull/102873)
        - [Use http request annotation instead](https://github.com/kubernetes/enhancements/tree/master/keps/sig-cli/859-kubectl-headers)
    - [Balanced Attached Node Volumes](https://github.com/kubernetes/kubernetes/pull/60525/)
        - If you use these speak up now!
- CVE's
    - NA
- PR's of Note
    - [PodSecurity Admission](https://github.com/kubernetes/kubernetes/pull/103099)
        - [KEP](https://github.com/kubernetes/enhancements/tree/master/keps/sig-auth/2579-psp-replacement)
        - [Pod Security Standards](https://kubernetes.io/docs/concepts/security/pod-security-standards/)
    - [Kube API Server supports Distributed Tracing](https://github.com/kubernetes/kubernetes/pull/94942)
    - [kubectl command metadata in HTTP headers](https://github.com/kubernetes/enhancements/issues/859)
    - [exec credential provider](https://github.com/kubernetes/kubernetes/pull/99310)
    - [kubeadm controlplane run as non-root](https://github.com/kubernetes/kubernetes/pull/102759)
    - [Source Code location in JSON logging](https://github.com/kubernetes/kubernetes/pull/102437)
- Community News
    - [Forklift: VMware virtual machines to KubeVirt](https://github.com/konveyor/forklift-documentation)
    - [vcluster: Virtual Clusters within Namespaces](https://github.com/loft-sh/vcluster)
    - [Capsule: multi-tenancy enhancements for K8s](https://github.com/clastix/capsule)
    - [PorterLB: Open Source LB for Baremetal K8s](https://github.com/kubesphere/porterlb)
    - [reconiler-runtime: Picking up where controller-runtime leaves off](https://github.com/vmware-labs/reconciler-runtime)

## Meetup Links

- [https://github.com/adrienjt/demo-k8s-atlanta-meetup](https://github.com/adrienjt/demo-k8s-atlanta-meetup)

## Meetup Slides

## Meetup Recordings
- [Youtube](https://youtu.be/fQpK_AFbK4o)

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup`, `2021`, `june`, `admirality`, `multi-cluster`, `cni` <!--Add additional tags for `year`, `month` and anything else pertinent-->