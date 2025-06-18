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

Clicking on the links on the working group page will get you to the public drafts of the M11 specifications and the latest workplan. The template and techncial specifications were published in mid-March 2025 and are now out for public review:

- [Template Specifcation](https://database.ich.org/sites/default/files/ICH_M11_Template_Updated%20Step%202_ForReferenceOnly_2025_0203.pdf)
- [Technical Specification](https://database.ich.org/sites/default/files/ICH_M11_Technical%20Specification_Updated%20Step%202_2025_0203.pdf)
- [Work Plan](https://database.ich.org/sites/default/files/ICH_M11_EWG_WorkPlan_2024_0812.pdf)

The links below take you to the regualtory authority pages relating to the new documents and the associated review.

- [ICH, Review / Comment Process](https://www.ich.org/page/public-consultations)
- [EU, EMA M11 Review](https://www.ema.europa.eu/en/ich-m11-guideline-clinical-study-protocol-template-technical-specifications-scientific-guideline)
- [Taiwan, FDA M11 Review](https://www.fda.gov.tw/TC/siteContent.aspx?sid=13288)
- [Japan, MHLW M11 Review](https://public-comment.e-gov.go.jp/pcm/detail?CLASSNAME=PCMMSTDETAIL&id=495240433&Mode=0)

The previous versions of the M11 documents (from 2022) can be found here:

- [Template Specification](https://database.ich.org/sites/default/files/ICH_M11_Template_Step2_2022_0904.pdf)
- [Technical Specification](https://database.ich.org/sites/default/files/ICH_M11_TechnicalSpecification_Step2_2022_1014.pdf)

# USDM

## General

USDM, the Unified Study Definitions Model, is a new [CDISC](www.cdisc.org) standard developed in conjunction with [TransCelerate](https://www.transceleratebiopharmainc.com/). 

The USDM is focused on protocol digitization. See [the CDISC DDF page](https://www.cdisc.org/ddf) where there are plenty of links to various USDM & DDF resources. Links off to the various CDISC and TransCelerate resources can be found here including:

- [CDISC DDF page](https://www.cdisc.org/ddf)
- [TransCelerate DDF Website](https://transcelerate.github.io/ddf-home/index.html)
- [TransCelerate DDF GitHub](https://github.com/transcelerate/ddf-sdr-platform)
- [TransCelerate DDF Solutions](https://www.transceleratebiopharmainc.com/initiatives/digital-data-flow/)

Also there is the CDISC DDF-RA GitHub (see more below)

- [DDF-RA USDM repo](https://github.com/cdisc-org/DDF-RA)

## Phases

There have been four phases of development to date

- Phase 1: An initial model
- Phase 2: Added in detail around the SoA
- Phase 3: Initial alignment with M11 and move to handing the whole protocol as a document within the model
- Phase 4: More complex use cases and further alignment to M11. Release in June 2025.

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
- USDM and M11 Protocol. This infographic shows where content from an M11 protocol document goes into USDM. Based on the latest public review version of the template. Now updated for USDM v4. [USDM M11 Template Infographic](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/usdm_m11.pdf)
- USDM and M11 Classes. This infographic shows which USDM classes are used to support the M11 protocol template. Based on the latest public review version of the template and USDM v4. [USDM M11 Classes Infographic](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/usdm_m11_classes.pdf)


## Posters

- ICH M11, USDM etc. A poster from the PHUSE CSS meeting held in Utrecht in May 2025 looking at the big picture. [USDM M11 Poster](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/phuse_2025_css_poster.pdf)

## Presentations on Behalf of CDISC

A series of presentations going back over the last few years from a number of different conferneces. These presentations were presented on behalf of CDISC. Link is to the [whole directory](https://github.com/data4knowledge/usdm_m11_resources/tree/main/documents/presentations/cdisc). File names contain the date, the conference and presenter.

## d4k Presentations

Presentations made by d4k can be found in this [directory](https://github.com/data4knowledge/usdm_m11_resources/tree/main/documents/presentations/d4k)

## 2024 "DDF in Action" Day

The DDF in Action day was held in October 2024 in Copenhagen and New Jersey. It was day for sponsors, vendors and others to share eperiences and information about DDF and to see, well, DDF in action! Couple of items from the day:

- The use cases infrographic, [Use Case Infographic](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/use%20cases.png) and associated [LinkedIn post](https://www.linkedin.com/feed/update/urn:li:activity:7255527712906199042/) (repeated from above).
- [Official TransCelerate](https://github.com/data4knowledge/usdm_m11_resources/tree/main/documents/ddf-in-action/DDF%20in%20Action%20Day%20Readout.pdf) readout from the day.
- [CPH slide deck](https://github.com/data4knowledge/usdm_m11_resources/tree/main/documents/ddf-in-action/DDF%20in%20Action%20Day%20Presentation_CPH.pdf) 
- [NJ slide deck](https://github.com/data4knowledge/usdm_m11_resources/tree/main/documents/ddf-in-action/DDF%20in%20Action%20Day%20Presentation_NJ.pdf)

The official TransCelerate [Report Page](https://transcelerate.github.io/ddf-home/ddf-in-action.html)

## PRISM

Information about the PRISM pilot.

- Presentation by Ginny Hussong at the [PHUSE CSS](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/presentations/fda/2024%2006%20CSS%20PRISM.pdf) meeting in June 2024
- Good [background and overview](https://www.agencyiq.com/blog/another-cloud-in-the-sky-fda-and-industry-team-up-to-test-prism-a-new-regulatory-cloud-submissions-platform/) in this article
- A single slide used to provide an overview of the [PRISM technology](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/presentations/cdisc/2025%2001%2016%20PRISM%20-%20DIH.pdf)
 
