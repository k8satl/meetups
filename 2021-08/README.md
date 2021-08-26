# Kubernetes Atlanta Meetup: August 2021<!--Month Year-->

- **Date:** 08.25.2021<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**

    - **Moshe Shitrit @ Sysdig** <!--presenter name @ company-->
    
        Moshe is a Senior Infrastructure Engineer at Sysdig, where he is responsible for building and maintaining a set of tools used for all things automation. Moshe has played various roles in the IT area for over 14 years. He has been a Kubernetes enthusiast for the past 6 years, and has been a contributor to the project for over year.
        
        - **A Simple GitOps Workflow in Action - GitHub Actions, Kustomize, ArgoCD and Bitnami SealedSecrets**<!--presentation title-->

            GitOps is becoming more and more popular due to the desire to automate as much as possible. In this talk, we’ll go through one way of achieving the goal of automated CI/CD using a combination of free / open source tools. We’ll have a simple REST API running in a k8s cluster, having its codebase stored in GitHub. We’ll look at the GitHub actions workflow that we use to build our code upon our desired triggers, and keep diving until we see our new code running in our k8s cluster.
            
    - **Andy Holtzmann @ Equinix** <!--presenter name @ company-->
    
        Andy is an engineer at Packet (an Equinix company). During his time working with Kubernetes, he helped Sendgrid do their initial k8s migration and helping implement the start of their initial cluster api 2.0 project. He joined Equinix Metal to help them consolidate from 3 other platforms to Kubernetes as one platform to rule them all.
        
        - **Lessons Learned from Equinix's K8s migration**<!--presentation title-->

            Joining a new company can be full of surprises and it’s funny how many meanings “we run in a containerized environment” can take on. While the primary delivery mechanism for application code might be an OCI container the supporting deployment, secret management, operational burden, and organization’s cognition load can differ wildly. Here are some of the lessons learned in consolidating for 4 platforms to 1, and the far reaching impacts it had on an entire engineering org.

- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- v1.23 Release Cycle <!-- Link to latest release for the current K8s release cycle -->
    - Release cycle began this week
    - Next Deadline: <!-- Date and general description for the next release cycle deadline -->
        - [Call for enhancements](https://groups.google.com/g/kubernetes-dev/c/SY4E4q-r_CA)
        - [Production Readiness Review (PRR) approval required for all KEP's](https://groups.google.com/g/kubernetes-sig-architecture/c/a6_y81N49aQ)
        - Enhancement Freeze - September 9th, 2021
    - Kubernetes 1.22.0 released on August 4, 2021 🎉🎉🎉
    - Fix Releases <!-- List of latest fix releases for supported/maintained Kubernetes version -->
        - [v1.22.1](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.22.md)
        - [v1.21.4](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.21.md)
        - [v1.20.10](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.20.md)
- Promotions <!-- List of any interesting feature/API promotions -->
    - NA
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - NA
- CVE's <!-- List of any Kubernetes related CVE's -->
    - NA
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - [ExtractItems for unstructured apply configurations](https://github.com/kubernetes/kubernetes/pull/103564)
- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - [Git powered K8s Controller](https://github.com/ibuildthecloud/gitbacked-controller)
    - [OCI Base Image Annotations](https://github.com/ImJasonH/ImJasonH/tree/main/articles/oci-base-image-annotations)
    - [Kubernetes Benchmark Operator](https://github.com/ImJasonH/ImJasonH/tree/main/articles/oci-base-image-annotations)
    - [Sysdig Overview of what's new in K8s 1.22](https://sysdig.com/blog/kubernetes-1-22-whats-new/)

## Meetup Links

- [Moshe's Demo - Basic Go API](https://github.com/moshitrit/basic-go-api)

## Meetup Slides

## Meetup Recordings

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` <!--Add additional tags for `year`, `month` and anything else pertinent-->