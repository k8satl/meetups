# Kubernetes Atlanta Meetup: March 2021<!--Month Year-->

- **Date:** 03.24.2021<!--date as MM.DD.YYYY-->
- **Location:**
    - [Virtual via Zoom](#)
- **Speakers:**
    - **Introduction to OpenTelemetry - Austin Parker @ Lightstep**

        You might have heard about OpenTelemetry, a CNCF project that aims to create a unified observability framework for cloud-native software. You might also wonder what any of that actually means, and what it means to you. In this talk, I'll discuss the history behind the project, its design, and what it does. You'll learn how OpenTelemetry benefits the cloud-native ecosystem, and how it can benefit you and your team. It's a big topic, so this is intended to be an overview - be sure to bring your questions!

    - **An Intro to Distributed Tracing with OpenTelemetry - Joe Searcy @ T-Mobile**

        A short introduction to distributed tracing with a focus on the OpenTelemetry project. Covering high level concepts, some common practices, and a walkthrough of instrumenting a real application.

- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- Kubernetes Release Info
    - 1.21.0-beta.1 released
    - Next Deadline: Complete feature docs, Test Freeze, March 24th
    - 1.21 Final release targeted for April 8th
        - [49 tracked enhancements](http://bit.ly/k8s121-enhancements)
    - Fix Releases (Bug fix only, no CVE's)
        - v1.20.5
        - v1.19.9
        - v1.18.17
- PR's of Note
    - [The death of Bazel](https://github.com/kubernetes/kubernetes/pull/99561)
    - [Kustomize in kubectl upgrades from v2.0.3 to v4.0.5](https://github.com/kubernetes/kubernetes/pull/98946)
    - [`darwin/arm64` support for binaries](https://github.com/kubernetes/kubernetes/pull/97743)
    - [Pod deletion cost](https://github.com/kubernetes/kubernetes/pull/99163)
    - [Default `exec` container](https://github.com/kubernetes/kubernetes/pull/97099)
    - [Service Internal Traffic Policy](https://github.com/kubernetes/kubernetes/pull/96600)
    - [LoadBalancer Service Class](https://github.com/kubernetes/kubernetes/pull/98277)
    - [Add default namespace label](https://github.com/kubernetes/kubernetes/pull/96968)
- Promotions
    - [EndpointSlice API to GA](https://github.com/kubernetes/kubernetes/pull/99662)
- Deprections
    - [Kube-DNS support removed from kubeadm](https://github.com/kubernetes/kubernetes/pull/99646)
- Community News
    - [Klustered: Kubernetes experts trying to fix clusters broken by other Kubernetes experts](https://www.youtube.com/playlist?list=PLz0t90fOInA5IyhoT96WhycPV8Km-WICj)
    - [Pinniped Authentication service for Kubernetes](https://pinniped.dev/docs/)
        - [Blog](https://pinniped.dev/posts/multiple-pinnipeds/)

## Meetup Links

## Meetup Slides

## Meetup Recordings
- [Youtube](https://youtu.be/2mMED_7XatQ)

## Meetup Notes

### Who's Hiring 
  - Spaceship is hiring! SRE and engineering roles. We're building a Continuous Delivery platform using Buildpacks and Kubernetes. Details and job openings are here:  https://www.notion.so/onspaceship/Careers-Spaceship-ce7e56262044459eab24c9d8b97ec29e

  - StormForge is looking for a Frontend Engineer: https://jobs.lever.co/stormforge/860aa644-9d91-4362-8920-da00c3dd9727

###### tags: `meetup` <!--Add additional tags for `year`, `month` and anything else pertinent-->