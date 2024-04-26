# Kubernetes Atlanta Meetup: April 2024

- **Date:** <!--date as MM.DD.YYYY-->
- **Location:**
    - Ga Tech ATDC
- **Speakers:**
    - **Jenn Allen, Product Manager @ Dagger.io** <!--presenter name @ company-->
    
        Jenn leads technical product management at Dagger, working to reduce the toil software teams face when making apps and services.
        
        - **An Introduction to Dagger. A brief overview of Dagger, how to build modules, and how to use Dagger with K8s**<!--presentation title-->

            Dagger is a programmable open source CI/CD engine that runs your pipelines in containers — pre-push on your local machine and/or post-push in CI. We'll cover what Dagger is, walk through a few simple examples, and look at how to use modules from the Daggerverse to build and publish a containerized app.
            
    - **Matthew LeRay - Co-founder & CTO @ Speedscale** <!--presenter name @ company-->
    
        Jenn leads technical product management at Dagger, working to reduce the toil software teams face when making apps and services.
        
        - **Leveraging the Power of User Traffic in Dev: Remote Capture and Playback in K8s**<!--presentation title-->

            Observing production workloads with enough detail to find real problems is difficult, but it's getting easier with the rise of eBPF and Kubernetes traffic tools like KubeShark and Speedscale. As the technology becomes better understood, tools like Cilium and Pixie are increasingly appearing in production clusters. But have you ever considered using observed traffic to help with unit tests, Continuous Integration and load testing? This talk will present some examples of how to use collected traffic for a variety of software quality use cases. You'll also get some ideas on using those calls in your Continuous Integration pipeline to sanity check builds before they are deployed. Included in that discussion will be handling some common issues like timestamp skew and authentication.
            
- **Hosts:**
    - Nate Lee
    - Joe Searcy - @phenixblue

## This Month in Kubernetes

- v1.31 Release Cycle <!-- Link to latest release for the current K8s release cycle -->
    - In between releases right now
    - Next Deadline: Cycle begins April 2024'ish<!-- Date and general description for the next release cycle deadline -->
        - 
    - Fix Releases <!-- List of latest fix releases for supported/maintained Kubernetes version -->
        - v1.30.0
        - v1.29.4
        - v1.28.9
        - v1.27.13
- Promotions <!-- List of any interesting feature/API promotions -->
    - [CRD Validation with CEL moves to stable](https://github.com/kubernetes/enhancements/tree/master/keps/sig-api-machinery/2876-crd-validation-expression-language)
    - [Container Resource based Autoscaling](https://github.com/kubernetes/enhancements/blob/master/keps/sig-autoscaling/1610-container-resource-autoscaling/README.md)
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - NA
- CVE's <!-- List of any Kubernetes related CVE's -->
    - NA
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - NA
- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - [OpenUnison - SSO for K8s](https://openunison.github.io)
    - [kubectl-sidecar](https://github.com/thockin/kubectl-sidecar)
    - [Rancher k3k](https://github.com/rancher/k3k)
    - [Azure Fleet](https://github.com/Azure/fleet/)

## Meetup Links

- Dagger Community Discord: https://discord.gg/dagger-io
- Demo Source: https://github.com/d3rp3tt3/dagger-demos/tree/main/dagger-tekton
- 

## Meetup Slides

## Meetup Recordings

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->
- Speedscale: for a Front End/Full Stack Engineer. The job is Hybrid located in Atlanta and you can reach me at matt@speedscale.com. You can also apply online here: [https://speedscale.com/careers/position/front-end-engineer/](https://speedscale.com/careers/position/front-end-engineer/)
- Calendly: We’re hiring SREs and Platform engineers at the senior and staff level. Can [find me on LinkedIn](https://www.linkedin.com/in/alexrbarnes/) if you’re interested!

###### tags: `meetup` `2024` `april` `atdc` `dagger` `kubeshark`<!--Add additional tags for `year`, `month` and anything else pertinent-->