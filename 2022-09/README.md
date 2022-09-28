# Kubernetes Atlanta Meetup: September 2022<!--Month Year-->

- **Date:** 09.28.2022<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **Christian Posta, VP & Global Field CTO @ Solo.io** <!--presenter name @ company-->
    
        Christian Posta (@christianposta) is Global Field CTO at Solo.io, former Chief Architect at Red Hat, and well known in the community for being an author (Istio in Action, Manning, Istio Service Mesh, O'Reilly 2018, Microservices for Java Developers, O’Reilly 2016), frequent blogger, speaker, open-source enthusiast and committer on various open-source projects including Istio, Kubernetes, and many others. Christian has spent time at both enterprises as well as web-scale companies and now helps companies create and deploy large-scale, cloud-native resilient, distributed architectures. He enjoys mentoring, training and leading teams to be successful with distributed systems concepts, microservices, devops, and cloud-native application design.
        
        - **The Future of Istio is sidecar-less**<!--presentation title-->

            Every service mesh, including Istio, uses a sidecar proxy as its data plane. With this pattern, a mesh can intercept and enhance the capability of networking communication on behalf of an application. However, and unfortunately, this sidecar deployment pattern comes with a price to pay in terms of operations, complexity, and performance. With the advent of eBPF in modern operating systems, and some coordination with the Linux networking capabilities, we can look forward to improvements in service mesh architecture including moving away from a sidecar approach to a more transparent approach. In this talk we dig into the future of Istio, which I work on, to show how Istio can be run in a sidecarless mode.
    - **Leigh Capili, Staff Developer Advocate @ VMware** <!--presenter name @ company-->
    
        Leigh is an empathetic speaker and developer with niches in cloud-native systems and security. He has a background in building software to manage infrastructure.

        Leigh contributes to Kubernetes and Flux and is frequently working on his next software demo. He also co-maintains Ignite, the microVM manager with Docker UX. (https://ignite.rtfd.io/)

        Leigh works with the VMware Tanzu Advocacy team and previously built Developer Experience and Platform with Weaveworks, Beatport, AT&T, and DIRECTV.

        Leigh enjoys snowboarding with his wife and has a 60lb dog named Pepsi.
        
        - **Packaging vcluster with Carvel**<!--presentation title-->

            Jump in with Leigh Capili for an adventure into the fun components and quirks of `vcluster` the awesome open-source project from Loft. This project is very exciting because it enables a multi-tenancy model that empowers platform builders to implement controls and features while also enabling end-users to have access and freedom within their virtual-cluster boundary.
            
            Expect Leigh to bring his hacking spirit and obsession with developer experience along!
Flux now supports OCI sources, and Carvel has a new package creation workflow ;) (`kctrl package`).
See you for the demo!
- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- v1.26 Release Cycle <!-- Link to latest release for the current K8s release cycle -->
    - Have your draft KEPs ready for the PRR team by Thursday, and final versions opted-in by Oct. 6. Current CI signal is green
    - Next Deadline: Production Readiness Sept. 29th<!-- Date and general description for the next release cycle deadline -->
    - Fix Releases <!-- List of latest fix releases for supported/maintained Kubernetes version -->
        - The September 15th patch releases [broke user applications](https://groups.google.com/a/kubernetes.io/g/dev/c/tA6LNOQTR4Q). As such, new patch releases for 1.25.2, 1.24.6, 1.23.12, and 1.22.15 were pushed on Sept. 21. Users should skip the prior update and go straight to this one.
        - v1.25.2
        - v1.24.6
        - v1.23.12
        - v1.22.15
- Promotions <!-- List of any interesting feature/API promotions -->
    - NA
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - [In-tree cloud provider auth for kubectl is removed again for 1.26](https://github.com/kubernetes/kubernetes/pull/112341)
- CVE's <!-- List of any Kubernetes related CVE's -->
    - [CVE-2022-3172 - Allows aggregated API servers to misdirect traffic and steal credentials](https://github.com/kubernetes/kubernetes/issues/112513)
    - [CVE-2021-2574](https://github.com/kubernetes/kubernetes/issues/112192)
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - [Add auth API to get self subject attributes](https://github.com/kubernetes/kubernetes/pull/111333)
- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - [COSI: Object Storage Management using Kubernetes](https://kubernetes.io/blog/2022/09/02/cosi-kubernetes-object-storage-management/)
    - [Security Checklist for Clusters](https://kubernetes.io/docs/concepts/security/security-checklist/)
    - [Official CVE Feed - Alpha](https://kubernetes.io/docs/reference/issues-security/official-cve-feed/)
        - For machines: `$ curl -Lv https://k8s.io/docs/reference/issues-security/official-cve-feed/index.json`
        - [Blog Post](https://kubernetes.io/blog/2022/09/12/k8s-cve-feed-alpha/)
    - [Testing Kubernetes operators using EnvTest](https://www.infracloud.io/blogs/testing-kubernetes-operator-envtest/?utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-8-AZSSSkSGwDWQPTjjlwt6X_LczIZigbAkshtQrfozIfeMo-leSIPVa75ZJxXg_dB6caEc)

## Meetup Links

- [Cody Crudgington Memorial Site](https://everloved.com/life-of/cody-crudgington/)

## Meetup Slides

## Meetup Recordings

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` `september` `2022` `cody crudgington` `istio` `ambient mesh` `service mesh` `sidecarless` `carvel` `vcluster` `oci` `imgpkg` <!--Add additional tags for `year`, `month` and anything else pertinent-->