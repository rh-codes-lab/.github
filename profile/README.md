# [CoDes Lab: A co-design research lab to advance specialized hardware projects](https://research.redhat.com/blog/research_project/codes-a-co-design-research-lab-to-advance-specialized-hardware-projects/)
<p align="center">
  <img src="https://github.com/rh-codes-lab/.github/blob/c9d6e3907bde4f4e28e7a6bbe46cc886c592f821/img/CoDes_banner.png" alt="CoDees banner" width="600">
</p>

The CoDes research lab provides the infrastructure and engineering foundation needed to support co-design based specialized hardware research. The lab is currently located at Boston University, as part of the Red Hat – Boston University collaboratory. At its core, CoDes targets:

- **Automation**: Replacing developer expertise requirements with Machine Learning, and automating tasks to improve productivity. 
- **Scalability**: Across the cloud-edge continuum, having a common development ecosystem; this in particular includes hardware blocks that can be scaled based on user and system constraints. 
- **Tunability/Configurability**: Enabling developers to configure both hardware and software to better match their requirements. 
- **Features**: Focusing not only on features that are critical for specialized hardware workloads, but also features that can significantly boost productivity and enable exploration into innovative methods for how specialized hardware can be used.
- **Portability**:  Move as much functionality out of the chip/board specific blocks as possible, and minimize the role of components in board support packages.
- **Uniformity**: Having uniform abstractions between different parts of the ecosystem. This includes both uniformity of interfaces between hardware components, as well as uniformity between devices so that specialized hardware can be leveraged by existing software stacks as much as possible.

# Why is CoDes an on-premise infrastructure?
While specialized hardware is readily available in both production and research environments, users are restricted in how they can use specialized hardware since the infrastructure is shared. These constraints limit the type of specialized hardware research that can be done.

Simply put, there is a deadlock –  the current support for specialized hardware is not advanced enough to support systems research, and there is not sufficient systems research possible to advance available support for specialized hardware to address restrictions. CoDes aims to break this deadlock by adding an on-premise incubation step to the process. 

CoDes is not an alternative to large infrastructures in the cloud and edge. Rather, CoDes substantially widens the pool of specialized hardware research projects by minimizing the risk of this research, and by providing researchers with more control over the software and hardware stacks. Once projects reach a certain level of completeness and reliability, they can be transitioned into larger infrastructures and the research can continue in the shared environment.

# What forms of specialized hardware will CoDes target?
Our initial focus is primarily FPGAs and microcontrollers because of the importance of these devices in modern compute environments. As shown by the illustration below, the flexibility and versatility of FPGAs enables them to play various critical roles aimed at improving the performance, power efficiency, resource utilization, security and costs for infrastructures across the cloud-edge continuum. When coupled with microcontrollers, we can add even more capability to the FPGA enhanced systems such as device management, wireless communication, remote debugging etc.

<p align="center">
  <img src="https://github.com/rh-codes-lab/.github/blob/c9d6e3907bde4f4e28e7a6bbe46cc886c592f821/img/fpga_taxonomy.png" width="600">
</p>

In the long run, the goal of CoDes is to target multiple forms of specialized hardware – from other forms of Dataplane Processing Units to Graphics Processing Units to even Quantum computing. This is because we have a: i) large specialized hardware pool, each with its own advantages, and ii) a large workload pool, where each workload can have its own unique combination of hardware, connectivity and code mapping strategy. As a result, there are research opportunities in exploring novel combinations of hardware+workloads that can deliver even better results than established approaches.
 

# Who will be using CoDes?
There are two dimensions of collaboration that CoDes enables. CoDes brings together:

- researchers and engineers in order to ensure that a project’s scientific advancements are built on top of a strong, standard and practical engineering foundation. By leveraging the tried and tested principles of software development, we aim to progress hardware ecosystems at the same rapid pace as software ecosystems.  
- researchers from various disciplines by having completed project milestones available for use by collaborators within the CoDes ecosystem. This centralization and availability of project data, coupled with the above engineering foundation, can reduce the overhead of research, validate completed efforts, help identify areas of further improvement/innovation, lower the bar for entry in specialized hardware research, and  open up new exciting avenues of research.
