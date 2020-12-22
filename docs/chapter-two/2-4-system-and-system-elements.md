---
layout: default
title: 2.4 SYSTEM AND SYSTEM ELEMENTS 
parent: CHAPTER TWO, THE FUNDAMENTALS 
nav_order: 240
---
<style>
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}
</style>
## 2.4 SYSTEM AND SYSTEM ELEMENTS 

This publication uses the statutory definition of information system for RMF execution. It is important, however, to describe information systems in the context of the SDLC process and how security and privacy capabilities are implemented within the components of those systems. Therefore, organizations executing the RMF take a broad view of the life cycle of information system development to provide a contextual relationship and linkage to architectural and engineering concepts that allow security and privacy risks (including supply chain risks) to be addressed throughout the life cycle and at the appropriate level of detail to help ensure that such capabilities are achieved. [ISO 15288] provides an engineering view of an information system and the entities with which the system interacts in its environment of operation.<sup>33</sup>

Similar to how federal law defines information system as a discrete set of information resources organized for the collection, processing, maintenance, use, sharing, dissemination, or disposition of information. [ISO 15288] defines a system as a set of interacting elements that are organized to achieve one or more stated purposes. Just as the information resources that comprise an information system include information and other resources (e.g., personnel, equipment, funds, and information technology), system elements include technology or machine elements, human elements, and physical or environmental elements. Each of the system elements<sup>34</sup> within the system fulfills specified requirements and may be implemented via hardware, software, or firmware;<sup>35</sup> physical structures or devices; or people, processes, policies, and procedures. Individual system elements or a combination of system elements may satisfy stated system requirements. Interconnections between system elements allow those elements to interact as necessary to produce a capability as specified by the system requirements. Finally, every system operates within an environment that influences the system and its operation.

The authorization boundary defines the system<sup>36</sup> for RMF execution to facilitate risk management and accountability. The system may be supported by one or more enabling systems that provide support during the system life cycle. Enabling systems are not contained within the authorization boundary of the system and do not necessarily exist in the system’s environment of operation. An enabling system may provide common (i.e., inherited) controls for the system or may include any type of service or functionality used by the system such as identification and authentication services, network services, or monitoring functionality. Finally, there are other systems the system interacts with in the operational environment. The other systems are also outside of the authorization boundary and may be the beneficiaries of services provided by the system or may simply have some general interaction.<sup>37</sup>

***

<sup>33</sup> [SP 800-160 v1] addresses system security engineering as part of the SDLC.
{: .fs-2 }
<sup>34</sup> The terms system element and information resource are used interchangeably in this publication. Information resources as defined in 44 U.S.C. Sec. 3502 include information and related resources, such as personnel, equipment, funds, and information technology. By law, a system is composed of a discrete set of information resources.
{: .fs-2 }
<sup>35</sup> The term system component refers to a system element that is implemented via hardware, software, or firmware.
{: .fs-2 }
<sup>36</sup> Historically, NIST has used the terms authorization boundary and system boundary interchangeably. In the interest of clarity, accuracy, and use of standardized terminology, the term authorization boundary is now used exclusively to refer to the set of system elements comprising the system to be authorized for operation or authorized for use by an authorizing official (i.e., the scope of the authorization). Authorization boundary can also refer to the set of common controls to be authorized for inheritance purposes.
{: .fs-2 }
<sup>37</sup> Risk management and accountability for enabling systems and other systems are addressed within their respective authorization boundaries.
{: .fs-2 }
***

Figure 5 illustrates the conceptual view of the system and the relationships among the system, system elements, enabling systems, other systems, and the environment of operation.<sup>38</sup>

<img src="https://statics.bsafes.com/images/NIST-SP-800-37-R2-Fig-5.png" alt="FIGURE 5: CONCEPTUAL VIEW OF THE SYSTEM" class="center">

Certain parts of the environment of operation may be included in the authorization boundary (i.e., determined to be “in scope” for the authorization) while other parts may be excluded. For example, if the facility (i.e., environment of operation) that provides protection for the system elements is determined to be in scope for the authorization of the system, the physical and environmental protection controls (e.g., physical access controls at entry points, perimeter protection devices) are included in the authorization boundary and therefore, are included in the system security plan. If the facility provides physical and environmental protections as common controls to be inherited by the system, the environment of operation is out of scope for the system and is not included in the authorization boundary for the system.<sup>39</sup>

The system may also communicate or have other interactions with enabling systems and other systems that are part of the extended environment of operation but are outside of the scope of authorization for the system.<sup>40</sup> Organizations determine which parts of the environment of operation are within the authorization boundary. These determinations are typically specific to the system and are context-driven.

***
<sup>38</sup> The terms system, system element, enabling system, other systems, and the environment of operation are agnostic with respect to information technology (IT) and operations technology (OT).
{: .fs-2 }
<sup>39</sup> Common controls are referenced in the security and privacy plans for the system inheriting the controls.
{: .fs-2 }
<sup>40</sup> For connections and information exchange between the system and the enabling or other systems outside of the authorization boundary, organizations consider the risks introduced by such connections and information exchange.
{: .fs-2 }
***
