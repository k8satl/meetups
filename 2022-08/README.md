# Kubernetes Atlanta Meetup: August 2022<!--Month Year-->

- **Date:** 08.31.2022<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **David Espejo, Community Manager @ VMware** <!--presenter name @ company-->
    
        David has spent the last 13 years collaborating with Telcos and financial institutions on building IaaS offerings and enhanced automation processes. With a Kubernetes and distributed systems background, recently joined VMware as Open Source Community Manager to support several OSS projects in their engagement with the community of users, contributors and maintainers.
        
        - **From Orchestration to Choreography: how to modernize and streamline your CI/CD**<!--presentation title-->

            This talk will discuss the benefits of declarative choreography and show how teams can move from orchestrating pipelines to choreographing secure supply chains using the open source tool, Cartographer.
    - **Scott Adams, Principal Engineer @ T-Mobile** <!--presenter name @ company-->
    
        Scott Adams is a Principal Engineer on the Conducktor team at T-Mobile, which provides a standardized Kubernetes platform for application teams to deploy their containerized workloads to the public cloud.
        
        - **QLKube: GraphQL for the Kubernetes API**<!--presentation title-->

            QLKube is a dynamic GraphQL proxy for the Kubernetes API
- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- Post v1.25 Release Cycle <!-- Link to latest release for the current K8s release cycle -->
    - We are currently in the “clear out the queues” phase between releases
    - Next Deadline: K8s v1.26 Release Cycle Begins, Sept. 5th<!-- Date and general description for the next release cycle deadline -->
        - [Apply to be a Release Team shadow](https://github.com/kubernetes/sig-release/blob/master/releases/release-1.26/release-team.md)
    - Fix Releases <!-- List of latest fix releases for supported/maintained Kubernetes version -->
        - v1.25.0
        - v1.24.4
        - v1.23.13
- Promotions <!-- List of any interesting feature/API promotions -->
    - [CSIInlineVolume is GA](https://github.com/kubernetes/kubernetes/pull/111258)
    - [CustomResourceValidationExpressions to beta](https://github.com/kubernetes/kubernetes/pull/111524)
    - [EphemeralContainers to GA](https://github.com/kubernetes/kubernetes/pull/111402)
    - [podOS filed to GA]()
        - [KEP](https://github.com/kubernetes/enhancements/blob/master/keps/sig-windows/2802-identify-windows-pods-apiserver-admission/README.md)
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - [Deprecated beta node labels (e.g. failure-domain.beta.kubernetes.io/zone) will result in a warning in more places](https://github.com/kubernetes/kubernetes/pull/108554)
    - [The /logs endpoint for kube-apiserver is no longer enabled by default; set --enable-logs-handler to re-enable](https://groups.google.com/a/kubernetes.io/g/dev/c/OkSc6KLmD0Q)
        - [Security Concerns](https://github.com/kubernetes/kubernetes/issues/77182)
- CVE's <!-- List of any Kubernetes related CVE's -->
    - [enhancements#3204: KEP-3203: Add Auto-refreshing Official CVE feed](https://github.com/kubernetes/enhancements/pull/3204)
        - [KEP](https://github.com/kubernetes/enhancements/tree/master/keps/sig-security/3203-auto-refreshing-official-cve-feed)
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - [#111090: Add support for user namespaces phase 1 (KEP 127)](https://github.com/kubernetes/kubernetes/pull/111090)
    - [Minimal Container Checkpointing Support](https://github.com/kubernetes/kubernetes/pull/104907)
        - [KEP](https://www.meetup.com/kubernetes-atlanta-meetup/events/287845059/)
    - [Introduce kuberc](https://github.com/kubernetes/enhancements/pull/3392)
    - [PodSecurity to GA](https://github.com/kubernetes/kubernetes/pull/110459)
    - [#109938: Move from k8s.gcr.io to registry.k8s.io](https://github.com/kubernetes/kubernetes/pull/109938)
- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - [Kubectl Tips](https://www.learncloudnative.com/blog/2022-05-10-kubectl-tips)
    - [SansShell: A non-interactive daemon for host management](https://github.com/Snowflake-Labs/sansshell)
    - [Trow: Container Registry and Image Management for Kubernetes Clusters](https://github.com/ContainerSolutions/trow)
    - [kube-fledged: Operator for caching container Images directly on nodes](https://github.com/senthilrch/kube-fledged)
    - [A web-based simulator for the Kubernetes scheduler](https://github.com/kubernetes-sigs/kube-scheduler-simulator)
    - [Scaling Kubernetes to Thousands of CRDs](https://blog.upbound.io/scaling-kubernetes-to-thousands-of-crds/)
    - [OpenTelemetry Operator](https://github.com/open-telemetry/opentelemetry-operator#opentelemetry-operator-for-kubernetes)

## Meetup Links

## Meetup Slides

## Meetup Recordings
- [Youtube](https://youtu.be/MrI-IIVqx7g)

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` `august` `2022` `cartographer` `choreography` `graphql` `qlkube` <!--Add additional tags for `year`, `month` and anything else pertinent-->