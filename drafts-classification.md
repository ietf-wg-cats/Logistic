

# Reminder of CATS Charter

The CATS WG is chartered to work on the following items:

* (**Use Cases**) Groundwork may be documented via a set of informational Internet-Drafts, not necessarily for publication as RFCs:

    + Problem statement for the need to consider both network and computing resource status.
    + Use cases for steering traffic from applications that have critical
      SLAs that would benefit from the integrated consideration of network
      and computing resource status.
    + Requirements for commonly agreed computing metrics and their
      distribution across the overlay network, as well as the appropriate
      frequency and scope of distribution.

* (**Framework**) Overall CATS framework & architecture:

This work encompasses the various building blocks and their
interactions, realizing a CATS control and data plane that addresses
the identified problems and requirements in the groundwork,
including methods for distributing necessary information to utilize
the identified metrics in CATS use cases. This will also cover OAM,
scalability, and security aspects.

* Additional groundwork to include:

   + Analyze the suitability and usefulness of computing and networking
metrics for traffic steering decisions in CATS with a CATS metrics
ontology as a possible outcome.
   + Analyze methods for distributing the necessary information to
utilize the identified metrics in CATS use cases.

* (**Applicability**)  Applicability of existing tools and mechanisms:

   + Analysis of implementing the CATS control and data plane using
existing mechanisms, including identifying the limitations of
existing tools in fulfilling requirements.

   + Study potential new approaches for the CATS control and data plane
solution that can fill the identified gaps in existing tools and
solutions.

   + Study FCAPS (fault, configuration, accounting, performance,
security) requirements, mechanisms, and suitability of existing
messaging protocols (NETCONF) and data models (YANG).

# I-Ds

| I-D                                           |Title                                                                     | Topic              | In/Out Scope |
|----------------------------------------------:|:-------------------------------------------------------------------------|:------------------:|:------------:|
|draft-jeong-cats-its-use-cases                 |Use Cases for Computing-Aware Intelligent Transportation Systems Use Cases| Use Cases          |      ?       |
|draft-lcmw-cats-midhaul                        |Compute-Aware Traffic Steering for Midhaul Networks) Use Cases	           | Use Cases          |      ?       |
|draft-wang-cats-security-considerations        | Security Considerations for Computing-Aware Traffic Steering 	           | Framework          |      ?       |
|draft-wang-cats-usecase-green                  | A Use case for Green Computing-Aware Traffic Steering                    | Use Cases          |      ?       |
|draft-ysl-cats-metric-definition               | CATS metric Definition                                                   | Metrics            |      ?       |
|draft-lu-cats-smam-security                    | A mechanism of security monitoring and management for service resources in CATS| Solutions    |      ?       |
|draft-shi-cats-analysis-of-metric-distribution | Design analysis of methods for distributing the computing metric	       | Metrics            |      ?       |
|draft-yi-cats-hierarchical-metric-distribution | Hierarchical methods of computing metrics distribution	                 | Metrics            |      ?       |
|draft-yuan-cats-hierarchical-loop-prevention   | Microloop Prevention in a Hierarchical Segment Routing Solution for CATS | Solutions          |      ?       |	
|draft-jiang-cats-usecase-5gedge                | Computing-Aware 5G Edge Enhancement                                      | Use Cases          |      ?       |
|draft-wang-cats-awareness-system-for-casfc     | Information Awareness System for Computing-Aware Service Function Chain (IAS-CASFC): Security Service Aspect|Framework | ?|	
|draft-bernardos-cats-anchoring-service-mobility| Service Mobility-Enabled Computing Aware Traffic Steering using IP address anchoring| Solutions|      ?       |	
|draft-bernardos-cats-ip-address-anchoring      | Computing Aware Traffic Steering using IP address anchoring              | Solutions          |      ?        |	
|draft-fu-cats-muti-dp-solution                 | Analysis for Multiple Data Plane Solutions of Computing-Aware Traffic Steering | Applicability|      ?        |	
|draft-fu-cats-oam-fw                           | Operations, Administration and Maintenance (OAM) for Computing-Aware Traffic Steering	|  OAM  |      ?        |
|draft-yl-cats-data-model                       | Data Model for CATS	                                                     | OAM                |      ?        |
|draft-fu-cats-flow-lb                          | Flow-Level Load Balancing of Computing-Aware Traffic Steering (CATS)	   | Solutions          |      ?        |	
|draft-yi-cats-hybrid-solution                  | Hybrid Computing and Network Awareness and Routing Solution for CATS     | Solutions          |      ?        |	
|draft-du-cats-aggregated-metrics-on-egress     | Aggregated Metrics on Egress Node and Corresponding Routing Mechanism	   | Metrics            |      ?        |
|draft-wang-cats-green-challenges               | Green Challenges in Computing-Aware Traffic Steering (CATS)              | Use Cases          |      ?        |
|draft-du-cats-computing-modeling-description   | Computing Information Description in Computing-Aware Traffic Steering	   | Metrics            |      ?        |	
|draft-lbdd-cats-dp-sr                          | Computing-Aware Traffic Steering (CATS) Using Segment Routing	           | Applicability      |      ?        |
|draft-fu-cats-sr-te-based-solution             | An SR-TE based Solution For Computing-Aware Traffic Steering	           | Applicability      |      ?        |	
|draft-gao-cats-oam-data-collection             | OAM data collection for service decision-making in Computing-Aware Traffic Steering| OAM      |      ?        |	
|draft-ftzhs-cats-industrial-requirement        | Problem statements and requirements of Deterministic CATS on the Industrial Internet| Use Cases|     ?        |
|draft-jaehwoon-cats-mobility                   | Network-based mobility management in CATS network environment            | Solutions          |      ?        |	

