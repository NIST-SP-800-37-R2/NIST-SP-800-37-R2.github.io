---
layout: default
title: • CONTROL ASSESSMENTS, TASK A-3 
parent: 3.5 ASSESS 
grand_parent: CHAPTER THREE, THE PROCESS
nav_order: 35003
---

### CONTROL ASSESSMENTS 
TASK A-3
{: .fs-4 .label }
Assess the controls in accordance with the assessment procedures described in assessment plans.  
**Potential Inputs:** Security and privacy assessment plans; security and privacy plans; external assessment or audit results (if applicable).  
**Expected Outputs:** Completed control assessments and associated assessment evidence.  
**Primary Responsibility:** Control Assessor.
**Supporting Roles:** Authorizing Official or Authorizing Official Designated Representative; System Owner; Common Control Provider; Information Owner or Steward; Senior Agency Information Security Officer; Senior Agency Official for Privacy; System Security Officer; System Privacy Officer.  
**System Development Life Cycle Phase:** New – Development/Acquisition; Implementation/Assessment. Existing – Operations/Maintenance.  
**Discussion:** Control assessments determine the extent to which the selected controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting security and privacy requirements for the system and the organization. The system owner, common control provider, and/or organization rely on the technical skills and expertise of assessors to assess implemented controls using the assessment procedures specified in assessment plans and provide recommendations on how to respond to control deficiencies to reduce or eliminate identified vulnerabilities or unacceptable risks. The senior agency official for privacy serves as the control assessor for the privacy controls and is responsible for conducting an initial assessment of the privacy controls prior to system operation, and for assessing the controls periodically thereafter at a frequency sufficient to ensure compliance with privacy requirements and to manage privacy risks.<sup>89</sup> Controls implemented to achieve both security and privacy objectives may require a degree of collaboration between security and privacy control assessors. The assessor findings are a factual reporting of whether the controls are operating as intended and whether any deficiencies<sup>90</sup> in the controls are discovered during the assessment. 

Control assessments occur as early as practicable in the SDLC, preferably during the development phase. These types of assessments are referred to as developmental testing and evaluation, and validate that the controls are implemented correctly and are consistent with the established information security and privacy architectures. Developmental testing and evaluation activities include, for example, design and code reviews, regression testing, and application scanning. Deficiencies identified early in the SDLC can be resolved in a more cost-effective manner. Assessments may be needed prior to source selection during the procurement process to assess potential suppliers or providers before the organization enters into agreements or contracts to begin the development phase. The results of control assessments conducted during the SDLC can also be used (consistent with reuse criteria established by the organization) during the authorization process to avoid unnecessary delays or costly repetition of assessments. Organizations can maximize the use of automation to conduct control assessments to increase the speed, effectiveness, and efficiency of the assessments, and to support continuous monitoring of the security and privacy posture of organizational systems. 

Applying and assessing controls throughout the development process may be appropriate for iterative development processes. When iterative development processes (e.g., agile development) are employed, an iterative assessment may be conducted as each cycle is completed. A similar process is employed for assessing controls in commercial IT products that are used in the system. Organizations may choose to begin assessing controls prior to the complete implementation of all controls in the security and privacy plans. This type of incremental assessment is appropriate if it is more efficient or cost-effective to do so.

Common controls (i.e., controls that are inherited by the system) are assessed separately (by assessors chosen by common control providers or the organization) and need not be assessed as part of a system- level assessment. 

Organizations ensure that assessors have access to the information system and environment of operation where the controls are implemented and to the documentation, records, artifacts, test results, and other materials needed to assess the controls. This includes the controls implemented by external providers through contracts, interagency agreements, lines of business arrangements, licensing agreements, or supply chain arrangements. Assessors have the required degree of independence as determined by the authorizing official.<sup>91</sup> Assessor independence during the continuous monitoring process facilitates reuse of assessment results to support ongoing authorization and reauthorization. 

To make the risk management process more efficient and cost-effective, organizations may choose to establish reasonable and appropriate criteria for reusing assessment results as part of organization-wide assessment policy or in the security and privacy program plans. For example, a recent audit of a system may have produced information about the effectiveness of selected controls. Another opportunity to reuse previous assessment results may come from external programs that test and evaluate security and privacy features of commercial information technology products (e.g., Common Criteria Evaluation and Validation Program and NIST Cryptographic Module Validation Program,). If prior assessment results from the system developer or vendor are available, the control assessor, under appropriate circumstances, may incorporate those results into the assessment. In addition, if a control implementation was assessed during other forms of assessment at previous stages of the SDLC (e.g., unit testing, functional testing, acceptance testing), organizations may consider potential reuse of those results to reduce duplication of efforts. And finally, assessment results can be reused to support reciprocity, for example, assessment results supporting an authorization to use (see Appendix F). Additional information on assessment result reuse is available in [SP 800-53A].  
 
**References:** [SP 800-53A]; [SP 800-160 v1] (Verification and Validation Processes); [IR 8011 v1].

***

<sup>89</sup> The senior agency official for privacy can delegate the assessment functions, consistent with applicable policies.
{: .fs-2}
<sup>90</sup> Only deficiencies in controls that can be exploited by threat agents are considered vulnerabilities.
{: .fs-2}
<sup>91</sup> In accordance with [OMB A-130], an independent evaluation of privacy program and practices is not required. However, an organization may choose to employ independent privacy assessments at the organization’s discretion.
{: .fs-2}

*** 
