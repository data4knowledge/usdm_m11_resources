# USDM and ICH M11 Resources

## General

This is an informative repo just holding a series of resource related to the Unified Studies Definition Model and the ICH M11 Protocol Template Specification.

# ICH M11

## General

The ICH M11 [Concept Paper](https://database.ich.org/sites/default/files/M11_EWG_Concept_Paper.pdf) states

> This Concept Paper supports a proposal for a new harmonised guideline that specifies comprehensive clinical protocol organization with standardized content with both required and optional components. The working group will deliver the following:

> - Guideline outlining two main sets of harmonised approaches 
>   - a template to include identification of headers, common text and a set of data fields and terminologies which will be the basis for efficiencies in data exchange
>   - a technical specification that uses an open, nonproprietary standard to enable electronic exchange of clinical protocol information

As an aside, the full M11 title is "CLINICAL ELECTRONIC STRUCTURED HARMONISED PROTOCOL (CeSHarP)" ... eProtocol to you and me.

## M11 Working Group

Information on M11 is a little difficult to find on the [ICH web site](https://www.ich.org/), you really have to look quite hard. Details on the working groups can be found on the [Working Groups](https://www.ich.org/page/multidisciplinary-guidelines) page. Click on the M11 section, you might need to scroll down. 

## M11 Documents

Clicking on the links on the working group page will get you to the latest public drafts of the M11 specifications and the latest workplan

- [Template Specification](https://database.ich.org/sites/default/files/ICH_M11_Template_Step2_2022_0904.pdf)
- [Technical Specification](https://database.ich.org/sites/default/files/ICH_M11_TechnicalSpecification_Step2_2022_1014.pdf) 
- [Work Plan](https://database.ich.org/sites/default/files/ICH_M11_EWG_WorkPlan_2024_0812.pdf)

The template and techncial specifications published here are the latest "public" versions. They are quite old (from late 2022, the last public review) and there are more recent internal drafts. Hopefully these will be generally available but I suspect this will not be until around Q3 / Q4 2025, see the work plan. 

The work plan is predicting the FHIR message support for Q2 2026.

# USDM

## General

USDM, the Unified Study Definitions Model, is a new [CDISC](www.cdisc.org) standard developed in conjunction with [TransCelerate](https://www.transceleratebiopharmainc.com/). 

The USDM is focused on protocol digitization. See [the CDISC DDF page](https://www.cdisc.org/ddf) where there are plenty of links to various USDM & DDF resources.

## Phases

There have been four phases of development to date

- Phase 1: An initial model
- Phase 2: Added in detail around the SoA
- Phase 3: Initial alignment with M11 and move to handing the whole protocol as a document within the model
- Phase 4: Current phase that will result in the v4 release in April 2025. More complex use cases and further alignment to M11

To look at the various release use the tags within the CDISC DDF-RA (Digital Data Flow - Reference Architecture) GitHub, see below.

## CDISC DDF-RA USDM GitHub

### Deliverables

Just a remiinder:

- DDF: Digital Data Flow
- RA: Reference Architecture

The main repo for USDM is the CDISC [DDF-RA USDM repo](https://github.com/cdisc-org/DDF-RA)

Note the "Deliverables" directory within the repo where you will find ... the deliverables:

- UML, the USDM logical model
- CT, the supporting CT, full definitions for the entities, attributes, relationships and associated CT for coded attributes
- API, definition of the JSON used to transport a single USDM study
- CORE, validation rules using the CDISC CORE engine
- IG, The Implementation Guide

### Supporting Info

In the "Documents" directory you will find supporting information and examples. Couple of things worth noting

- [Informational diagram](https://github.com/cdisc-org/DDF-RA/blob/main/Documents/DDF%20USDM%20Model%20Informative.png). This is a different representation of the UML, with API infomration added, see the key top right.
- The [changes directory](https://github.com/cdisc-org/DDF-RA/tree/main/Documents/Changes) holds the changes made during phase 3.

# Tools

## Study Definition Workbench

- Access to the tool is via [this link](https://d4k-sdw.fly.dev).
- LinkedIn [article here](https://www.linkedin.com/feed/update/urn:li:activity:7284824136701399040/).
# Background Information

## General

The following are diagrams, slides decks etc that I tend to reach for as I am talking about USDM and M11

## Infographics

Couple of infographics that I have produced during the development of the USDM

- Use Cases. This was prepared for the DDF in Action day held in October 2024 in Copenhagen and New Jersey. I created this to show the range of touch points for eProtocol. [Use Case Infographic](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/use%20cases.png). I did a LinkedIn post of this, [see here](https://www.linkedin.com/feed/update/urn:li:activity:7255527712906199042/)
- USDM and a Typical Protocol. This is an attempt to show where the items within an exisitng protocol go in USDM. A little old now but still relevant. [Protocol Infographic](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/protocol.png)

## Presentations on Behalf of CDISC

A series of presentations going back over the last few years from a number of different conferneces. These presentations were presented on behalf of CDISC. Link is to the [whole directory](https://github.com/data4knowledge/usdm_m11_resources/tree/main/documents/presentations/cdisc). File names contain the date, the conference and presenter.

## PRISM

Information about the PRISM pilot.

- Presentation by Ginny Hussong at the [PHUSE CSS](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/presentations/fda/2024%2006%20CSS%20PRISM.pdf) meeting in June 2024
- Good [background and overview](https://www.agencyiq.com/blog/another-cloud-in-the-sky-fda-and-industry-team-up-to-test-prism-a-new-regulatory-cloud-submissions-platform/) in this article
- A single slide used to provide an overview of the [PRISM technology](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/presentations/cdisc/2025%2001%2016%20PRISM%20-%20DIH.pdf)
 