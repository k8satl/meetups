# Kubernetes Atlanta Meetup: May 2021<!--Month Year-->

- **Date:** 05.26.2021<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **Joe Searcy @ T-Mobile**
    
        Joe Searcy leverages 16 years of experience within infrastructure and distributed systems across Telecommunications, High Frequency Trading, and various other industries in his role as a Staff Engineer on the Platform Engineering team at T-Mobile. Joe helps lead a team of Rockstars to design, build, and maintain the various components that make up the TKE (T-Mobile Kubernetes Engine) platform and foster innovation at the Uncarrier.
        
        - **Multi-Architecture Image Builds for Kubernetes Workloads**<!--presentation title-->

            We will introduce Docker's "buildx" tooling and how it can help ease the burden of building container images for multiple compute architectures (amd64, arm64, ppc64le, riscv64, etc.). We will also walk through a simple Github Actions workflow that shows how easy it can be to integrate "buildx" into your existing workflow and ease the burden of publishing multi-architecture images for you Kubernetes applications/projects.
            
    - **Joe Lupo @ T-Mobile**

        Joe Lupo is a principal engineer at T-Mobile. With 25 years of experience in IT from helpdesk and desktop support to *NIX system administration and storage engineering, he has turned his attention to Kubernetes, specifically the T-Mobile Kubernetes Engine, with a focus on helping design and implement a "platform as code" model.

        - **Project Harbor: Intro and Failover Architecture**<!--presentation title-->

            Harbor is a Cloud Native Artifact Registry. In this talk we'll provide an overview of what Project Harbor is, what problems it can solve, and why you might decide to use it versus the likes of DockerHub, Quay.io, GCR, etc. We'll also explore an example failover architecture for how Harbor can be deployed across multiple Data Centers that balances operational complexity and artifact availability.


- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- 1.21.0 released
    - [1.22 Release Cycle has begun](https://github.com/kubernetes/sig-release/tree/master/releases/release-1.22)
        - v1.22.0-alpha.2 has been released
    - Next Deadline: 
        - Exception Requests Due, June 28
        - July 8th: Code Freeze
        - August 4th: Release
    - Fix Releases
        - v1.21.1
        - v1.20.7
        - v1.19.11
        - v1.18.19
- Promotions
    - [Indexed Job to Beta](https://github.com/kubernetes/kubernetes/pull/101292)
    - [Namespace selector affinity to beta](https://github.com/kubernetes/kubernetes/pull/101496)
    - [Warning headers to GA](https://github.com/kubernetes/kubernetes/pull/100754)
- Deprecations
    - [Ingress v1beta1](https://github.com/kubernetes/kubernetes/pull/102030)
- CVE's
    - [CVE-2021-25736](https://github.com/kubernetes/kubernetes/pull/99958)
    - [CVE-2021-25737](https://github.com/kubernetes/kubernetes/issues/102106)
    - [CVE-2021-25738](https://github.com/kubernetes-client/java/issues/1698)
- PR's of Note
    - [Per field warning hooks](https://github.com/kubernetes/kubernetes/pull/101688)
    - [Feature gate to disable all in-tree cloud providers](https://github.com/kubernetes/kubernetes/pull/100136)
- Community News
    - KubeCon EU
        - [CNI Working on v2.0](https://kccnceu2021.sched.com/event/iE8W/towards-cni-v20-casey-callendrello-red-hat)
        - [How cluster autoscaler scales](https://kccnceu2021.sched.com/event/iE7n/sig-autoscaling-deep-dive-and-qa-maciek-pytel-marcin-wielgus-google)
    - [kcp: Minimal Kubenretes API](https://github.com/kcp-dev/kcp)
    - [Kubewarden: Policy Engine for Kubernetes](https://www.kubewarden.io)
    - [sigstore: A non-profit, public good software signing & transparency service](https://sigstore.dev)
        - [cosign]((http://github.com/sigstore/cosign))
## Meetup Links

- The KubeCon Europe presentations are now up as video recordings on YouTube https://www.youtube.com/channel/UCvqbFHwN-nwalWPjPUKpvTA

## Meetup Slides

- https://slides.com/phenixblue/have-your-k8s-and-eat-it-too
- https://slides.com/phenixblue/cloud-native-artifacts-roundtable

## Meetup Recordings

## Meetup Notes

- https://hackmd.io/9-xwJoofTGu1i9Xw9cVvFQ

### Who's Hiring 

- StormforgeIO is hiring a PS / Customer Success Engineer. If you like k8s, ML, and working at a company with fantastic culture...Reach out to Cody Crudgington on K8's slack @CodyC or twitter @thecrudge1
- Hiring for currently AKS (eventually multi cloud), Terraform, Hub Spoke architecture, PaloAlto is a plus, but not mandatory. Please ping me (Vasant Javle) on linkedin

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` `may` `2021` `image` `architecture` `arm` `ppc` `registry` `haror` `oci` `cri` `docker` `buildx` `roundtable` <!--Add additional tags for `year`, `month` and anything else pertinent-->