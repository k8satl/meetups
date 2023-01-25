# Kubernetes Atlanta Meetup: January 2023<!--Month Year-->

- **Date:** 01.25.2023<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **Rich Burroughs, Staff Developer Advocate @ Loft Labs & Carl Montanari & Senior Software Engineer @ Loft Labs** <!--presenter name @ company-->
    
        **Rich Burroughs** is a Staff Developer Advocate at Loft Labs where he's focused on improving the happiness of teams using Kubernetes. He's the creator and host of the Kube Cuddle podcast where he interviews members of the Kubernetes community. Rich was one of the founding organizers of DevOpsDays Portland, and he's helped organize other community events. Rich also has a strong interest in how working in tech impacts mental health. He has ADHD and has documented his journey on Twitter since being diagnosed, and moderated a panel on ADHD at KubeCon Detroit.

        **Carl** is a Senior Software Engineer at Loft Labs, ex-network engineer, and reasonably likable guy. He enjoys being very serious about not being serious, and most days can be found working on Loft's commercial and open source projects. Outside of work he loves hiking, and working on his kit car that will, probably, eventually be complete and running... maybe.
        
        - **Virtual Kubernetes Clusters: Tips and Tricks**<!--presentation title-->

            A lot of interest in virtual Kubernetes clusters and the open source tool vcluster has developed over the last year. vcluster allows platform teams to provide virtual Kubernetes clusters to their users. A virtual cluster appears to be a full-blown Kubernetes cluster to the users, but it runs within a namespace of the host cluster. This allows users to have admin access to the cluster, use multiple namespaces in it, and manage global objects like CRDs.

            During the last year many new features have been added to vcluster, and we’ve seen it used for use cases that we hadn’t even imagined. In this talk we’ll provide some tips and tricks to help teams get more from their virtual clusters, and a few weird things you can do with them.
            
            Some things we’ll cover: How to share resources like ingresses from the host cluster, using vcluster’s isolated mode to automatically add network policies and Pod Security Standards to your virtual clusters, pausing and resuming virtual clusters, and monitoring and backing up virtual clusters. We’ll also cover some fun examples like using vcluster for shadow IT (users don’t need to have elevated privileges in the host cluster to start a virtual cluster) and running a virtual cluster inside of a virtual cluster.
    - **Sean Shen, Senior Software Engineer @ Twilio & Ross Edman, Principal Software Engineer @ Twilio** <!--presenter name @ company-->
    
        **Sean** is a technologist at Twilio working to build a shared Kubernetes Platform. He's an avid gamer & meme sommelier

        **Ross** is also a technologist at Twilio working on the shared Kubernetes Platform and wider ecosystems. He holds the title of Heavy Metal Carpenter in his spare time
        
        - **Rego My Eggo: In Living Policy**<!--presentation title-->

            This talk will cover using the Rego policy language and various other tooling to create distributed Policy for use with Kubernetes in both CI and in-cluster.
- **Hosts:**
    - @alex.b
    - @phenixblue 
- **Sponsors**
    - [Calendly](https://calendly.com)

## This Month in Kubernetes

- v1.27 Release Cycle <!-- Link to latest release for the current K8s release cycle -->
    - 
    - Next Deadline: <!-- Date and general description for the next release cycle deadline -->
        - Begin [PRR](https://github.com/kubernetes/enhancements/tree/master/keps/sig-architecture/1194-prod-readiness) reviews, February 2nd
    - Fix Releases (Updates to Golang to fix [known security holes](https://github.com/advisories/GHSA-xrjj-mj9h-534m))<!-- List of latest fix releases for supported/maintained Kubernetes version -->
        - v1.26.1
        - v1.25.6
        - v1.24.10
        - v1.23.16
- Promotions <!-- List of any interesting feature/API promotions -->
    - NA
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - [Removing PSP code](https://github.com/kubernetes/kubernetes/pull/113467)
    - Leader Elections using ConfigMaps or Secrets will [be going away at some point in the future](https://github.com/kubernetes/kubernetes/pull/114055) and everyone should be using Leases instead
- CVE's <!-- List of any Kubernetes related CVE's -->
    - NA
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - [Autoscaling v2 API](https://github.com/kubernetes/kubernetes/pull/114358) is now preffered, and v1 will be moving towards deprecation
- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - [Troubleshoot](https://troubleshoot.sh/) - A kubectl plugin for collecting k8s cluster diagnostic info
    - [API Server Adventure Series: Part I - The Storage Interface](https://danielmangum.com/posts/k8s-asa-the-storage-interface/)
    - [A visual guide to K8s Pod Probes](https://speakerdeck.com/thockin/kubernetes-pod-probes)
    - [K8s Failure Stories](https://k8s.af)
    - [Clusterpedia - The Encyclopedia of Kubernetes clusters](https://github.com/clusterpedia-io/clusterpedia)

## Meetup Links

## Meetup Slides

## Meetup Recordings

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` <!--Add additional tags for `year`, `month` and anything else pertinent-->