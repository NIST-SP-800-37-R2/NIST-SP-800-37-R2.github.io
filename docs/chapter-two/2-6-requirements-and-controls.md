---
layout: default
title: 2.6 REQUIREMENTS AND CONTROLS  
parent: CHAPTER TWO, THE FUNDAMENTALS 
nav_order: 260
---
<style>
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}
</style>

## 2.6 REQUIREMENTS AND CONTROLS 

Before executing the RMF, it is important to understand the concept of security and privacy requirements and the relationship between requirements and controls. The term requirements can be used in different contexts. In the context of federal information security and privacy policies, the term is generally used to refer to information security and privacy obligations imposed on organizations. For example, OMB Circular A-130 imposes a series of information security and privacy requirements with which federal agencies must comply when managing information resources. In addition to the use of the term requirements in the context of federal policy, the term requirements is used in this guideline in a broader sense to refer to an expression of the set of stakeholder protection needs for a particular system or organization. Stakeholder protection needs and corresponding security and privacy requirements may be derived from many sources (e.g., laws, executive orders, directives, regulations, policies, standards, mission and business needs, or risk assessments). The term requirements, as used in this guideline, includes both legal and policy requirements, as well as an expression of the broader set of stakeholder protection needs that may be derived from other sources. All of these requirements, when applied to a system, help determine the required characteristics of the system—encompassing security, privacy, and assurance.

Organizations may choose to divide security and privacy requirements into more granular categories depending on where the requirements are employed in the SDLC and for what purpose. Organizations may use the term _capability requirement_ to describe a capability that the system or organization must provide to satisfy a stakeholder protection need. In addition, organizations may refer to system requirements that pertain to particular hardware, software, and firmware components of a system as _specification requirements_—that is, capabilities that implement all or part of a control and that may be assessed (i.e., as part of the verification, validation, testing, and evaluation processes). Finally, organizations may use the term _statement of work_ requirements to refer to actions that must be performed operationally or during system development.

_Controls_ can be viewed as descriptions of the safeguards and protection capabilities appropriate for achieving the particular security and privacy objectives of the organization and reflecting the protection needs of organizational stakeholders. Controls are selected and implemented by the organization in order to satisfy the system requirements. Controls can include technical aspects, administrative aspects, and physical aspects. In some cases, the selection and implementation of a control may necessitate additional specification by the organization in the form of _derived requirements_ or instantiated control parameter values. The derived requirements and control parameter values may be necessary to provide the appropriate level of implementation detail for particular controls within the SDLC.

<div style="background-color:lightblue; padding:20px" markdown="1">
<h3 style="text-align:center">CONTEXT-DEPENDENT REQUIREMENTS</h3>
Security and privacy requirements and risks identified by the organization, lead to the need for security and privacy controls to respond to the risk. The controls selected by the organization subsequently lead to both specification requirements and statement of work requirements in the systems engineering context. This is an important aspect of how systems engineers develop, derive, and decompose requirements as part of the SDLC process. Thus, organizations manage security and privacy requirements at various levels of granularity and specificity during the life cycle of the system. Controls play an important part in the life cycle by providing high-level statements of protection capability that can be refined and expanded upon by the organization.
</div>
