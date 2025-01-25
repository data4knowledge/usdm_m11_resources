# USDM and ICH M11 Resources

## General

This is an informative repo just holding a series of resource related to the Unified Studies Definition Model and the ICH M11 Protocol Template Specification.

# ICH M11

## General

The ICH M11 [Concept Paper](https://database.ich.org/sites/default/files/M11_EWG_Concept_Paper.pdf) states

> This Concept Paper supports a proposal for a new harmonised guideline that specifies comprehensive clinical protocol organization with standardized content with both required and optional components. The working group will deliver the following:
> - Guideline outlining two main sets of harmonised approaches 
    - a template to include identification of headers, common text and a set of data fields and terminologies which will be the basis for efficiencies in data exchange
    - a technical specification that uses an open, nonproprietary standard to enable electronic exchange of clinical protocol information

As an aside, the full M11 title is "CLINICAL ELECTRONIC STRUCTURED HARMONISED PROTOCOL (CeSHarP)" ... eProtocol

## M11 Working Group

Information on M11 is a little difficult to find on the [ICH web site](https://www.ich.org/), you really have to look quite hard. Details on the working groups can be found on the [Working Groups](https://www.ich.org/page/multidisciplinary-guidelines) page. Click on the M11 section, you might need to scroll down. 

## M11 Documents

Clicking on the links on the working group page will get you to the latest public draft of the M11 specifications and the latest workplan

- [Template Specification](https://database.ich.org/sites/default/files/ICH_M11_Template_Step2_2022_0904.pdf)
- [Technical Specification](https://database.ich.org/sites/default/files/ICH_M11_TechnicalSpecification_Step2_2022_1014.pdf) 
- [Work Plan](https://database.ich.org/sites/default/files/ICH_M11_EWG_WorkPlan_2024_0812.pdf)

The template and techncial specifications publish here are the latest "public" versions. They are quite old (from late 2022, the last public review) and there are more recent internal drafts. Hopefully these will be generally available but I suspect this will not be until around Q3 / Q4 2025, see the work plan. 

The work plan is predicting the FHIR message support for Q2 2026.

# USDM

## General

USDM, the Unified Study Definitions Model, is a new [CDISC](www.cdisc.org) standard developed in conjunction with [TransCelerate](). 

The USDM is focused on protocol digitization. See [the CDISC DDF page](https://www.cdisc.org/ddf) where there are plenty of links to various USDM & DDF resources.

## CDISC USDM GitHub

The main repo for USDM is the CDISC [USDM repo](https://github.com/cdisc-org/DDF-RA)

Note the "Deliverables" directory within the repo where you will find ... the deliverables:

- UML, the USDM logical model
- CT, the supporting CT, full definitions for the entities, attributes, relationships and associated CT for coded attributes
- API, definition of the JSON used to transport a single USDM study
- CORE, validation rules using the CDISC CORE engine
- IG, The Implementation Guide

In the "Documents" directory you will find supporting information and examples

## Background

