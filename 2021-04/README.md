# Kubernetes Atlanta Meetup: April 2021<!--Month Year-->

- **Date:** 04.28.2021<!--date as MM.DD.YYYY-->
- **Location:**
    - Virtual via Zoom
- **Speakers:**
    - **Scott Nichols @ VMware**
    
        Scott Nichols is a platform developer working on Knative Project at VMware. Knative raises the level of abstraction and simplifies Kubernetes development, including the development of event-driven architectures. Specifically Scott works on Eventing with the focus of event production. He also maintains the CloudEvents SDK for Go. In his free time, Scott is an aspiring traditional woodworker.
        
        - **Intro to Knative**<!--presentation title-->

            We will take a look at Knative Serving and Eventing through an escalating demo that will let us tour the capabilities of Knative. Serving provides a container based scale to zero, scale real big functionality; as well as rainbow deploys, auto-TLS, domain mappings, and various knobs to control concurrency and scale traits. Eventing provides a thin abstraction on top of traditional message brokers (think Kafka or AMQP) that lets you compose your application without considering the message persistence choices in the moment.

        - **Outro to Knative, Duck Types and Loose Coupling**

            One of the techniques developed inside the Knative Project is the concept of duck typing control plane resources. This enables a loose coupling not only between Knative and third party extensions, but between the Knative components themselves. Duck typing is broadly applicable to the Kubernetes ecosystem as a way to enable this loose coupling, and we are seeing interest and adoption in projects like Cluster API, Crossplane, and many others. Let's look at some examples and then deep dive to understand how this works and how you might leverage the techniques yourself.

- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- Kubernetes Release Info
    - 1.21.0 released
    - [1.22 Release Cycle has begun](https://github.com/kubernetes/sig-release/tree/master/releases/release-1.22)
        - v1.22.0-alpha.1 has been released
    - Next Deadline: 
        - March 24th: Complete feature docs, Test Freeze
        - May 13th: Enhancements Freeze
        - July 8th: Code Freeze
        - August 4th: Release
    - Fix Releases
        - v1.20.6
        - v1.19.10
        - v1.18.18
    - [Project is moving to 3 releases per year](https://groups.google.com/g/kubernetes-dev/c/IxnWeVRIadM)
        - [KEP](https://github.com/kubernetes/enhancements/pull/2567)
        - 1.22: August 2, 2021
        - 1.23: December 14, 2021
        - 1.24: April 12, 2022
        - 1.25: August 22, 2022
        - 1.26: December 6, 2022
    - Next set of patch releases closes to cherry-picks on May 7th and is expected out May 12th
        - v1.18 has been extended for one more patch release (v1.18.19). This will be the final v1.18 release before it's rolled off of community support
- Promotions
    - [Server Side Apply to GA](https://github.com/kubernetes/kubernetes/pull/100139)
    - [NamespaceDefaultLabelName to GA](https://github.com/kubernetes/kubernetes/pull/101342)
- Community News
    - [PodSecurityPolicy, Past, Present, and Future](https://kubernetes.io/blog/2021/04/06/podsecuritypolicy-deprecation-past-present-and-future/)
    - [Karmada: Multi-Cluster/Muli-Cloud Kubernetes orchestration](https://github.com/karmada-io/karmada)
    - [Evolving Kubernetes Networking: The Gateway API](https://kubernetes.io/blog/2021/04/22/evolving-kubernetes-networking-with-the-gateway-api/)
    - [Network policy conformance for CNI Providers](https://kubernetes.io/blog/2021/04/20/defining-networkpolicy-conformance-cni-providers/)
    - [Annotating K8s for Humans](https://kubernetes.io/blog/2021/04/20/annotating-k8s-for-humans/)
    - [Indexed Jobs](https://kubernetes.io/blog/2021/04/19/introducing-indexed-jobs/)

## Meetup Links

- https://github.com/n3wscott/k8s-meetup-atlanta
- https://github.com/n3wscott/sockeye
- https://github.com/n3wscott/graph
- https://github.com/n3wscott/factor
- https://github.com/n3wscott/colorgrid
- https://github.com/falcosecurity/falco-website/pull/425

## Meetup Slides

## Meetup Recordings
- [Youtube](https://www.youtube.com/watch?v=Ceyf2QfnVqU)

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

###### tags: `meetup` `april` `2021` `knative` `eventing` `serving` `duck-typing`<!--Add additional tags for `year`, `month` and anything else pertinent-->