[![contributions welcome](https://img.shields.io/badge/contributions-welcome-green.svg?style=flat)](../CONTRIBUTING.md)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)
<img align="right" src="https://github.com/openzerotrust/.github/blob/main/images/OpenZeroTrustLogo_Green2.png" width="150px" />

## Open Zero Trust

# Overview

Open Zero Trust is a Full Lifecycle Container Security platform, delivering cloud-native security with uncompromising end-to-end protection, from DevOps vulnerability protection to automated run-time security, featuring a true Layer 7 container firewall that can block zero days and other threats.

With the Open Zero Trust (OZT) platform, DevOps, DevSecOps, and Security teams have the tools they need to secure the entire container pipeline, from Build to Ship to Run, automatically.

# Table of Contents

- [Migration](#Migration)
- [History](#History)
- [Architecture](#Architecture)
- [Features](#Features)
- [Getting Started](#Getting-Started)
  - [Quick start](#Quick-start)
- [Contributing](#Contributing)
  - [Security](#Security)
- [License](#License)


## History

The Open Zero Trust project started as NeuVector in 2015 by industry veterans Fei Huang and Gary Duan. Fei’s background is in security and virtualization from VMWare and Trend Micro, while Gary’s background is in security at Fortinet and Cisco.

NeuVector, previously a closed source product, has been in production at over a hundred enterprises, securing docker, Kubernetes, OpenShift, Rancher, Mirantis and public cloud (EKS, AKS, IKS, GKE etc) deployments. 
A large cloud service provider has stress tested the NeuVector architecture in a 1,000 node cluster successfully. 

Initially focused on run-time security of production workloads, the product has expanded to provide security across the lifecycle of containers, from build-phase scanning to admission controls and production security. The cloud-native zero trust security platform has had several major releases and is currently in its fifth generation, and there are several patents granted in the areas of network security and automated learning in a container environment.

In October, 2021, SUSE acquired NeuVector and announced plans to open source the software.

### Code
Since it was started as a closed source product, licensed only to enterprise customers for fee, the code history of the project is not publicly available due to issues such as privacy concerns with customer and PII information which existed in various parts of the code, as well as the use of internal proprietary tools for updating and building new versions. Typically, the project had major releases once per year, minor releases every 4-5 months, and bug fix/patch releases every 4-6 weeks.


## Architecture

<img align="center" src="https://github.com/openzerotrust/.github/blob/main/images/ozt_arch.png" alt="Neuvector_architecture" />


There are four main components:

+ [Manager](https://github.com/openzt/manager) - Security Center Admin Console for OZT Container Security Platform.
+ [Scanner](https://github.com/openzt/scanner) - Vulnerability scanner for OZT Container Security Platform.
+ [Enforcer](https://github.com/openzt/neuvector) - The Enforcer is a lightweight container that enforces the security policies.
+ [Controller](https://github.com/openzt/neuvector) - The Controller manages the OZT Enforcer container cluster and provides REST APIs for the management console.



## Features


**[Roadmap](https://github.com/openzerotrust/docs/blob/main/ROADMAP.md)**


## Getting Started

In our [docs](https://open-docs.neuvector.com) you can find many examples and information about OZT.
Documentation for the Open Zero Trust project can be found temporarily [here](https://open-docs.neuvector.com), you can find many examples and information about OZT. This will soon be replicating into this repo.

You can also visit our [official blog](https://blog.neuvector.com/article) where you can find interesting articles, news and anouncements.


If you have some comments and would like to reach out or get involved in the project you can also visit our [chat group]().



### Quick start

OZT can be deployed in many kubernetes distributions and through different container management platforms, here you can find instructions on how to deploy on some of them:
+ [SUSE Rancher](https://open-docs.neuvector.com/deploying/rancher)
+ [Red Hat OpenShift](https://open-docs.neuvector.com/deploying/openshift)
+ [VMWare Tanzu]()
+ [EKS](https://open-docs.neuvector.com/deploying/publick8s)
+ [AKS](https://open-docs.neuvector.com/deploying/publick8s)
+ [GKE](https://open-docs.neuvector.com/deploying/publick8s)

For more information visit the [deployment section](https://open-docs.neuvector.com/deploying/production#planning-deployments)) in our documentation page.



## Contributing

**Contribute and join us!**

Do you have ideas you would like to see implemented into the project? do you see something that needs improvement? have you already developed something and want to see it in the main branch? 


**We welcome contributors!**


It doesn't have to be just technical.


Visit our [Contributing Guidelines](https://github.com/openzerotrust/docs/blob/main/CONTRIBUTING.md).


### Security


We are all about security, if you found a security issue we welcome your feedback.


Please have a look at our [security guidelines](https://github.com/openzerotrust/docs/blob/main/SECURITY.md) for how to report a vulnerability.



## License

Copyright © 2016-2022 [NeuVector Inc](https://neuvector.com). All Rights Reserved

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# Migration

The actively managed project is at [https://github.com/neuvector/neuvector](https://github.com/neuvector/neuvector). It will be migrated to this repository.
