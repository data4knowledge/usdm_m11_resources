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

As an aside, the full M11 title is "CLINICAL ELECTRONIC STRUCTURED HARMONISED PROTOCOL (CeSHarP)" ... M11 to you and me.

## M11 Working Group

Information on M11 is a little difficult to find on the [ICH web site](https://www.ich.org/), you really have to look quite hard. Details on the working groups can be found on the [Working Groups](https://www.ich.org/page/multidisciplinary-guidelines) page. Click on the M11 section, you might need to scroll down.  The concept paper, business plan and work plan can be found here.

## Addopted M11 Versions

These are the final, adopted, versions of the M11 documents.

- [M11 Guideline](https://database.ich.org/sites/default/files/ICH_Step4_M11_Final_Guideline_2025_1119.pdf)
- [Template Specifcation](https://database.ich.org/sites/default/files/ICH_Step4_M11_Final_Template_2025_1119.pdf)
- [Technical Specification](https://database.ich.org/sites/default/files/ICH_Step4_M11_Final_TechnicalSpecification_2025_1119.pdf)

## Previous M11 Version

These are the links to the previous versions of the M11 specifications. The template and techncial specifications were published in mid-March 2025:

- [Template Specifcation](https://database.ich.org/sites/default/files/ICH_M11_Template_Updated%20Step%202_ForReferenceOnly_2025_0203.pdf)
- [Technical Specification](https://database.ich.org/sites/default/files/ICH_M11_Technical%20Specification_Updated%20Step%202_2025_0203.pdf)

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

## Protocol2USDM

- Access the [Github library](https://github.com/Panikos/Protocol2USDMv3) and look at the readme

# Background Information

## General

The following are diagrams, slides decks etc that I tend to reach for as I am talking about USDM and M11

## Infographics

Couple of infographics that I have produced during the development of the USDM

- Use Cases. This was prepared for the DDF in Action day held in October 2024 in Copenhagen and New Jersey. I created this to show the range of touch points for eProtocol. [Use Case Infographic](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/use%20cases.png). I did a LinkedIn post of this, [see here](https://www.linkedin.com/feed/update/urn:li:activity:7255527712906199042/)
- USDM and a Typical Protocol. This is an attempt to show where the items within an exisitng protocol go in USDM. A little old now but still relevant. [Protocol Infographic](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/protocol.png)
- USDM and M11 Protocol. This infographic shows where content from an M11 protocol document goes into USDM. Based on the latest public review version of the template. Now updated for USDM v4. [USDM M11 Template Infographic](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/usdm_m11.pdf)
- USDM and M11 Classes. This infographic shows which USDM classes are used to support the M11 protocol template. Based on the latest public review version of the template and USDM v4. [USDM M11 Classes Infographic](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/usdm_m11_classes.pdf)
- USDM and CT. This infographic shows all the code lists used across the USDM as a quick reference guide. Useful for implementators. As usual, zoom in to see the detail. [USDM Controlled Terminology](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/usdm_ct_infographic.pdf)


## Posters

- ICH M11, USDM etc. A poster from the PHUSE CSS meeting held in Utrecht in May 2025 looking at the big picture. [USDM M11 Poster](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/phuse_2025_css_poster.pdf)
- USDM & SDTM. A poster from the TransCelerate Mission Possible 2025 event held in New Jersey and Basel, September 2025. [Protocol to SDTM in 15 mins. Is it Possible?](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/infographics/mission_possible_2025_poster.pdf)

## Newsletter

I publish a [LinkedIn newsletter](https://www.linkedin.com/newsletters/view-from-the-coffee-shop-7302649032726736896/) on USDM, M11 and related topics. 

List of editions:









| # | Title | Date | Topic |
|:---|:-------|:------|:---------------|
| 1 | [Ripples](https://www.linkedin.com/pulse/ripples-dave-iberson-hurst-partner-at-d4k-gd7cf/) | 4 Mar 2025 | USDM will become the single source of truth; change will reach every corner like ripples on a pond |
| 2 | [The Document Model Dichotomy](https://www.linkedin.com/pulse/document-model-dichotomy-dave-iberson-hurst-partner-at-d4k-osyxf/) | 11 Mar 2025 | How USDM reconciles the tension between protocol documents and structured data models — the detailed technical explanation |
| 3 | [New ICH M11 Specifications](https://www.linkedin.com/pulse/new-ich-m11-specifications-dave-iberson-hurst-partner-at-d4k-9ounf/) | 17 Mar 2025 | Announcement: M11 Technical Specification released for public review |
| 4 | [Corners and Edges](https://www.linkedin.com/pulse/corners-edges-dave-iberson-hurst-partner-at-d4k-ufrwf/) | 24 Mar 2025 | USDM provides the missing jigsaw pieces — the foundation that frames everything else |
| 5 | [Mapping ICH M11 to USDM: A Visual Guide](https://www.linkedin.com/pulse/mapping-ich-m11-usdm-visual-guide-dave-iberson-hurst-partner-at-d4k-tutkf/) | 2 Apr 2025 | Infographic revealing the SOA as a massive structured area hidden behind a single line in M11 |
| 6 | [Why](https://www.linkedin.com/pulse/why-dave-iberson-hurst-partner-at-d4k-jalcf/) | 16 Apr 2025 | The comprehensive use-case and business-case article: ROI, quality, capacity, regulatory timeline, and what USDM enables beyond today's processes |
| 7 | [Hello World](https://www.linkedin.com/pulse/hello-world-dave-iberson-hurst-partner-at-d4k-vjnjf/) | 7 May 2025 | Most users don't need to see USDM's internals — just as Word users never see XML. A detailed walkthrough of what gets digitised and why |
| 8 | [A Poster in Utrecht](https://www.linkedin.com/pulse/poster-utrecht-dave-iberson-hurst-partner-at-d4k-qw3tf/) | 20 May 2025 | PHUSE CSS poster connecting M11, USDM, and implementation; the value of face-to-face events |
| 9 | [Thoughts From Geneva](https://www.linkedin.com/pulse/thoughts-from-geneva-dave-iberson-hurst-partner-at-d4k-yfuaf/) | 21 May 2025 | Two moments at CDISC Interchange that crystallise the goal: linking study design to data so we can defeat diseases, not just speak to regulators |
| 10 | [Diamonds in the Legs](https://www.linkedin.com/pulse/diamonds-legs-dave-iberson-hurst-partner-at-d4k-qiwnf/) | 4 Jun 2025 | USDM v4 released — four years of work reaches its summit. Phase 5 shifts to adoption |
| 11 | [Hamburg and Magic Sauce](https://www.linkedin.com/pulse/hamburg-magic-sauce-dave-iberson-hurst-partner-at-d4k-toksf/) | 18 Jun 2025 | The technology demonstrator that captured industry attention; common USDM questions; preview of PHUSE Hamburg |
| 12 | [USDM Controlled Terminology](https://www.linkedin.com/pulse/usdm-controlled-terminology-dave-iberson-hurst-partner-at-d4k-wyyof/
) | 25 Jun 2025 | Infographic mapping coded attributes to their controlled terminology code lists — a practical implementation aid |
| 13 | [Solid Foundations](https://www.linkedin.com/pulse/solid-foundations-dave-iberson-hurst-partner-at-d4k-rkktf/) | 14 Jul 2025 | If one reason to adopt USDM: "solid foundation." Also addresses CRO benefits — they didn't write the protocol, so digital clarity matters even more |
| 14 | [Train Leaving The Station](https://www.linkedin.com/pulse/train-leaving-station-dave-iberson-hurst-partner-at-d4k-lsvyf/) | 18 Sep 2025 | Industry had a decade for SDTM (2004–2016); there won't be a decade for M11/USDM. The train is leaving |
| 15 | [Road to ...](https://www.linkedin.com/pulse/road-dave-iberson-hurst-partner-at-d4k-e333f/) | 26 Sep 2025 | Reflections from TransCelerate Mission Possible: "yes, we got this right." USDM has crossed (or is crossing) the adoption chasm |
| 16 | [Connecting the Dots](https://www.linkedin.com/pulse/connecting-dots-dave-iberson-hurst-partner-at-d4k-kez8f/) | 23 Oct 2025 | The big-picture vision: USDM as foundation for a connected data layer removing silos across safety, analysis, and operations |
| 17 | [What is a SoA?](https://www.linkedin.com/pulse/what-soa-dave-iberson-hurst-partner-at-d4k-gzkaf/) | 6 Nov 2025 | A deep interrogation of what "SoA" actually means — introducing study logic, the timeline model, the Google Maps analogy, and the distinction between study science, study logic, and study narrative |
| 18 | [Two Questions and an Onion](https://www.linkedin.com/pulse/two-questions-onion-dave-iberson-hurst-partner-at-d4k-9y4gf/) | 2 Dec 2025 | Data first, documents second. The onion model: build from the study science core outward. AI works best on structured foundations |
| 19 | [Year-End Reflections](https://www.linkedin.com/pulse/view-from-coffee-shop-year-end-reflections-dave-p5tie/) | 19 Dec 2025 | Myth-busting: premature compliance claims, USDM doesn't add requirements, the iPhone analogy, and a defence of idealism |
| 20 | [ICH M11 and USDM: Mind the Gap](https://www.linkedin.com/pulse/ich-m11-usdm-mind-gap-dave-iberson-hurst-partner-at-d4k-yutwe/) | Feb 2026 | M11 through a writer's eyes; practical friction between document labels and data model needs; CT alignment challenges |


## Articles

- [BioMedical Concepts – The Key to Unlocking Meaningful Clinical Data](https://www.clinflo.com/biomedical-concepts-the-key-to-unlocking-meaningful-clinical-data/) by Doug Bain.
- [Unlocking Clinical Trial Efficiency with the Unified Study Definition Model (USDM)](https://www.linkedin.com/pulse/unlocking-clinical-trial-efficiency-unified-study-basia-7huoe/?trackingId=h2LFLnjTRoK10O%2BR6bLI9g%3D%3D) by Basia Coulter, Ph.D., M.Sc.
- Transcelerate DDF Use Cases, LinkedIn post [with link in the post](https://www.linkedin.com/posts/digital-data-flow_ddf-usdm-digitaldataflow-activity-7426659554626576384-CNVL?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAA51QwBghCAJ2HEhiuN2EFzhRi5_QyYfc8)
- [Clinical Leader](https://www.clinicalleader.com/doc/digital-protocols-are-at-an-inflection-point-a-conversation-with-novartis-and-transcelerate-leaders-0001)

## LinkedIn 

Useful LinkedIn accounts

- [Transcelerate DDF](https://www.linkedin.com/company/digital-data-flow/posts/?feedView=all)

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

## 2025 "Mission Possible" Day

The TransCelerate DDF September 2025 in Basel (Roche) and New Jersey (Novartis). It was the second event for sponsors, vendors and others to share eperiences and information about DDF.

The official outputs from the event:

- [Event Summary Report](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/mission-possible/DDF_Mission_Possible_Summary_Report.pdf)
- [Presentations](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/mission-possible/DDF_Mission_Possible_Master_Presentation.pdf)

## White Papers

- TransCelerate white paper [Practical Approach to Implementing Digital Data Flow: A Framework to Getting Started](https://transcelerate.github.io/ddf-home/documents/white_paper/DDF_Practical_Approach_to_Implementation.pdf)

## PRISM

Information about the PRISM pilot.

- Presentation by Ginny Hussong at the [PHUSE CSS](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/presentations/fda/2024%2006%20CSS%20PRISM.pdf) meeting in June 2024
- Good [background and overview](https://www.agencyiq.com/blog/another-cloud-in-the-sky-fda-and-industry-team-up-to-test-prism-a-new-regulatory-cloud-submissions-platform/) in this article
- A single slide used to provide an overview of the [PRISM technology](https://github.com/data4knowledge/usdm_m11_resources/blob/main/documents/presentations/cdisc/2025%2001%2016%20PRISM%20-%20DIH.pdf)
 
