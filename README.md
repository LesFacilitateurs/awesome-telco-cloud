# Awesome Telco Cloud

A curated list of Telco Cloud ecosystem projects and resources.

- [Awesome Squared](#awesome-squared)
- [Resources](#resources)
  * [Books](#books)
  * [Courses](#courses)
  * [Hands-on trainings](#hands-on-trainings)
  * [Papers](#papers)
  * [Research Projects](#research-projects)
  * [Blogs and Websites](#blogs-and-websites)
- [NF Development Projects](#nf-development-projects)
- [NF Orchestration and Automation Projects](#nf-orchestration-and-automation-projects)
  * [Linux Foundation Networking - LFN projects](#linux-foundation-networking---lfn-projects)
  * [Open Networking Foundation - ONF projects](#open-networking-foundation---onf-projects)
  * [Open Infrastructure Foundation - OIF projects](#open-infrastructure-foundation---oif-projects)
  * [Cloud Native Computing Foundation - CNCF projects](#cloud-native-computing-foundation---cncf-projects)
  * [European Telecommunications Standards Institute - ETSI projects](#european-telecommunications-standards-institute---etsi-projects)
  * [Telecom Infra Project - TIP projects](#telecom-infra-project---tip-projects)
  * [Open Radio Access Network - O-RAN projects](#open-radio-access-network---o-ran-projects)
- [Open Source Cellular Network NFs](#open-source-cellular-network-nfs)
  * [5G](#5g)
  * [4G](#4g)
  * [3G](#3g)
  * [2G](#2g)
- [Private 3G-4G-5G Core Networks based on Open Source](#private-3g-4g-5g-core-networks-based-on-open-source)
- [Artificial Intelligence for Telcos](#artificial-intelligence-for-telcos)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


## Awesome Squared

  - [Awesome Virtualization](https://github.com/Wenzel/awesome-virtualization) - Collection of resources about Virtualization
  - [Awesome SysAdmin](https://github.com/kahun/awesome-sysadmin) - A curated list of open source sysadmin resources
  - [Awesome 5G](https://github.com/calee0219/awesome-5g) - Awesome lists about 5G projects
  - [Awesome Telco](https://github.com/ravens/awesome-telco) - A curated list of telco resources and projects
  - [Awesome SDN](https://github.com/sdnds-tw/awesome-sdn) - A awesome list about Software Defined Network (SDN)
  - [Awesome SDR](https://github.com/mendel5/sdr) - Overview of use cases and applications for software defined radios (SDR)
  - [Awesome Telco Security](https://github.com/Lofmir/awesome-telco-security) - A list of telco security resources and projects
  - [Awesome Free Cloud for Dev](https://github.com/ripienaar/free-for-dev) - A list of SaaS, PaaS and IaaS offerings that have free tiers
  - [Awesome PaaS](https://github.com/debarshibasak/awesome-paas) - A curated list of PaaS, developer platforms, Self hosted PaaS, Cloud IDEs and ADNs
  - [Awesome IoT](https://github.com/phodal/awesome-iot) - A collaborative list of great resources about IoT Framework, Library, OS, Platform

## Resources

### Books

  - [Software Networks: Virtualization, SDN, 5G, and Security](https://ieeexplore.ieee.org/book/9116614)
  - [Cloud Native Patterns](https://www.oreilly.com/library/view/cloud-native-patterns/9781617294297/)
  - [Network Functions Virtualization (NFV) with a Touch of SDN](https://www.amazon.com/Network-Functions-Virtualization-NFV-Touch/dp/0134463056)
  - [Multi-access Edge Computing: Software Development at the Network Edge](https://link.springer.com/book/10.1007/978-3-030-79618-1)
  - [5G System Design: Architectural and Functional Considerations and Long Term Research](https://www.wiley.com/en-us/5G+System+Design%3A+Architectural+and+Functional+Considerations+and+Long+Term+Research-p-9781119425120)
  - [Telco Cloud For Dummies](https://telco.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/microsites/telco/vmware-telco-cloud-for-dummies.pdf)
  - [Private 5G: A Systems Approach](https://github.com/SystemsApproach/private5g)

### Courses

  - [Network Transformation](https://www.coursera.org/learn/network-transformation-101)
  - [Intel Telco Cloud Technologies](https://www.coursera.org/learn/intel-telco-cloud-technologies)
  - [Introduction to Magma: Cloud Native Wireless Networking](https://training.linuxfoundation.org/training/introduction-to-magma-cloud-native-wireless-networking-lfs166x/)
  - [OpenStack and NFV (TelcoCloud)](https://www.udemy.com/course/openstack-telcocloud-asad/)
  - [Kubernetes in NFV (TelcoCloud)](https://www.udemy.com/course/kubernetes-in-nfv-telcocloud/)
  - [Beginners Guide: Software Defined Network, Telco Cloud & NFV](https://www.udemy.com/course/beginners-guide-software-defined-network-telco-cloud-nfv/)
  - [Open RAN (ORAN) architecture, evolution & deployment - 5G](https://www.udemy.com/course/open-ran-oran-architecture-evolution-deployment-5g/)
  - [Private 5G Networks / 5G Non-Public Networks (NPNs)](https://www.udemy.com/course/private-5g-networks-5g-non-public-networks-npns-5g-tsn-industry-4/)

### Hands-on trainings
  - [Lablabee](https://www.lablabee.com/catalog) - Telco cloud technologies with hands-on Labs
  - [K8s 5G Lab](https://github.com/m4r1k/k8s_5g_lab) - 5G Telco Lab based on OpenShift

### Papers
  - [Network Function Virtualization: State-of-the-Art and Research Challenges](https://ieeexplore.ieee.org/abstract/document/7243304)
  - [Virtualizing network services–the telecom cloud](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=62c2e15ec9138f41af9029f5074f3b8b23767311)
  - [Carrier grade Telco-Cloud](https://ieeexplore.ieee.org/abstract/document/7374941)
  - [Large-scale cluster management at Google with Borg](https://research.google/pubs/pub43438/)

### Research Projects

  - [5GPPP 5G EVE](https://github.com/5GEVE) - the European 5G validation platform for extensive trials
  - [5GPPP 5Genesis](https://github.com/5genesis) - 5G KPIs validation infrastructure
  - [SoftFIRE](https://github.com/softfire-eu) - federated NFV/SDN testbed infrastructure

### Blogs and Websites

  - [K8s introducing SCTP multihoming functionality with LoxiLB](https://www.loxilb.io/post/k8s-introducing-sctp-multihoming-functionality-with-loxilb)

## NF Development Projects
  - [Ligato](https://ligato.io/) - a Go Framework for Building Applications to Control and Manage Cloud Native Network Functions (CNF)
  - [CNCF CNF Test Suite](https://github.com/cncf/cnf-testsuite) - check K8s + cloud native best practices in networking applications and platforms
  - [TRex](https://github.com/cisco-system-traffic-generator/trex-core) - Realistic Traffic Generator
  - [Firecracker](https://github.com/firecracker-microvm/firecracker) - microVMs for serverless computing from AWS
  - [OpenShift CNF Features Deploy](https://github.com/openshift-kni/cnf-features-deploy) - Kustomize configs for installing CNF features and e2e functional tests for verifying feature deployment/integration
  - [CNCF CNF Certification](https://github.com/cncf/cnf-certification) - Beta release for Cloud native Network Function Certification program
  - [cnfuzz](https://github.com/suecodelabs/cnfuzz) - Breaking Cloud Native Web APIs in their natural habitat
  - [ETSI api-test](https://forge.etsi.org/rep/nfv/api-tests) - NFV API Conformance test specification
  - [Cisco NSO developer](https://github.com/NSO-developer) - developer tools of the Cisco Network Services Orchestrator
  - [5G APIs](https://forge.3gpp.org/rep/all/5G_APIs) - OpenAPI Specification Files for 3GPP 5G Core Network
  - [Kata Containers](https://katacontainers.io/) - CRI compatible implementation of lightweight virtual machines

## NF Orchestration and Automation Projects

### Linux Foundation Networking - LFN projects

  - [Camara](https://camaraproject.org/) - 4G/5G network capabilities exposed through APIs
  - [Magma](https://github.com/magma/magma) - an open source platform for building access networks and modular network services 
  - [Anuket](https://wiki.anuket.io/) - Standardized reference infrastructure specifications and CNF compliance
    - [NFVBench](https://docs.anuket.io/projects/nfvbench/en/latest/testing/user/userguide/installation.html) - Configuration, orchestration, and traffic generation
  - [EMCO](https://project-emco.io/) - Kubernetes-based end-to-end inter-application communication at the Edge
  - [L3AF](https://l3af.io/) - a control plane and a marketplace for eBPF programs
  - [ONAP](https://www.onap.org/) - orchestration, management, and automation of network and edge computing services
  - [XGVela](https://xgvela.org/) - reference design of telco-PaaS to accelerate cloud native transformation for telcos

### Open Networking Foundation - ONF projects

  - [Aether](https://opennetworking.org/aether/) - open source 5G Connected Edge platform
  - [OMEC](https://github.com/omec-project) - 3GPP Release 13 compatible stand-alone EPC
  - [CORD](https://github.com/opencord) - leverages SDN, NFV to build agile datacenters for the network edge
  - [ODTN](https://wiki.onosproject.org/display/ODTN/ODTN) - an open source platform for running multi-vendor optical transport networks
  - [XOS](https://github.com/opencord/xos) - a model-based platform for assembling, controlling, and composing services

### Open Infrastructure Foundation - OIF projects

  - [StarlingX](https://www.starlingx.io/) - cloud infrastructure software stack for the edge used for industrial IOT, telecom, video delivery and other ultra-low latency use cases
  - [OpenStack Tacker](https://opendev.org/openstack/tacker/) - ETSI MANO NFV Orchestrator / VNF Manager
  - [Kata Containers](https://katacontainers.io/) - CRI compatible implementation of lightweight virtual machines
  - [Airship](https://www.airshipit.org/) - a collection of loosely coupled but interoperable open source tools that declaratively automate cloud provisioning


### Cloud Native Computing Foundation - CNCF projects
  - Cloud-native Network Function (CNF) Testbed [project](https://github.com/cncf/cnf-testbed)
  - CNCF Telecom User Group [page](https://github.com/cncf/telecom-user-group)

### European Telecommunications Standards Institute - ETSI projects

  - [Open Source MANO](https://osm.etsi.org/) - an ETSI-hosted project to develop an Open Source NFV Management and Orchestration (MANO) software stack aligned with ETSI NFV
  - [VIM emulator](https://osm.etsi.org/gitweb/?p=osm/vim-emu.git;a=tree) - a NFV multi-PoP emulation platform

### Telecom Infra Project - TIP projects

  - [OpenCellular](https://github.com/Telecominfraproject/OpenCellular) - an open source platform with a focus on enabling rural connectivity
  - [wlan-ap](https://github.com/Telecominfraproject/wlan-ap) - an OpenWrt-based access point network operating system (AP NOS) for TIP OpenWiFi
  - [GNPy](https://github.com/Telecominfraproject/oopt-gnpy) - an open source simulator for Fiber networks with Route Planning, Based on a Gaussian Noise Model 

### Open Radio Access Network - O-RAN projects 

  - [it/test](https://gerrit.o-ran-sc.org/r/gitweb?p=it%2Ftest.git;a=summary) - end-to-end testing and validation for the oran ric project
  - [it/rtp](https://gerrit.o-ran-sc.org/r/gitweb?p=pti%2Frtp.git;a=summary) - Performance Tuned Infrastructure
  - [ric-plt/appmgr](https://gerrit.o-ran-sc.org/r/gitweb?p=ric-plt%2Fappmgr.git;a=summary) - deployment and management of various RIC xApp applications in Kubernates environment
  - [ric-plt/jaegeradapter](https://gerrit.o-ran-sc.org/r/gitweb?p=ric-plt%2Fjaegeradapter.git;a=summary) - bootstrap project for Jaeger Agent as a side-car container

## Open Source Cellular Network NFs

### 5G

  - [OpenAirInterface 5G RAN](https://openairinterface.org/oai-5g-ran-project/) - an open source 5G Radio Access Network supporting 5G SA & NSA
  - [srsRAN](https://github.com/srsran/srsran_project) - a complete 5G RAN solution, featuring an ORAN-native CU/DU
  - [Free5GC](https://free5gc.org/) - an open-source project for 5th generation (5G) mobile core networks (Release 15)
  - [Open5GS](https://open5gs.org/) - a C-language Open Source implementation of 5G Core Network (Release-16)
  - [OpenAirInterface 5GC](https://openairinterface.org/oai-5g-core-network-project/) - an open source 5G core network

### 4G

  - [srsENB](https://www.srslte.com/4g) - a full-stack SDR 4G eNodeB application
  - [Open5GS](https://open5gs.org/) - a C-language Open Source implementation of 4G EPC
  - [srsEPC](https://www.srslte.com/4g) - a light-weight 4G core network implementation with MME, HSS and S/P-GW
  - [Corenet](https://github.com/mitshell/corenet) - Minimal 3G and LTE / EPC core network
  - [OMEC](https://opennetworking.org/omec/) - an Open Source Virtualized Mobile Core Project from ONF

### 3G

  - [OpenBTS-UMTS ](https://github.com/RangeNetworks/OpenBTS-UMTS) - a 3G UMTS Data Radio Access Network Node
  - [Corenet](https://github.com/mitshell/corenet) - Minimal 3G and LTE / EPC core network
  - [OsmoSGSN](https://osmocom.org/projects/osmosgsn) - an Open Source implementation of a SGSN (Serving GPRS Support Node)
  - [OsmoGGSN](https://osmocom.org/projects/openggsn) - an Open Source implementation of a GGSN (Gateway GPRS Support Node)

### 2G

  - [OsmocomBB](https://osmocom.org/projects/baseband/wiki) - an Open Source GSM Baseband software implementation
  - [OpenBTS](https://github.com/RangeNetworks/openbts) - an open source GSM+GPRS Radio Access Network Node
  - [OsmoTRX](https://osmocom.org/projects/osmotrx) - a GSM Radio Modem based on a fork of the OpenBTS Transceiver program
  - [OsmoBTS](https://osmocom.org/projects/osmotrx/wiki/OsmoTRX) - a software implementation of a GSM BTS

## Private 3G-4G-5G Core Networks based on Open Source
  
  - [BubbleRAN](https://bubbleran.com) - private 4G/5G core network based on OpenAirInterface
  - [OAIBOX](https://oaibox.com/) - private 5G core network based on OpenAirInterface
  - [Saviah](https://www.saviah.com/en) - private 5G core network based on Free5GC
  - [firecell](https://firecell.io/) - private 4G & 5G core networks based on OpenAirInterface
  - [5-fi](https://5-fi.net/) - 5G private core network based on OpenAirInterface
  - [sysmocom](https://sysmocom.de/products/cni/) - 3G & 4G private core networks based on Osmocom
  - [NeoPlane](https://neoplane.io/) - private 4G & 5G core networks based on Open5GS

## Artificial Intelligence for Telcos

  - [Telco-RAG](https://github.com/netop-team/Telco-RAG) - a specialized Retrieval-Augmented Generation for 3GPP documents