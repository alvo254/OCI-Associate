# OCI-Associate
This is documentation on Oracle Cloud Infrastructure Associate
### Review exam topics

**Getting Started with OCI**

-   Describe the key features and components of OCI
-   Discuss OCI Regions and Availability Domains

**Core OCI Services**

-   Describe OCI Compute services
-   Describe  OCI Storage services
-   Describe OCI Networking services
-   Describe OCI Observability and Management services
-   Describe  OCI Analytics and AI services
-   Describe OCI Hybrid offerings
-   Describe OCI App Dev services
-   Describe OCI Database services

 **Security and Compliance**

-   Explain the OCI Security model
-   Describe OCI Security services
-   Describe OCI Identity and Access Management services

**OCI Pricing, Support and Operations (Governance and Administratio**n)

-   Explain the OCI Pricing model
-   Explain the OCI SLA and Support model

## OCI Cloud racer 

Regions and ADs
OCI has been built using the concept of regions. A region is simply a physical location in the world where OCI hosts data centers. In a nutshell, a region is a localized geographic area. Within a region, OCI hosts one or more physical data centers and calls this an Availability Domain (AD).
In this section, we will look at the main concepts of OCI in more detail, such as regions, ADs, and fault domains. Additionally, we will learn how to subscribe to other regions.
A lot of OCI services are regional; for example, Virtual Cloud Networks (VCNs). If you create a VCN, it will span across the AD. Other services are AD-specific, such as compute resources. You can create a compute instance that has access to a specific AD. Additionally, there is a very strong interconnectivity between the ADs within a region and across regions. Within an AD, interconnected traffic is encrypted as well.
