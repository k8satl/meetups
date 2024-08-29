# Kubernetes Atlanta Meetup: August 2024<!--Month Year-->

- **Date:** 08.29.2024<!--date as MM.DD.YYYY-->
- **Location:**
    - Ga Tech ATDC
- **Speakers:**

    - **John Platt, CTO @ StormForge** <!--presenter name @ company-->
    
        John has a PHD in Applied Maths and has spent most of his career building Machine Learning powered products. Throughout his career he constantly found himself using machine learning to solve infrastructure related problems that he didn’t want to toil with. The desire to automate away mundane tasks combined with a desire to solve the hard problems with maths is what led him to his current role as CTO of StormForge, which focuses on Kubernetes resource optimization.
        
        - **Kubernetes Autoscaling: Beyond One-Size-Fits-All**<!--presentation title-->

            There’s no one-size-fits-all approach to Kubernetes autoscaling. Fitting the right pieces together requires a deep understanding of the various autoscaling dimensions and the open-source projects that can plug in to meet specific use cases.This session will explore the three key dimensions: cluster, horizontal, and vertical. We’ll start with the tools built into Kubernetes before moving onto the more advanced open-source projects—Karpenter and KEDA, which enhance flexibility and efficiency for each.Attendees will learn:

        - Strategies for cluster, horizontal and vertical autoscaling, their challenges, and solutions that improve on or replace them
        - How to assess workload requirements to choose the right mix of autoscaling tailored to specific app needs
        - Best practices to optimize deployments for peak performance and cost-efficiency for dynamic workloads

    - **Eldon Stegall, Sr. SRE @ Bisect.dev** <!--presenter name @ company-->

        Eldon is a longtime K8s ATL Community Member and a repeat presenter

        - **Easy Workload Identity for CD: Smooth Authentication with Gitlab and K3s**<!--presentation title-->

            As we deploy more code more frequently, keeping the deploy process smooth is vital. Here we discuss one strategy for connecting the dots without a lot of hassle.

- **Hosts:**
    - Nate Lee
    - Joe Searcy - @phenixblue

## This Month in Kubernetes

- [v1.31 Release Cycle](https://github.com/kubernetes/kubernetes/releases/tag/v1.31.0) <!-- Link to latest release for the current K8s release cycle -->
    - [K8s v1.31 Release Blog](https://kubernetes.io/blog/2024/08/13/kubernetes-v1-31-release/)
    - Next Deadline: 1.32 cycle begins, September 9<!-- Date and general description for the next release cycle deadline -->
        - [Shadow application for 1.32 release team](https://docs.google.com/forms/d/e/1FAIpQLSdb60FW9aYIepSdXIWexQIKNJ8m3JSqHZ6kkH3Q_I7XP9OVYA/viewform)
    - Fix Releases <!-- List of latest fix releases for supported/maintained Kubernetes version -->
        - v1.31.0
        - v1.30.4
        - v1.29.8
        - v1.28.13
- Promotions <!-- List of any interesting feature/API promotions -->
    - [Custom profiling in `kubectl debug` Graduates to Beta](https://kubernetes.io/blog/2024/08/22/kubernetes-1-31-custom-profiling-kubectl-debug/)
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - NA
- CVE's <!-- List of any Kubernetes related CVE's -->
    - NA
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - [Add an nftables based backend for kube-proxy](https://github.com/kubernetes/enhancements/blob/master/keps/sig-network/3866-nftables-proxy/README.md)
    - [Support for OCI Image Volumes](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/4639-oci-volume-source)
        - https://kubernetes.io/blog/2024/08/16/kubernetes-1-31-image-volume-source/
- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - [Nacos - Dynamic `Na`ming and `Co`nfiguration `S`ervice](https://github.com/alibaba/nacos)

## Meetup Links

## Meetup Slides

## Meetup Recordings

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` `2024` `august` `autoscaling` `continuous delivery` `cd` `k3s` `gitlab` `authentication` `workload identity` <!--Add additional tags for `year`, `month` and anything else pertinent-->