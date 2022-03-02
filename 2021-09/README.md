# Kubernetes Atlanta Meetup: September 2021<!--Month Year-->

- **Date:** 09.29.2021<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **Michael Solberg @ Red Hat** <!--presenter name @ company-->
    
        Michael has been an architect at Red Hat since 2008, where he has helped many of the South's largest organizations adopt Open Source software, including Linux, OpenStack, and Kubernetes. He currently leads the Southeast Regional Technology Office at Red Hat where he works with Red Hat's Emerging Technology portfolio.
        
        - **Data Science workflows on Kubernetes**<!--presentation title-->

            Once upon a time in the Dark Ages of Artificial Intelligence, Scientists relied on massive, customized compute farms with specialized software to generate insights from the data that they gathered from the world around them. With the adoption of nimble Open Source software and Cloud Computing, even a total beginner can now crunch numbers, generate models, and analyze massive data sets for fun or profit. Projects like Kubeflow and OpenDataHub have made these tools easily available on Kubernetes and now we can apply the same architectures to Data Science workloads that we have been using for massively scalable microservices. In our talk, we'll walk through a little background on how Kubernetes fits into the traditional Data Science workflow and then we'll demonstrate how to use Jupyterhub, Tensorflow, Ceph, Strimzi, and Grafana to build out a pipeline for real-time image analysis and labeling.
- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- v1.23 Release Cycle <!-- Link to latest release for the current K8s release cycle -->
    - [v1.23.0-alpha.3](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.23.md) has been released
    - Next Deadline: <!-- Date and general description for the next release cycle deadline -->
        - Cherry-picks due Oct 15
        - Last call for Exceptions, Nov 1
    - Fix Releases <!-- List of latest fix releases for supported/maintained Kubernetes version -->
        - v1.22.2
        - v1.21.5
        - v1.20.11
        - v1.19.15
- Promotions <!-- List of any interesting feature/API promotions -->
    - [IPv6 DualStack to GA](https://github.com/kubernetes/kubernetes/pull/104691) in v1.23
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - NA
- CVE's <!-- List of any Kubernetes related CVE's -->
    - [CVE-2020-8561 - Allows webhook owners to hijack sessions](https://github.com/kubernetes/kubernetes/issues/104720)
    - [CVE-2021-25741- User bypass of volume restrictions in VolumeSubpath](https://github.com/kubernetes/kubernetes/issues/104980)
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - [UID Impersonation for client-go](https://github.com/kubernetes/kubernetes/pull/104483)
- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - [No formally organized Contributor Summit at KubeCon NA 2021](https://groups.google.com/g/kubernetes-dev/c/e7xIp2Mz398)
        - Still having a social event on monday
        - Online Contributor Celebration in December
    - [KEP-2876 - CRD Validation Expression Language](https://github.com/kubernetes/enhancements/blob/master/keps/sig-api-machinery/2876-crd-validation-expression-language/README.md)
    - [Kubernetes API Server Tracing](https://kubernetes.io/blog/2021/09/03/api-server-tracing/)
    - [Cluster API Provider - Nested](https://github.com/kubernetes-sigs/cluster-api-provider-nested/tree/main/docs)
    - [Kubescape - K8s Security Conformance tooling](https://github.com/armosec/kubescape)
    - [SuperEdge - Edge-Native Container Management](https://github.com/superedge/superedge)
        - https://superedge.io
    - [Karmada - Open, Multi-Cloud, Multi-Cluster Kubernetes Orchestration](https://github.com/karmada-io/karmada)
    - [Akri - A Kubernetes resource interface for the Edge](https://github.com/deislabs/akri)
    - [Inclavare - Confidential Container Runtime Tooling](https://github.com/alibaba/inclavare-containers)
        * https://occlum.io
        * https://software.intel.com/content/www/us/en/develop/topics/software-guard-extensions.html
        * https://graphene.readthedocs.io/en/latest/oldwiki/Introduction-to-Graphene-SGX.html
    * [Cluster API ClusterClass & Managed Topologies](https://github.com/kubernetes-sigs/cluster-api/blob/master/docs/proposals/20210526-cluster-class-and-managed-topologies.md)
    * [KinK - KinD in Kubernetes](https://github.com/Trendyol/kink)

## Meetup Links

- [Machine Learning Workshop Guides](https://github.com/Red-Hat-SE-RTO/machine-learning-workshop-guides)

## Meetup Slides

## Meetup Recordings
- [Youtube](https://www.youtube.com/watch?v=8p7MSTPa0gw)

## Meetup Notes

### Who's Hiring 

- Salesloft:
    - SRE: https://salesloft.com/careers/?gh_jid=3246302

- Redhat:
    - Cloud Specialist Solutions Architect: https://us-redhat.icims.com/jobs/89335/cloud-specialist-solutions-architect/job?hub=7
    - Senior Cloud Specialist Solutions Architect: https://us-redhat.icims.com/jobs/89094/senior-cloud-specialist-solutions-architect/job?hub=7&mobile=false&width=1140&height=500&bga=true&needsRedirect=false&jan1offset=-300&jun1offset=-240

###### tags: `meetup` `september` `2021` `data science` `jupyter` `tensorflow`<!--Add additional tags for `year`, `month` and anything else pertinent-->
