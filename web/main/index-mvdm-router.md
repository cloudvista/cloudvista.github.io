---
layout: default
title: Home
---

The Veterans Information Systems Technology Architecture ([VISTA](https://en.wikipedia.org/wiki/VistA)) is the comprehensive  longitudinal  clinical, business, and administrative information system of the U.S. Veterans Health Administration ([VHA](https://www.va.gov/health/aboutVHA.asp)). 130 instances support the operations of over 1200 VA hospitals and clinics nationwide.  

VISTA's data model - the roadmap to all of VA's institutional, business, and clinical processes and data - has evolved organically over the past 35 years but has not been surfaced and leveraged in computable form. Until now. 

In the VISTA Data Project (VDP), this organic data model is comprehensively exposed and incrementally normalized across all VISTA systems to produce a national, standardized Master VISTA Data Model (MVDM) spanning all VISTA systems. An operationalized MVDM provides new clients with a single, secure, symmetric read-write interface to every VISTA and, through _emulation_ of existing interfaces, VISTA's current clients such as CPRS and JLV work unchanged, but with greatly enhanced security. 

Through this same MVDM-driven mechanism, the functionality across all VISTA systems can be centralized to a single secure, cloud-based, veteran-specific Veteran Integrated Care Service (VICS),  allowing  the corresponding functionality of the 130 decentralized VISTA systems to be decomissioned while maintaining seamless continuity of veteran-specific care and services.

![vdp-transition -width70](/assets/vdp-vista-vics-v3.png)

<br>

__Strategic Benefits__:

  * New, maintainable, centralized, cloud-based veteran care services based on mainstream technology
  * New web and mobile clients enabled with mainstream technology
  * Current clients (CPRS/JLV) supported and secured, enforcing continuity of VA Care coverage
  * May now safely incrementally retire legacy MUMPS VISTA systems, with no loss of veteran-specific care or services
  * May now implement generic COTS clinical and business systems (EHR/ERP), while preserving veteran-specific care and services

<br>

__Show Me:__ browse through and run VDP's [Clinical](/demo) and [Non Clinical](/demo2) Demos.


