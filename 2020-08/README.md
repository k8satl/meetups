# Kubernetes Atlanta Meetup: August 2020<!--Month Year-->

- **Date: 08.26.2020**<!--date as MM.DD.YYYY-->
- **Location:**
    - [Virtual via Zoom](https://www.meetup.com/Kubernetes-Atlanta-Meetup/events/272232711/)
      - NOTE: You must login to Meetup to view the Zoom link
- **Speakers:**
    - **Mettle: Our GitOps Journey**<!--presentation title-->
        - Steve Wade @ Mettle<!--speaker name/company-->

            > When Steve arrived at Mettle he was asked a question by senior management which he and his team could not answer. This talk will explain how GitOps has enabled them to be able to answer it. Steve will talk about the lessons learnt along the way, the tooling and processes he has helped put in place and what is left to do to complete the journey.
            > 
            > Steve Wade currently leads the Platform Team at Mettle in London. Prior to his current role, Steve was Principal Kubernetes Consultant at Apprenda providing Kubernetes training and implementation services. Steve has served in technology leadership roles across multiple verticals including real estate, gaming, and the UK parliament.
            > 
            > Steve has a BSc in Computer Science from Portsmouth University and is passionate about cloud-native software development and distributed computing.
            > Blog: https://medium.com/@swade1987
            > Twitter: https://twitter.com/swade1987
            > GitHub: https://github.com/swade1987

    - **Spinnaker, Jenkins, and Kubernetes: A sturdy ship ready to set sail**
        - Marky Jackson @ OpsMX

            > Every organization that has chosen the DevOps way wants to do "Continuous" everything, be it integration, deployment, testing, or monitoring. For a DevOps operation, CI/CD is very important for any small or big size organization to shorter development cycles and innovate faster, reduce deployment failures, safe rollbacks and reduce MTTR (mean time to recover).
            > In this meetup, Marky will uncover a new way of bringing continuous integration and continuous delivery of applications to your Kubernetes cluster. He will be using Jenkins as the CI tool, which will poll the Git repositories to build Docker images on commits and push it to the Docker registry. He will use Spinnaker as the CD tool, which continuously polls the Docker registry and triggers the deployment pipelines to update applications in your Kubernetes cluster.
            > 
            > Marky Jackson is a software developer and director of open-source software at OpsMX. He is a lover of family, friends, and a die-hard San Francisco Giants fan.
            > Marky is a Jenkins core code maintainer, SIG mentoring lead, org admin for Google Summer of Code and Google Summer of Docs.
            > Marky is also a Kubernetes org member, release lead associate for all quarterly releases, SIG leader, and administrator throughout the project.
            > Twitter: @markyjackson5
            > Linkedin: https://www.linkedin.com/in/marky-jackson/

- **Hosts:**
    - @alex.b
    - @phenixblue

## This Month in Kubernetes

- **Kubernetes Release Info**
    - [Kubernetes v1.19 should be released today!!!](https://github.com/kubernetes/sig-release/pull/1191)
    - [v1.19 Release Notes](https://github.com/kubernetes/sig-release/pull/1194/files)
    - **Features of note**
        - [Deprecation Warnings](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.19.md#deprecation-warnings)
        - [No more permanenet beta (I'm looking at you Ingress)](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.19.md#avoiding-permanent-beta)
        - [Speaking of Ingress not being Beta](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.19.md#ingress-graduates-to-general-availability)
        - [Debugging tools](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.19.md#expanded-cli-support-for-debugging-workloads-and-nodes)
        - [Endpoint Slices are now on by default](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG/CHANGELOG-1.19.md#endpointslices-are-now-enabled-by-default)
- **Community News**
    - [Hierarchical Namespaces](https://kubernetes.io/blog/2020/08/14/introducing-hierarchical-namespaces/)
        - https://github.com/kubernetes-sigs/multi-tenancy/blob/master/incubator/hnc/docs/user-guide/concepts.md#basic
        - https://github.com/kubernetes-sigs/multi-tenancy/blob/master/incubator/hnc/docs/user-guide/concepts.md#basic-subns
    - [Quake....for Kube...Quake-Kube](https://github.com/criticalstack/quake-kube)
    - [Kubernetes Application API](https://github.com/kubernetes-sigs/application)
        - [API Doc](https://github.com/kubernetes-sigs/application/blob/master/docs/api.md)
        - [Example Wordpress Application](https://github.com/kubernetes-sigs/application/blob/master/docs/examples/wordpress/application.yaml)
    - [What happens when....Kubernetes Edition](https://github.com/jamiehannaford/what-happens-when-k8s)

## Meetup Links

## Meetup Slides

## Meetup Recordings
- [On youtube](https://www.youtube.com/watch?v=a0F66F6zKY4)

## Meetup Notes

### Who's Hiring 

- Sysdig: https://sysdig.com/jobs/
    - Contact: pop@sysdig.com

- OpsMX: OpsMX is hiring

- Square:
    - https://jobs.smartrecruiters.com/ni/Square/18cbbd16-7098-408d-99a2-842f577a2d68
    - Contact: agoldsmith@squareup.com
    - converting to Kubernetes from our homegrown deployment tooling

- Vecima Networks is hiring.
    - We have a hyper-converged storage / video platform running Docker and moving to Kube soon.
    - Contact: jeremy.pullen@vecima.com


- Tock: Full Stack and Front End Developers at exploretock.com. Java and Javascript running in GCP and GKE.
    - located in Chicago, but they’re open to fully distributed folks (I’m in ATL and will continue to be for the foreseeable future).
    - https://www.exploretock.com/join/careers/senior-software-engineer and https://www.exploretock.com/join/careers/senior-software-engineer-frontend
    - Contact: dylan@tockhq.com

- RealTheory is hiring.
    - .NET Core, Golang, AWS, K8s.
    - Work anytime, anywhere
    - Only requires 5 hours a week.
    - If interested, email amazing@realtheory.io

- NCR is hiring
    - Contact Rashed.Kamal (rashed.kamal@ncr.com)

    - R0098954 Cloud Native Developer (Open)
      https://ncr.wd1.myworkdayjobs.com/ext_us/job/ATLANTA-GA-USA/Cloud-Native-Developer_R0098954-1

    - R0098955 Cloud Native Developer (Open)
      https://ncr.wd1.myworkdayjobs.com/ext_us/job/ATLANTA-GA-USA/Cloud-Native-Developer_R0098955

- Flamingo Sec
    - Container Security engineering position
    - email to contact@flamingosec.com
    - Startup K8 Security advisory services

- VMware
    - VMware is hiring a Tanzu Systems Engineer: https://rolp.co/gGVjj
    - Can contact edarby@vmware.com

###### tags: `meetup`, `2020`, `august`, `gitops`, `jenking`, `ci/cd`, `spinnaker` <!--Add additional tags for `year`, `month` and anything else pertinent-->
