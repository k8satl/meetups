# Kubernetes Atlanta Meetup: July 2020<!--Month Year-->

- **Date: 07.29.2020**<!--date as MM.DD.YYYY-->
- **Location:**
    - [Virtual via Zoom](https://www.meetup.com/Kubernetes-Atlanta-Meetup/events/271771682/)
      - NOTE: You must login to meetup to view the Zoom link
- **Speakers:**
    - 10 Minutes with Typhoon Lightning Talk
        - Eldon Stegall
    - How Cloud-Native Broke Dev (and Tilt fixes it)<!--presentation title-->
        - Dan Bentley (Tilt)<!--speaker name/company-->
- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- **Kubernetes Release Info**
    - We are still in [extended code freeze](https://groups.google.com/g/kubernetes-dev/c/4V5-ORCwoUM) due to ongoing [stability issues](https://github.com/kubernetes/kubernetes/issues?q=is%3Aissue+is%3Aopen+label%3Apriority%2Fcritical-urgent) with 1.19
    - [#90187: Implement server-side apply upgrade and downgrade](https://github.com/kubernetes/kubernetes/pull/90187)
    - [#90949: Add seccomp least privilege for kuberuntime](https://github.com/kubernetes/kubernetes/pull/90949)
    - [#92784: generic ephemeral inline volumes](https://github.com/kubernetes/kubernetes/pull/92784)
    - [#92310: kubectl debug: support debugging nodes](https://github.com/kubernetes/kubernetes/pull/92310)
    - [#92667:Admission webhook warnings](https://github.com/kubernetes/kubernetes/pull/92667)

- [CNCF Webinar from Alcide.io on recent CVE's](https://www.cncf.io/webinars/kubernetes-security-anatomy-and-the-recently-disclosed-cves/)
    - issues.k8s.io/93032 CVE-2020-8557 Node disk DOS by writing to container /etc/hosts
    - issues.k8s.io/90259 CVE-2020-8558 net.ipv4.conf.all.route_localnet=1 opens security issue
    - issues.k8s.io/92914 CVE-2020-8559 Privilege escalation from compromised node to cluster
- [Shell Operator](https://github.com/flant/shell-operator)
- Tim Hockin breaks down common K8s networking topologies and challenges
    - https://speakerdeck.com/thockin/kubernetes-and-networks-why-is-this-so-dang-hard
    - https://speakerdeck.com/thockin/bringing-traffic-into-your-kubernetes-cluster
- [Istio and Open Usage Commons](https://istio.io/latest/blog/2020/open-usage/)
- We got a [shoutout](https://github.com/vmware-tanzu/tgik/tree/master/episodes/125) on [TGIK!!!](https://tgik.io)

## Meetup Links

## Meetup Slides
- [Dan's slides](https://docs.google.com/presentation/d/1RGbxzaWoZyh2JEWLpFk4eiz8HOCJlCh1_uSxHqVqRnU/edit)

## Meetup Recordings
- [Video on Youtube](https://youtu.be/QLyu-SUdTqQ)

## Meetup Notes

### Who's Hiring 

<!--Company Name: Positions hiring for (link to hiring page), Contact Name/email/etc-->

### Unaffiliated Upcoming Events
- [Kubernetes Made Simple: An Overview of DigitalOcean Kubernetes](https://www.digitalocean.com/community/tech_talks/kubernetes-made-simple-an-overview-of-digitalocean-kubernetes)
    - Digital Ocean is hosting a beginner-oriented one hour talk about their DOKS managed Kubernetes offering at 13:00 ET on August 5th. The link above will take you to a registration page with more details for anyone who might be interested in attending.


###### tags: `meetup`, `2020`, `july`, `tilt`, `ci/cd`, `pipeline` <!--Add additional tags for `year`, `month` and anything else pertinent-->
