# Kubernetes Atlanta Meetup: July 2021<!--Month Year-->

- **Date:** 07.28.2021<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **Daniel Mangum @ Upbound** <!--presenter name @ company-->
    
        Daniel Mangum is a senior software engineer at Upbound where he is a maintainer of Crossplane, an open source CNCF project. He also is a Technical Lead for Kubernetes SIG Release and is an active contributor to the Kubernetes project and multiple other open source efforts. He hosts a biweekly live stream show, The Binding Status, focused on extending Kubernetes, building Crossplane, and enabling a cloud native future.
        
        - **Day 2 Operations on Crossplane**<!--presentation title-->

            Crossplane is a CNCF project and Kubernetes add-on that allows users to build an infrastructure platform on top of primitives from popular cloud providers, on-premise solutions, and anything else that exposes an API. This gives infrastructure administrators the ability to allow developers within an organization to safely self-service their infrastructure resources without having to understand the underlying implementation details. However, some infrastructure operations, such as backups, migrations, and updates are difficult to model using the Kubernetes API. In this session, we will explore how these heterogeneous operations can be modeled in Crossplane, and examine the advantages of adopting a control plane approach to managing infrastructure. Attendees will gain an understanding of the core concepts of Crossplane, while also being introduced to advanced usage patterns and best practices. Live demos will include examples of utilizing the latest Crossplane features, as well as yet to be released functionality.

    - **Duffie Cooley @ Isovalent**

        Duffie is Field CTO at Isovalent focused on helping enterprises find success with technologies like eBPF and Kubernetes. Duffie has been working with all things virtualization and networking for 20 years and remembers most of it. He likes to present on topics ranging from How do I solve this problem with Kubernetes to What even is a CNI implementation and which one should I choose?. A student of perspective, Duffie is always interested in working through problems and design choices from more than one perspective.
        
        - **Cilium & eBPF - Cloud Native Networking Security and Observability**

            eBPF is one of the fastest emerging kernel technologies. Projects like Cilium leverage eBPF to provide highly scalable and efficient networking, security and observability for containers and microservices. This talk will provide an introduction to both eBPF and Cilium. We’ll explore how eBPF enables the dynamic insertion of powerful security, visibility, and control logic within the OS kernel, then dive into how Cilium leverages the power of eBPF to deliver efficient load balancing, multi-cluster networking, security policies, deep observability, transparent encryption and much much more.

    

- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- v1.22 Release Cycle
    - [v1.22.0-rc.0 Released](https://github.com/kubernetes/kubernetes/releases/tag/v1.22.0-rc.0)
    - [A handful of remaining test fails/flakes](https://groups.google.com/g/kubernetes-dev/c/F3Mpjv2ximM)
    - Next Deadline: 
        -  Hopefully release on August 4th
    - Fix Releases
        - v1.21.3
        - v1.20.9
        - v1.19.13
- Promotions
    - NA
- Deprecations
    - NA
- CVE's
    - [CVE-2021-25740](https://github.com/kubernetes/kubernetes/issues/103675)
        - https://access.redhat.com/security/cve/cve-2021-25740
        - https://security-tracker.debian.org/tracker/CVE-2021-25740
- PR's of Note
    - NA
- Community News
    - [Contributor Summit NA 2021 planning has begun!](https://www.kubernetes.dev/events/kcsna2021/)
    - [Fejta Bot retired, long live k8s-triage-robot](https://groups.google.com/g/kubernetes-dev/c/oD_ijk7jpa8)
        - [Fun times with Fejta Bot](https://github.com/kubernetes/test-infra/issues/6464)
        - Thanks @fejta
    - [Proposal to use a DAG for sidecar container dependencies](https://docs.google.com/document/d/15Ker0cm6n3auAy_lYmvthilhTxF8OVisjl_52nTQJBE/edit)
    - [Helm Repository Credentials Security Hole](https://github.com/helm/helm/security/advisories/GHSA-56hp-xqp3-w2jf)
    - [Run containers in separate mount namespace](https://github.com/kubernetes/community/pull/5724)
    - [Kubernetes Release Cadence Change](https://kubernetes.io/blog/2021/07/20/new-kubernetes-release-cadence/)
    - [Sysbox Container Runtime](https://github.com/nestybox/sysbox)
    - [Argo Vulnerability leads to cryptomining](https://news.bitcoin.com/kubernetes-clusters-used-to-mine-monero-by-attackers/)
    - [CNCF Operator White Paper](https://github.com/cncf/tag-app-delivery/blob/master/operator-wg/whitepaper/Operator-WhitePaper_v1-0.md#)
    - [Admission Control: A micro-framework for Kubernetes Dynamic Admission Controllers](https://blog.questionable.services/article/kubernetes-admission-control/)
    - [Kubelet + Rust + WASM = Krustlet](https://thenewstack.io/krustlet-brings-webassembly-to-kubernetes-with-a-rust-based-kubelet/)

## Meetup Links

## Meetup Slides

## Meetup Recordings

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` `2021`, `july`, `isovalent`, `cilium`, `ebpf`, `upbound`, `crossplan.io`, `network`, `security`, `observability`<!--Add additional tags for `year`, `month` and anything else pertinent-->