---
layout: default
title: • CONTROL ALLOCATION, TASK S-3 
parent: 3.3 SELECT 
grand_parent: CHAPTER THREE, THE PROCESS
nav_order: 31003
---

### CONTROL ALLOCATION 
TASK S-3
{: .fs-4 .label }
Allocate security and privacy controls to the system and to the environment of operation.  
**Potential Inputs:** Security categorization; organization- and system-level risk assessment results; organizational policy on system registration; enterprise architecture; security and privacy architectures; security and privacy requirements; list of security and privacy requirements allocated to the system, system elements, and the environment of operation; list of common control providers and common controls available for inheritance; system description; system element information; system component inventory; relevant laws, executive orders, directives, regulations, and policies.  
**Expected Outputs:** List of security and privacy controls allocated to the system, system elements, and the environment of operation.  
**Primary Responsibility:** Security Architect; Privacy Architect; System Security Officer; System Privacy Officer.  
**Supporting Roles:**  Chief Information Officer; Authorizing Official or Authorizing Official Designated Representative; Mission or Business Owner; Senior Agency Information Security Officer; Senior Agency Official for Privacy; System Owner.  
**System Development Life Cycle Phase:** New – Initiation (concept/requirements definition). Existing – Operations/Maintenance.  
**Discussion:** The organization designates controls as system-specific, hybrid, or common, and allocates the controls to the system elements (i.e, machine, physical, or human elements) responsible for providing a security or privacy capability. Controls are allocated to a system or an organization consistent with the organization’s enterprise architecture and security or privacy architecture and the allocated security and privacy requirements. Not all controls need to be allocated to every system element. Controls providing a specific security or privacy capability are only allocated to system elements that require that capability. The security categorization, privacy risk assessment, security and privacy architectures, and the allocation of controls work together to help achieve a suitable balance between security and privacy protections and the mission-based function of the system.  
   
Security and privacy requirements allocated to the system, system elements, and the environment of operation (see Task P-17) guide and inform control allocation to system elements. Common controls that are made available by the organization during the RMF Prepare-Organization Level step (see Task P-5), are selected for inheritance; hybrid controls are also selected. Common controls satisfy security and privacy requirements allocated to the organization and provide a protection capability that is inherited by one or more systems. Hybrid controls satisfy security and privacy requirements allocated to the system and to the organization and provide a protection capability that is partially inherited by one or more systems. And finally, system-specific controls satisfy security and privacy requirements allocated to the system and provide a protection capability for that system. Controls can be allocated to specific system elements rather than to every element within a system. For example, system-specific controls associated with management of audit logs may be allocated to a log management server and need not be implemented on every system element.  
**References:** [SP 800-39] (Organization, Mission/Business Process, and System Levels); [SP 800-64]; [SP 800-160 v1] (System Requirements Definition, Architecture Definition, and Design Definition Processes); [NIST CSF] (Core [Identify Function]; Profiles); [OMB FEA].  

