---
layout: default
title: 2.2 RISK MANAGEMENT FRAMEWORK STEPS AND STRUCTURE 
parent: CHAPTER TWO, THE FUNDAMENTALS 
nav_order: 220
---
<style>
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}
</style>
## 2.2 RISK MANAGEMENT FRAMEWORK STEPS AND STRUCTURE 

There are seven steps in the RMF; a preparatory step to ensure that organizations are ready to execute the process and six main steps. All seven steps are essential for the successful execution of the RMF. The steps are:

* Prepare to execute the RMF from an organization- and a system-level perspective by establishing a context and priorities for managing security and privacy risk.
* Categorize the system and the information processed, stored, and transmitted by the system based on an analysis of the impact of loss.<sup>26</sup>
* Select an initial set of controls for the system and tailor the controls as needed to reduce risk to an acceptable level based on an assessment of risk.
* Implement the controls and describe how the controls are employed within the system and its environment of operation.
* Assess the controls to determine if the controls are implemented correctly, operating as intended, and producing the desired outcomes with respect to satisfying the security and privacy requirements.
* Authorize the system or common controls based on a determination that the risk to organizational operations and assets, individuals, other organizations, and the Nation is acceptable.
* Monitor the system and the associated controls on an ongoing basis to include assessing control effectiveness, documenting changes to the system and environment of operation, conducting risk assessments and impact analyses, and reporting the security and privacy posture of the system.

Figure 2 illustrates the steps in the RMF. The RMF operates at all levels in the risk management hierarchy illustrated in Figure 1. Chapter Three provides a detailed description of each of the tasks necessary to carry out the steps in the RMF.

<img src="https://statics.bsafes.com/images/NIST-SP-800-37-R2-Fig-2.png" alt="FIGURE 2: RISK MANAGEMENT FRAMEWORK" class="center">

While the RMF steps are listed in sequential order above and in Chapter Three, the steps following the Prepare step can be carried out in a nonsequential order. After completing the tasks in the Prepare step, organizations executing the RMF for the first time for a system or set of common controls typically carry out the remaining steps in sequential order. However, there could be many points in the risk management process where there is a need to diverge from the sequential order due to the type of system, risk decisions made by senior leadership, or to allow for iterative cycles between tasks or revisiting of tasks (e.g., during agile development). Once the organization is in the Monitor step, events may dictate a nonsequential execution of steps. For example, changes in risk or in system functionality may necessitate revisiting one or more of the steps in the RMF to address the change.

<div style="background-color:lightblue; padding:20px" markdown="1">
<h3 style="text-align:center">FLEXIBILITY IN RMF IMPLEMENTATION</h3>
Organizations are expected to execute all steps and tasks in the RMF (apart from tasks labeled as optional). However, organizations have significant flexibility in how each of the RMF steps and tasks are carried out, as long as organizations are meeting all applicable requirements and effectively managing security and privacy risk. The intent is to allow organizations to implement the RMF in the most efficient, effective, and cost-effective manner to support mission and business needs in a way that promotes effective security and privacy. Flexible implementation may include executing tasks in a different (potentially nonsequential) order, emphasizing certain tasks over other tasks, or combining certain tasks where appropriate. It can also include the use of the Cybersecurity Framework to enhance RMF task execution.

Flexibility of implementation can also be applied to control selection, control tailoring to meet organizational security and privacy needs, or conducting control assessments throughout the SDLC. For example, the selection, tailoring, implementation, and assessments of controls can be done incrementally as a system is being developed. The implementation of control tailoring helps to ensure that security and privacy solutions are customized for the specific missions, business functions, risks, and operating environments of the organization. In the end, the flexibility inherent in RMF execution promotes effective security and privacy that helps to protect the systems that organizations depend on for mission and business success and the individuals whose information is processed by those systems.

**Note:** Since the RMF is an SDLC process that emphasizes ongoing authorization, organizations have the flexibility to determine which RMF step to enter (or reenter) based on an assessment of risk and the tasks described in the Prepare—System Level step. Determination of the appropriate RMF step requires an assessment of the current state of the system, a review of the activities that have already been completed for the system, identification of a proposed step and task entry into the RMF, a gap analysis to ensure that the risk is acceptable, documenting decisions, notifying stakeholders, and approval from the Authorizing Official (or other relevant decision maker).
{: .fs-2 }
</div>

Although the risk management approach in Figure 1 is conveyed as hierarchical, project and organization dynamics are typically more complex. The risk management approach selected by an organization may vary on a continuum from top-down command to decentralized consensus among peers. However, in all cases, organizations use a consistent approach that is applied to risk management processes organization-wide from the organization level to the information system level. Organizational officials identify and secure the needed resources to complete the risk management tasks described in this publication and ensure that those resources are made available to the appropriate personnel. Resource allocation includes funding to conduct risk management tasks and assigning qualified personnel that are needed to accomplish the tasks.

Each step in the RMF has a purpose statement, a defined set of outcomes, and a set of tasks that are carried out to achieve those outcomes. The outcomes can be achieved by different risk management levels—that is, some of the outcomes are universal to the entire organization, while others are system-focused or mission/business unit-focused. Figure 3 provides an example of the purpose statement and outcomes for the RMF Prepare step—Organization-Level.

<img src="https://statics.bsafes.com/images/NIST-SP-800-37-R2-Fig-3.png" alt="FIGURE 3: RISK MANAGEMENT FRAMEWORK TASK STRUCTURE" class="center">

Each task contains a set of potential inputs needed to execute the task and a set of expected outputs generated from task execution.<sup>27</sup> In addition, each task describes the risk management roles and responsibilities associated with the task and the phase of the SDLC where task execution occurs.<sup>28</sup> A discussion section provides information related to the task to facilitate understanding and to promote effective task execution. Finally, completing the RMF task description, there is a list of references to provide organizations with supplemental information for each task. Where applicable, the references also identify systems security engineering tasks that correlate with the RMF task.<sup>29</sup> Figure 4 illustrates the structure of a typical RMF task.

<img src="https://statics.bsafes.com/images/NIST-SP-800-37-R2-Fig-4.png" alt="FIGURE 4: RISK MANAGEMENT FRAMEWORK TASK STRUCTURE" class="center">

***
<sup>26</sup> Impact of loss is one of four risk factors considered during risk assessment activities—the other three factors being threats, vulnerabilities, and likelihood of occurrence [SP 800-30]. Organizations leverage risk assessment results when categorizing information and systems. For national security systems, it may be important to consider specific issues affecting risk factors as part of categorization, such as, whether the system processes, stores, or transmits classified or intelligence information; whether the system will be accessed directly or indirectly by non-U.S. personnel; and whether the information processed, stored, or transmitted by the system will cross security domains. [CNSSI 1253] provides additional information on categorizing national security systems.
{: .fs-2 }
<sup>27</sup> The potential inputs for a task may not always be derived from the expected outputs from the previous task. This can occur because the RMF steps are not always executed in sequential order, breaking the sequential dependencies.
{: .fs-2 }
<sup>28</sup> Appendix D provides a description of each of the roles and responsibilities identified in the tasks.
{: .fs-2 }
<sup>29</sup> [SP 800-160 v1] describes life cycle-based systems security engineering processes.
{: .fs-2 }
***
