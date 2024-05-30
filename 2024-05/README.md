# Kubernetes Atlanta Meetup: May 2024<!--Month Year-->

- **Date:** 05.30.2024<!--date as MM.DD.YYYY-->
- **Location:**
    - Ga Tech ATDC
- **Speakers:**
     - **Tyler Gillson, Principal Software Engineer @ Spectro Cloud** <!--presenter name @ company-->
    
        Tyler is a programmer and a problem solver, with 6 years of experience designing, discussing, and building complex systems in a multitude of languages. His technical interests lie in cloud computing, automation, declarative infrastructure and application configuration for distributed systems. When he isn’t building things, Tyler can often be found playing with rocks: scrambling, climbing, and mountain biking.
        
        - **Two-node HA kubernetes for edge computing cost savings**<!--presentation title-->

            When you’re scaling production K8s workloads to hundreds or thousands of edge sites, you know you need HA — but with conventional 3-node architectures, the hardware costs can be terrifying. This talk presents a new architecture for 2-node HA that gives you the resilience you need, and 33% cost savings.

            We'll cover:

            - The challenge: real end user examples from hospitals, coffee shops and factory floors where 3-node HA proved problematic
            - The problem space: existing alternatives such as external data stores and ‘witnesses’ — and why they fall short
            - The blueprint: a new OSS-based 2-node HA design built on kairos, k3s, kine, and postgres
            - Tradeoffs: when and where 2-node makes sense and how it stacks up against traditional 3-node k8s.
    - **Lachlan Heywood, wasmCloud Contributor & Software Engineering Lead @ Cosmonic**

        - **Resilient Workloads in Kubernetes: From Cloud to Edge with WebAssembly**

            Lachlan will give an overview of WebAssembly outside the browser, the wasmCloud CNCF project and how it can assist building and deploying resilient workloads in Kubernetes across regions, clouds and to the edge.
            
- **Hosts:**
    - Nate Lee
    - Joe Searcy - @phenixblue

## This Month in Kubernetes

- v1.31 Release Cycle <!-- Link to latest release for the current K8s release cycle -->
    - [43 enhancements opted in for the release so far](https://bit.ly/k8s131-enhancements)
        - 20 are in alpha
        - 9 graduating to beta
        - 10 graduating to GA
    - Next Deadline: <!-- Date and general description for the next release cycle deadline -->
        - Production Readiness Freeze, June 6th, 2024
    - Fix Releases <!-- List of latest fix releases for supported/maintained Kubernetes version -->
        - v1.10.1
        - v1.29.5
        - v1.28.10
        - v1.27.14
- Promotions <!-- List of any interesting feature/API promotions -->
    - NA
- Deprecations <!-- List of any interesting feature/API deprecations -->
    - NA
- CVE's <!-- List of any Kubernetes related CVE's -->
    - NA
- KEP's of Note
    - [CBOR Serializer](https://github.com/kubernetes/enhancements/tree/master/keps/sig-api-machinery/4222-cbor-serializer)
        - https://cbor.io
- PR's of Note <!-- List of any interesting PR's to the Kubernetes project (use lwkd.io) -->
    - [kubectl logs --all-pods](https://github.com/kubernetes/kubernetes/pull/124732)
- Community News <!-- List of any interesting news from the Kubernetes community/ecosystem -->
    - [Kubebuilder v4.0.0](https://github.com/kubernetes-sigs/kubebuilder/releases/tag/v4.0.0)
    - [k8s-wait-for](https://github.com/groundnuty/k8s-wait-for)
    - [Paraglider](https://www.linuxfoundation.org/press/linux-foundation-launches-paraglider-to-reduce-complexity-for-developers-and-network-operators-within-and-across-clouds?hs_amp=true)
        - [Github Project](https://github.com/paraglider-project/paraglider)
    - [Kubernetes Cloud Provider for KIND](https://github.com/kubernetes-sigs/cloud-provider-kind)
    - [Ian Rudie added as Istio Ambient `ztunnel` Maintainer](https://github.com/istio/community/pull/1401)

## Meetup Links

## Meetup Slides

## Meetup Recordings

## Meetup Notes

- [KubeCon + CloudNativeCon (15% off)](https://events.linuxfoundation.org/kubecon-cloudnativecon-north-america/register/?utm_source=hs_email&utm_medium=email&_hsenc=p2ANqtz-9eA9XSefxXunBMBa9P1w1hApuWtuQgpAVCH0MtsVHCll6Vnf_WLgdqji6PcxCRoH94d4TX): KCNA24JOIN

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` <!--Add additional tags for `year`, `month` and anything else pertinent-->