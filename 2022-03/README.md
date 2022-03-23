# Kubernetes Atlanta Meetup: March 2022<!--Month Year-->

- **Date:** 03.23.2022<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **Leigh Capili, Staff Developer Advocate @ VMware** <!--presenter name @ company-->
    
        Leigh is an empathetic speaker and developer with niches in           cloud-native systems and security. He has a background in building software to manage infrastructure. 
    
        Leigh contributes to Kubernetes and Flux and is frequently working on his next software demo. He also co-maintains Ignite, the microVM manager with Docker UX. (https://ignite.rtfd.io/)
    
        Leigh works with the VMware Tanzu Advocacy team and previously built Developer Experience and Platform with Weaveworks, Beatport, AT&T, and DIRECTV.
    
        Leigh enjoys snowboarding with his wife and has a 60lb dog named Pepsi.
        
        - **Securing GitOps Debug Access with Pinniped, Dex, and GitHub**<!--presentation title-->

            Git alone provides a pretty mediocre inner-loop for deployment to a cluster -- Git is powerful for collaboration, but it’s not a debugger.

            However, git platforms can still add value for debugging!
            Roles and group membership are usually weaved into the habits teams build around git repos. This can be combined within the authentication and authorization systems used in a multi-cluster Kubernetes platform!

            In this live demo, Leigh will show how the incredibly flexible, open-source combo of Flux (fluxcd.io) , Pinniped (pinniped.dev/), and Dex (dexidp.io/) can empower a team to leave a traceable solution during a production incident. Let’s explore effective team debugging habits with Kubernetes and git :)
            
    - **Joe Searcy, Staff Engineer @ T-Mobile** <!--presenter name @ company-->

        Joe Searcy leverages 18 years of experience within infrastructure and distributed systems across Telecommunications, High Frequency Trading, and various other industries in his role as a Staff Engineer on the Platform Engineering team at T-Mobile. Joe helps lead a team of Rockstars to design, build, and maintain the various components that make up the TKE (T-Mobile Kubernetes Engine) ecosystem and foster innovation at the Un-Carrier.

        - **A Primer on Kubernetes Load Testing & Benchmarking**<!--presentation title-->

            Ok, you've got your Kubernetes clusters...they're running ok...but sometimes they just start to feel slow, runtimes take longer, packets and requests get dropped, and you're not sure if it happened after your last CNI upgrade or that CVE patch a few kernels ago. Being able to simulate load, at scale, on-demand, and track changes over time is important. We'll discuss the differences between load testing and benchmarking, when and why you would perform one over the other, and some of the common tools you can use for each.

- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- v1.24 Release Cycle <!-- Link to latest release for the current K8s release cycle -->
    - Kubernetes v1.24.0-alpha.4
    - Next Deadline: <!-- Date and general description for the next release cycle deadline -->
        - Code Freeze, March 30th
    - Fix Releases <!-- List of latest fix releases for supported/maintained Kubernetes version -->
        - v1.23.5
        - v1.22.8
        - v1.21.11
- Promotions <!-- List of any interesting feature/API promotions -->
    - NA
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - NA
- CVE's <!-- List of any Kubernetes related CVE's -->
    - NA
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - [No auto-generation of secret-based service account token](https://github.com/kubernetes/kubernetes/pull/108309)
    - [Disabling beta API's by default](https://github.com/kubernetes/enhancements/pull/3137)
        - [Issue](https://github.com/kubernetes/enhancements/issues/3136)
        - [KEP](https://github.com/kubernetes/enhancements/pull/3137)
        - [Add CEL runtime cost into CR validation](https://github.com/kubernetes/kubernetes/pull/108482)
- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - K8s Reliability Discussions
        - [KEP](https://github.com/kubernetes/enhancements/pull/3139)
        - [Dev Thread](https://groups.google.com/a/kubernetes.io/g/dev/c/ai8SetaxYuk)
    - Dockershim Removal
        - [Committment and Next Steps](https://kubernetes.io/blog/2022/01/07/kubernetes-is-moving-on-from-dockershim/)
        - [Migrating from Dockershim](https://kubernetes.io/docs/tasks/administer-cluster/migrating-from-dockershim/)
        - [FAQ](https://kubernetes.io/blog/2022/02/17/dockershim-faq/)
    - [Spotlight on SIG Multicluster](https://kubernetes.io/blog/2022/02/17/dockershim-faq/)
    - [Scripting with Go](https://github.com/bitfield/script)
    - [Updates to Kubernetes Hardening Guide](https://www.cisa.gov/uscert/ncas/current-activity/2022/03/15/updated-kubernetes-hardening-guide?utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-_cRPRGtJvhFFUoykn-L39N8IiwIraw9ogRBZcGVSPUmOn3qvdBRQvPSXRvm61OPFn2Ukkn)
    - [Static code analysis for infra-as-code and k8s resources](https://github.com/bridgecrewio/checkov)
    - [ktop: Top for K8s](https://github.com/vladimirvivien/ktop)
    - [Sonobuoy skeleton plugin](https://github.com/vmware-tanzu/sonobuoy-plugins/tree/main/examples/e2e-skeleton)

## Meetup Links

## Meetup Slides

## Meetup Recordings

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` `march` `2022` `gitops` `flux` `pinniped` `performance` `benchmarking` `locust` `dbench` `netperf` `sonobuoy` `loadtest`<!--Add additional tags for `year`, `month` and anything else pertinent-->