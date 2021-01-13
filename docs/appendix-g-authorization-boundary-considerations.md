---
layout: default
title: . AUTHORIZATION BOUNDARY CONSIDERATIONS 
nav_order: 100000
---

#### APPENDIX G 
{: .no_toc }
## AUTHORIZATION BOUNDARY CONSIDERATIONS 
{: .no_toc }

COMPLEX SYSTEMS, APPLICATIONS, AND THE EFFECTS OF CHANGING TECHNOLOGIES

1. TOC
{:toc}

This appendix provides additional considerations for determining authorization boundaries for complex systems and software applications. It also includes guidance on authorization boundaries when organizations use external providers for their information resources. The foundational RMF steps and tasks described in Chapter Three can be applied in all three scenarios to help organizations manage security and privacy risks and comply with the laws, executive orders, and OMB policies discussed in Chapter One.  

### AUTHORIZATION BOUNDARIES FOR COMPLEX SYSTEMS
The determination of authorization boundaries for complex systems can present significant challenges to organizations. A complex system can be viewed as set of individual subsystems. A subsystem is a major subdivision of a system consisting of system elements that perform one or more specific functions. Figure G-1 illustrates the concept of a complex system.  

![FIGURE G-1: CONCEPTUAL VIEW OF A COMPLEX SYSTEM](https://statics.bsafes.com/images/NIST-SP-800-37-R2-Fig-G-1.png)

Organizations can employ the concept of subsystems to divide complex systems into a set of manageable system elements or identify those elements that support a similar mission, but are sufficiently distinct to be identified separately. Each subsystem has its own boundary (distinct from an authorization boundary) and can be defined within a comprehensive authorization boundary that includes all subsystems.  

For example, an organization may find it useful to combine several systems that are under the same direct management control or that have similar missions or business functions into a single system to achieve the dual purposes of effective risk and resource management. An organization may also choose to develop a system composed of multiple independent systems (distributed across a widespread geographic area) supporting a set of common missions or business functions. Similarly, a system can be divided into multiple subsystems to facilitate and support management of the system and risk-based decision making (e.g., categorization decisions, tailoring decisions, and control allocation decisions).  

Dividing a system into subsystems (i.e., divide and conquer) facilitates a targeted application of controls to achieve adequate security, protection of individual privacy, and a cost-effective risk management process. Dividing complex systems into subsystems also supports the important security concepts of domain separation and network segmentation, which can be significant when dealing with high value assets. When systems are divided into subsystems, organizations may choose to develop individual subsystem security and privacy plans or address the system and subsystems in the same security and privacy plans.  

Information security and privacy architectures play a key part in the process of dividing complex systems into subsystems. This includes monitoring and controlling communications at internal boundaries among subsystems and selecting, allocating, and implementing controls that meet or exceed the security and privacy requirements of the constituent subsystems. One approach to control selection and allocation is to categorize each identified subsystem separately (see Task C-2). However, separately categorizing each subsystem does not change the overall categorization of the system. Rather, separately categorizing each subsystem allows the subsystems to receive a separate and more targeted allocation of controls from [SP 800-53] instead of deploying higher-impact controls across the entire system (see Task P-17 and Task S- 3). Another approach is to bundle smaller subsystems into larger subsystems within the system, categorize each of the aggregated subsystems, and allocate controls to the subsystems, as needed. While subsystems within complex systems may exist as complete systems, the subsystems are, in most cases, not treated as independent entities because they are typically interdependent and interconnected.  

When the security categorizations for the identified subsystems are different (e.g., low-impact versus high-impact), the organization examines the subsystem interfaces,<sup>164</sup> information flows, and security and privacy dependencies among subsystems and selects the appropriate controls for the interconnection of the subsystems to eliminate or reduce potential vulnerabilities. This helps to ensure that the system is adequately protected. Controls for the interconnection of subsystems are also employed when the subsystems implement different security and privacy policies or are administered by different authorities. The extent to which the selected controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting the security and privacy requirements for the complex system, can be determined by combining control assessments at the system level and adding considerations addressing interface issues. The combined approach facilitates a targeted and cost-effective risk management process by scaling the level of effort of the assessment in accordance with the security categorization and allowing for reuse of assessment results at the system level.  

***

<sup>164</sup> The types of interfaces and couplings among subsystems may introduce inadvertent vulnerabilities in a complex system. For example, if a large organizational intranet is decomposed into smaller subsystems (e.g., severable systems such as local area network segments) and subsequently categorized individually, the specific protections at the system level may expose an attack vector against the intranet by erroneously selecting and implementing controls that are not sufficiently strong with respect to the rest of the system. To avoid this situation, organizations carefully examine the interfaces among subsystems and take appropriate actions to eliminate potential vulnerabilities in this area, thus helping to ensure that the information system is adequately protected.
{: .fs-2}

***

### AUTHORIZATION BOUNDARIES FOR SOFTWARE APPLICATIONS
Authorization boundaries include all system elements, including hardware, firmware, and software. Software elements include applications (e.g., database applications, customized business applications, and web applications), middleware, and operating systems. The software elements are included in authorization boundaries, either as part of the information system on which the software is hosted or as a part of an application-only system or subsystem that inherits controls from the hosting system. Software applications may depend on the resources provided by the hosting system and as such, can leverage the controls provided by the hosting system to help provide a foundational level of protection for the hosted applications. Additional application-level controls are provided by the respective software applications, as needed. Application owners coordinate with system owners to help ensure that security and privacy requirements are satisfied among applications and hosting systems. Coordination between system owners and application owners includes, for example, consideration for the selection, implementation, assessment, and monitoring of controls for the applications; the effects of changes to the applications on the security and privacy posture of the system and the organization; and the effects of changes to the system on the hosted applications.  

### AUTHORIZATION BOUNDARIES AND EXTERNAL PROVIDERS
While the concepts of external systems and external service providers are not new, the current pervasiveness and frequency of their invocation can present organizations with significant, new challenges. There are instances where system elements, subsystems, or perhaps the entire system may be outside of the direct control of the organization that authorizes its operation. The nature of such external systems can vary from organizations employing external cloud computing services to process, store, and transmit federal information to organizations allowing platforms under their control to host applications or services developed by some external entity.<sup>165</sup>

FISMA and OMB policy require external providers that process, store, or transmit federal information or operate information systems on behalf of the federal government to meet the same security and privacy requirements as federal agencies. Federal security and privacy requirements also apply to external systems storing, processing, or transmitting federal information and any services provided by or associated with the external system. Furthermore, the assurance or confidence that the risk from using external providers is at an acceptable level depends on the trust that the organization places in the provider. In some instances, the level of trust is based on the amount of direct control the organization can exert on the provider regarding the employment of controls necessary to protect federal information and protect the privacy of individuals.  

The level of trust can also be based on the evidence brought forth by the external provider or by an independent assessor as to the effectiveness of those controls. In other instances, trust can be based on other factors, such as the previous experience the organization has had with the external provider and the confidence the organization has in the provider taking the correct actions. There are a variety of factors that can complicate the level of trust with external providers:
* The delineation between what is owned by the external provider and the organization may be blurred (e.g., organization-owned platform executing external provider-developed application, software module, or firmware);
* The degree of control the organization has over the external provider may be very limited;
* The nature and content of the system, subsystem, service, or application may be subject to
rapid change; and
* The system, subsystem, service, or application may be of such critical nature that it needs to be incorporated into organizational systems very rapidly.
The consequence of the above factors is that some of the traditional means organizations use to verify and validate the correct functioning of a system, subsystem, application or service and the effectiveness of implemented controls (e.g., clearly defined requirements, design analysis, testing and evaluation before deployment, control assessments and continuous monitoring) may not be feasible. As a result, organizations may be left to depend upon the nature of the trust relationships with the external provider as the basis for determining whether to issue an authorization to use or authorization to operate for the system or subsystems processing, storing, or transmitting federal information (e.g., use of GSA list of approved providers). Alternatively, organizations may allow externally provided systems or services to be used only in those instances where the exchange of information risk determined by the organization is acceptable.  

Ultimately, when the level of trust in the external provider does not provide sufficient assurance, the organization employs compensating controls; accepts greater risk; contracts with a more trustworthy external provider; or does not obtain the service (i.e., conducts its missions and business operations with reduced levels of functionality or possibly no functionality at all).
 
***

<sup>165</sup> The Federal Risk and Authorization Management Program (FedRAMP) operated by the General Services Administration (GSA) provides guidance on determining cloud authorization boundaries.
{: .fs-2}

***

<div style="background-color:lightblue; padding:20px" markdown="1">
<h3 style="text-align:center">LEVERAGING EXTERNAL PROVIDER CONTROLS AND ASSESSMENTS</h3>
Organizations should exercise caution when attempting to leverage external provider controls and assessment results. Controls implemented by external providers may be different than the controls in [SP 800-53] in the scope, coverage, and capability provided. NIST provides a mapping of the controls in its catalog to the [ISO 27001] security controls and to the [ISO 15408-2] and [ISO 15408-3] security requirements. However, such mappings are inherently subjective and should be reviewed carefully by organizations to determine if the controls and requirements addressed by external providers meet the protection needs of the organization. The mappings between different standards or guidelines also do not address the potential for differing scopes and purpose for each publication.  

Similar caution should be exercised when attempting to use or leverage security and privacy assessment results from external providers. The type, rigor, and scope of the assessments may vary widely from provider to provider. In addition, the assessment procedures employed by the provider and the independence of the assessors conducting the assessments are critical issues that should be reviewed and considered by organizations prior to leveraging assessment results.  

Effective risk decisions by authorizing officials depend on the transparency of controls selected and implemented by external providers and the quality and efficacy of the assessment evidence produced by those providers. Transparency is essential to achieve the assurance necessary to ensure adequate protection for organizational assets.
</div>
