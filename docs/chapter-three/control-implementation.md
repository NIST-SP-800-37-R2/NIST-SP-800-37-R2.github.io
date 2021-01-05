---
layout: default
title: • CONTROL IMPLEMENTATION, TASK I-1 
parent: 3.4 IMPLEMENT 
grand_parent: CHAPTER THREE, THE PROCESS
nav_order: 34001
---

### CONTROL SELECTION 
TASK I-1
{: .fs-4 .label }
Implement the controls in the security and privacy plans.  
**Potential Inputs:** Approved security and privacy plans; system design documents; organizational security and privacy policies and procedures; business impact or criticality analyses; enterprise architecture information; security architecture information; privacy architecture information; list of security and privacy requirements allocated to the system, system elements; and environment of operation; system element information; system component inventory; organization- and system-level risk assessment results.  
**Expected Outputs:** Implemented controls.  
**Primary Responsibility:** System Owner; Common Control Provider.  
**Supporting Roles:** Information Owner or Steward; Security Architect; Privacy Architect; Systems Security Engineer; Privacy Engineer; System Security Officer; System Privacy Officer; Enterprise Architect; System Administrator.  
**System Development Life Cycle Phase:** New – Development/Acquisition; Implementation/Assessment. Existing – Operations/Maintenance.  
**Discussion:** Organizations implement the controls as described in the security and privacy plans. The control implementation is consistent with the organization’s enterprise architecture and associated security and privacy architectures. Organizations use best practices when implementing controls, including systems security and privacy engineering methodologies, concepts, and principles. Risk assessments guide and inform decisions regarding the cost, benefit, and risk trade-offs in using different technologies or policies for control implementation. Organizations also ensure that mandatory configuration settings are established and implemented on system elements in accordance with federal and organizational policies. When organizations have no direct control over what controls are implemented in a system element, for example, in commercial off-the-shelf products, organizations consider the use of system elements that have been tested, evaluated, or validated by approved, independent, third-party assessment facilities (e.g., NIST Cryptographic Module Validation Program Testing Laboratories, National Information Assurance Partnership Common Criteria Testing Laboratories). The tests, evaluations, and validations consider products in specific configurations and in isolation; control implementation addresses how the product is integrated into the system while preserving security functionality and assurance. 

Organizations also address, where applicable, assurance requirements when implementing controls. Assurance requirements are directed at the activities that control developers and implementers carry out to increase the level of confidence that the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting the security and privacy requirements for the system. The assurance requirements address quality of the design, development, and implementation of the controls.<sup>85</sup> 

For the common controls inherited by the system, systems security and privacy engineers with support from system security and privacy officers, coordinate with the common control provider to determine the most appropriate way to implement common controls. System owners can refer to the authorization packages prepared by common control providers when making determinations regarding the adequacy of common controls inherited by their systems. During implementation, it may be determined that common controls previously selected to be inherited by the system do not meet the specified security or privacy requirements for the system. For common controls that do not meet the requirements for the system inheriting the controls or when common controls have unacceptable deficiencies, the system owners identify compensating or supplementary controls to be implemented. System owners can supplement the common controls with system-specific or hybrid controls to achieve the required protection for their systems or they can accept greater risk with the acknowledgement and approval of the organization. Risk assessments may determine how gaps in security or privacy requirements between systems and common controls affect the risk associated with the system, and how to prioritize the need for compensating or supplementary controls to mitigate specific risks. 

Consistent with the flexibility allowed in applying the tasks in the RMF, organizations conduct initial control assessments during system development and implementation. Conducting such assessments in parallel with the development and implementation phases of the SDLC facilitates early identification of deficiencies and provides a cost-effective method for initiating corrective actions. Issues discovered during these assessments can be referred to authorizing officials for resolution. The results of the initial control assessments can also be used during the authorize step to avoid delays or costly repetition of assessments. Assessment results that are subsequently reused in other phases of the SDLC meet the reuse requirements established by the organization.<sup>86</sup> 
 
**References:** [FIPS 200]; [SP 800-30]; [SP 800-53]; [SP 800-53A]; [SP 800-160 v1] (Implementation, Integration, Verification, and Transition Processes); [SP 800-161]; [IR 8062]; [IR 8179]. 

***


<sup>85</sup> [SP 800-53] provides a list of assurance-related security and privacy controls.
{: .fs-2}
<sup>86</sup> See the RMF Assess step and [SP 800-53A] for information on assessments and reuse of assessment results.
{: .fs-2}

***
