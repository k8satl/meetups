# Kubernetes Atlanta Meetup: January 2022<!--Month Year-->

- **Date:** 01.26.2022<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **Parth Patel @ BoxBoat** <!--presenter name @ company-->
    
        Parth Patel is a DevOps engineer at BoxBoat an IBM Company. Contributor to various secure supply chain projects such as Tekton Chains and in-toto-golang. In his free time, Parth likes to travel and fly FPV drones.
        
        - **Secure Supply Chain, Tekton Chains**<!--presentation title-->

            Supply chain attacks have become predominant in the past few years and companies are scrambling to secure their software supply chain. Trying to understand and overcome this problem is no easy feat.

            Various tools and cloud native solutions have stepped up to help ease the integration of security practices based on SLSA (Supply-chain Levels for Software Artifacts) security levels. Tekton, a cloud native solution for building CI/CD systems, is one of these tools that has a lot to offer. With the addition of Tekton Chains, companies are empowered to shift security left and create DevSecOps pipelines to improve the security of their build and release process.

            Learn more about Tekton Chains and how it can be used with Tekton Pipelines (CI/CD) to create signed provenance! In this presentation we will walk through initial setup, configuration and how to verify the final provenance.

    - **Jim Bugwadia @ Nirmata** <!--presenter name @ company-->
    
        Jim is a founder and the CEO at Nirmata. Jim has been building large-scale distributed software systems for over two decades. Jim launched his career developing C++ software at Motorola for cellular network infrastructure, where his team launched the world's first CDMA network. Since then Jim has held several developer, architect, and leadership roles at companies like Bell Labs, Cisco, Trapeze Networks, and Pano Logic. In 2013 Jim founded Nirmata, a startup focused on solving enterprise DevOps pain points, by providing multi-cloud management of cloud-native workloads.
        
        - **Managing Kubernetes workloads and clusters with Kyverno**<!--presentation title-->

            Handling workloads and clusters in Kubernetes can be very tricky and challenging. That is why Kyverno offers a solution to these configuration channels via policies and shares. Kyverno, a CNCF project, is a popular policy engine designed for Kubernetes. It provides an easy way to validate settings, generates defaults and mutates resources, using policies. In addition, Kyverno can easily check your existing cluster configurations against a set of customizable rules, and help you move towards enforcing best practices for security, isolation, and resiliency across clusters. This allows DevOps teams to use familiar tools such as kubectl, git, and kustomize to manage policies. In this session, Jim will provide an overview of Kyverno and walk through some real-world examples of using policies. He will highlight how you can Write and generate policies and in turn aid your team’s collaboration

- **Hosts:**
    - @alex.b
    - @phenixblue


## This Month in Kubernetes

- v1.24 Release Cycle <!-- Link to latest release for the current K8s release cycle -->
    - [v1.24.0-alpha.1](https://github.com/kubernetes/kubernetes/releases/tag/v1.24.0-alpha.1) has been released
    - Next Deadline: <!-- Date and general description for the next release cycle deadline -->
        - [1.24 Production Readiness Review: 01/27/22](https://groups.google.com/a/kubernetes.io/g/dev/c/OjepOATqwD4)
- Fix Releases <!-- List of latest fix releases for supported/maintained Kubernetes version -->
    - v1.23.2
    - v1.22.6
    - v1.21.9
    - v1.20.15 - LAST UPDATE
- Promotions <!-- List of any interesting feature/API promotions -->
    - NA
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - [kubeadm removed Dockershim support](https://github.com/kubernetes/kubernetes/pull/107317)
- CVE's <!-- List of any Kubernetes related CVE's -->
    - NA
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - [Reserve Service IP Ranges](https://github.com/kubernetes/enhancements/pull/3071)
        - [KEP](https://github.com/kubernetes/enhancements/issues/3070)
- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - [dev@kubernetes.io is the new kubernetes-dev@googlegroups](https://groups.google.com/a/kubernetes.io/g/dev/)
    - [Kubernetes - The Documentary (part 1)](https://www.youtube.com/watch?v=BE77h7dmoQU)
    - [New API for job queueing proposed](http://bit.ly/kueue-apis)
    - [Strip unwanted metadata fields from "kubectl --dry-run"](https://github.com/kubernetes/kubernetes/pull/107088)
    - [Octo CLI - Make Databases look like Web API's](https://github.com/octoproject/octo-cli)
    - [Securing Admission Controllers](https://kubernetes.io/blog/2022/01/19/secure-your-admission-controllers-and-webhooks/)
        - [Threat model for Admission Controllers](https://github.com/kubernetes/sig-security/tree/main/sig-security-docs/papers/admission-control)
    - [Detecting Container Drift at Runtime](https://kubernetes.io/blog/2021/12/21/admission-controllers-for-container-drift/)


## Meetup Links


## Meetup Slides


## Meetup Recordings

- [Youtube](https://youtu.be/BL9BAaGmOs8)

## Meetup Notes


### Who's Hiring 
- Roy Duvall - CTO at Calendly - We have an open SRE role that is 100% remote on an outstanding GCP/GKE based platform team. Check out the job description, https://careers.calendly.com/jobs/job/126-site-reliability-engineer, or reach out to r.duvall@calendly.com

- Currently looking for Senior Azure, AKS, terraform and kubernetes engg. with preferably .NET workloads (but open for experience with other workloads as well). If interested, please reach out on vjavle@hotmail.com. Completely remote role. Org name would be invoicecloud.com

- Red Hat is hiring pre-sales technical "Solution Architects"  This is an Atlanta area position. OpenShift Kubernetes runs on any cloud so all of your cloud, k8s, and app-dev experience is valued. The contact is msolberg@redhat.com   - jbarlow@redhat.com

###### tags: `meetup` `january` `2022` `kyverno` `policy-as-code` `admission controller` `tekton` `chains` `supply chain` `security`<!--Add additional tags for `year`, `month` and anything else pertinent-->