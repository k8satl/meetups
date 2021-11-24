# Kubernetes Atlanta Meetup: November 2021<!--Month Year-->

- **Date:** 11.17.2021<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **Scott Nichols @ Chainguard** <!--presenter name @ company-->
    
        Scott Nichols is a co-founder at Chainguard. He is a contributor to Knative, and also maintains the CloudEvents SDK for Go. In his free time, Scott is an aspiring traditional woodworker.
        
        - **Explain like I'm five: SBOMs, Container Signing, and Verification**<!--presentation title-->

            Let's take a look at the wild SBOM world through a lens that everyone can understand: your neighborhood coffee shop. We will work through an analogy for the state of the art for Supply Chain Security. We will take a look at what Container Signing is and how it works, then a demo to stitch all this together in a couple workflows that you might be able to take home.

    - **Alex Barnes @ Datadog** <!--presenter name @ company-->
    
        Alex Barnes has been hanging around the Kubernetes community for years. He is a co-organizer of the Atlanta Kubernetes meetup and an engineer on Datadog's Kubernetes platform team. In his free time, Alex is an aspiring aspiring traditional woodworker.
        
        - **Intro to Gatekeeper: OPA on Kubernetes**<!--presentation title-->

            Gatekeeper allows you to easily run OPA on Kubernetes. Let's take a look at the project and how it makes Policy as Code easy on K8s.

- **Hosts:**
    - @alex.b


## This Month in Kubernetes

- v1.23 Release Cycle <!-- Link to latest release for the current K8s release cycle -->
    - [v1.23.0-alpha.4](https://github.com/kubernetes/kubernetes/releases/tag/v1.23.0-alpha.4) has been released
    - Next Deadline: <!-- Date and general description for the next release cycle deadline -->
        - [Code freeze as of 11/16/21](https://groups.google.com/g/kubernetes-dev/c/pqdD3S7rhy0)
    - Fix Releases <!-- List of latest fix releases for supported/maintained Kubernetes version -->
        - v1.22.3
        - v1.21.6
        - v1.20.12
        - v1.19.16
- Promotions <!-- List of any interesting feature/API promotions -->
    - [ConfigurableFSGroupPolicy GA](https://github.com/kubernetes/kubernetes/pull/105885)
    - [IngressClass.Spec.Parameters.Namespace GA](https://github.com/kubernetes/kubernetes/pull/104636)
    - [DownwardAPIHugePages beta](https://github.com/kubernetes/kubernetes/pull/106271)
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - NA
- CVE's <!-- List of any Kubernetes related CVE's -->
    - NA
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - [HPA v2](https://github.com/kubernetes/kubernetes/pull/102534)

- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - [2021 Steering Committee results](https://kubernetes.io/blog/2021/11/08/steering-committee-results-2021/)
    - [GCP External HTTP LBs now based on Envoy](https://twitter.com/kniga/status/1460380151041052673)
    - [SIG-Node is collecting feedback on the removal process for Dockershim (1.24)](https://docs.google.com/forms/d/e/1FAIpQLSdx8lrDbVG71OwIWUidYIbakN4WYs7Zet5X59dnfyz5wwXoiA/viewform)
    - [CFP is open for Kubecon EU 2021 until Dec 17th](https://events.linuxfoundation.org/kubecon-cloudnativecon-europe/program/cfp/#overview)
    - [kube-lineage: CLI for visualizing K8s object relationships](https://tohjustin.github.io/posts/2021-11-01-kube-lineage/)
    - [Knative 1.0](https://knative.dev/blog/articles/knative-1.0/)


## Meetup Links


## Meetup Slides

## Meetup Recordings
- [Youtube](https://www.youtube.com/watch?v=PuTJ176djsc)

## Meetup Notes

### Who's Hiring 
- DigitalOcean is hiring a senior engineer for our app platform team: https://www.digitalocean.com/careers/position/apply/?gh_jid=3517964 I’m happy to answer questions about the team slevy@digitalocean.com.

###### tags: `meetup` `november` `2021` `sbom` `chainguard` `sigstore` `opa` `gatekeeper`<!--Add additional tags for `year`, `month` and anything else pertinent-->