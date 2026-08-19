---
title: "Why RDM matters for every researcher"
subtitle: "Research Data Mangement and Data Management Plan"
author: "Linda Zollitsch"
date: "2026-09-15"
format:
  revealjs:
    theme: dark
    smaller: true
    footer: "Linda Zollitsch | Zentrales Forschungsdatenmanagement | 2026-09-15."
    slide-number: c/t
    show-slide-number: all
    logo: media/cau-norm-de-lilagrey-rgb-0720.png
    title-slide-attributes:
      data-background-image: "media/cau-bcu2020.jpg"
      data-background-size: cover
      data-background-opacity: "0.5" # Macht das Bild transparenter, damit Text lesbar bleibt
---

# Agenda

* Why is Research Data Management important?

* Research Data Management

* Data Management Plan

* Benefits of Research Data Management




# Goals


<div style="float:right; width:30%;">
 <img src="./media/2022-09-27_Zielscheibe.png" alt="targets">
  <small><span style="text-align: right;"></span></small>
</div>

At the end of the workshop you…

- have a basic idea of the general concept of RDM and know some important related terms.
- can describe what research data and research data management is.
- can describe basics about the data management plan.



# Why is Research Data Management important?

-----

Let us first watch a short video

<iframe width="560" height="315" src="https://www.youtube.com/embed/66oNv_DJuPc
" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

{{1}}
****************


- What do you think about the video?

- Has someone experienced similar things already?

- Which parts of the video do you think refer to research data management?

****************

# Research Data Management

## Research Data

****************

+------------------------+--------------------------+------------------------------+
| Text and               |  Audio and               |  Geographic information      |
| spreadsheet documents  |  Video recordings        |  system (GIS) data           |
+------------------------+--------------------------+------------------------------+
| Transcripts            |  Pictures and figures    |  Topography data             |
+------------------------+--------------------------+------------------------------+ 
| Laboratory and         | Model, script and        | Samples and artifacts        |
| field notebooks        | research software code   |                              |
+------------------------+--------------------------+------------------------------+
| Diaries                |  Sensor data             | Sequence data                |
+------------------------+--------------------------+------------------------------+ 
| Text corpora           | Questionnaires and       | Spectra                      |
| and annotations        | codebooks                |                              |
+------------------------+--------------------------+------------------------------+ 

{{1}}
****************

What is research data?

> _‘Any information you use in your research.‘_
>
>[University of Camebridge PrePARe Project](https://www.repository.cam.ac.uk/handle/1810/243750)

****************

{{2}}
****************

> _‘The term “research data” generally refers to all kinds of (digital) data that represent the result of scientific work or that serve as a basis for such work. Research data is generated using a wide variety of methods, such as measurements, source research or surveys. Therefore, it is always subject- and project-specific.’_
>
>[Uni Giessen](https://www.uni-giessen.de/ub/en/resteach/researchdata#anchor_what-is-research-data)

****************

## Research Data Management

> ‘Research data management is an explicit process covering the creation and stewardship of research materials to enable their use for as long as they retain value.’
>
>[DCC Glossary](https://www.dcc.ac.uk/about/digital-curation/glossary#R)

{{1}}
****************
> ‘Research Data Management (RDM) is the methodical handling of the information produced or re-used during the course of academic research.’
>
>[University of Edinburgh Research Data Service](https://www.ed.ac.uk/information-services/research-support/research-data-service/research-data-management)

******************

{{2}}
****************
Research Data Management concerns all aspects of the research process. From simple aspects like naming conventions for data and folder up to complex aspects like specific digital tools that are needed for the research process.

****************

## Research data lifecycle

<center>

![RD-Lifecycle](images\FDM_Zyklus_klein_ohneText.jpg "Illustration: Cleo Michelsen, based on UK Data Service") <!-- width="500px" -->

</center>

{{1}}
****************
**Planning**:

* How do you plan to create data?
* Will data be reused? How is the data available?
* Which data types, in terms of data formats (e.g. image data, text data or measurement data in tables) are created?
* What volume of data can be expected?
* What legal and ethical aspects need to be taken into account?
* Who is responsible (for what)?
* Which analyses are planned? What requirements must the data meet in order to be analysed as planned? What kind of software environment will you need?

************

{{2}}
****************
**Collection and analysis**:

* Which (digital) methods and tools (e.g. software) are required collect and safe the (raw) data?
* What measures are taken to ensure high quality of the data?
* What approaches are taken to document all your work in a comprehensible manner?
* Which digital methods and tools (e.g. software) are required to read, use and analyse the data?
* How and where will the data be stored during the project?
* What is your back up strategy?
* How will the security of sensitive data be guaranteed during the project (access and usage management)?

************

{{3}}
****************
**Archiving & publication**:

* What legal conditions need to be considered in regard of publishing your research data?
* What ethical conditions need to be considered in regard of publishing your research data?
* Are there any effects or restrictions to be expected with regard to publication or accessibility of the data?
* How are usage and copyright aspects as well as ownership issues taken into account?
* Are there any important scientific codes or professional standards that should be taken into account?

************

{{4}}
****************
**Re-use**:

* Which data is particularly suitable for re-use?
* What criteria are used to select research data in order to make it available for re-use by others?
* Do you plan to archive your data in a suitable infrastructure?
* Are there embargo periods?
* When can the research data expected to be used by third parties?

****************

## FAIR Data Principles

{{0}}
****************

> An important goal of research data management is to keep data <span style="color:#F363F8">FAIR</span> in the <span style="color:#F363F8">long term</span> and <span style="color:#F363F8">independent of individuals</span>.

****************

{{1}}
****************

<span style="color:#F363F8">FAIR Data Principles</span>


🔍 <span style="color:#F363F8">F</span>indable (use persistent identifier (PIDs) like DOI, ORCiD, ROR...)

🔐 <span style="color:#F363F8">A</span>ccessible (make Metadata available, describe how to get access)

🔗 <span style="color:#F363F8">I</span>nteroperable (use Standards and open formats like csv, svg, jpg)

♻️ <span style="color:#F363F8">R</span>eusable (use licences, have a data documentation)

****************

## RDM checklist

1. Consider applicable policies

2. Account for ethical regulations and legislation

3. Have a sound data storage and security concept

4. Keep your working directories clean

5. Have a sound data collection strategy

6. Work on comprehensive documentation

7. Develop a data management plan

8. Make use of standard and open file formats

9. Share your research data

10. Continuous self-monitoring

<small>Hassenstein, M. J., & Jung, K. (2025). Ten simple rules for effective research data management. PLoS computational biology, 21(12), e1013779. https://doi.org/10.1371/journal.pcbi.1013779</small>



# Data Management Plan

"The Data Management Plan is a living summary document that provides assistance with organising and planning all the phases in the lifecycle of data. It explains, for each dataset, how project data will be managed, from creation or collection to sharing and archiving."

<small>https://www.universite-paris-saclay.fr/en/recherche/science-ouverte/introduction-data-management-plans</small>

{{1}}
****************

"A Data Management Plan (DMP or DMSP) details how data will be collected, processed, analyzed, described, preserved, and shared during the course of a research project."

<small>https://www.nnlm.gov/resources/data/data-glossary/data-management-plan</small>

****************

## Components of a DMP

- Administrative data
- Data Description
- Data documentation & quality control
- Storage & Backup
- Legal aspects
- Data publication
- Responsibilities & Ressources

Length can vary from a few paragraphs to several pages!


{{1}}
****************

<span style="color:#F363F8">Administrative data</span>

  - Basic data
    - Project title
    - data originator
    - other contributors
    - contact
    - funding organisation
    - grant number
  
  - Relevant guidelines and policies 

**********

{{2}}
****************
<span style="color:#F363F8">Data Description</span>

  - Type of research data

    - data types and formats that are reused or generated
    - tools or software to be used

  - volume
    - amount of data to be expected
    - size of the largest individual file

**********

{{3}}
****************

<span style="color:#F363F8">Data documentation & quality control</span>

  - folder and file naming conventions
  - versioning
  - metadata standards
  - controlled vocabularies / ontologies
  - supporting documentation
  - virtual research environments / databases / ELAB journals

*********

{{4}}
****************
<span style="color:#F363F8">Storage & Backup</span>

  - storage and data sharing during the project
  - backup strategy
  - access control according to protection requirements (e.g. GDPR)
  - long-term storage according to GRP

*********

{{5}}
****************

<span style="color:#F363F8">Legal aspects</span>

  - Data protection
  - Copyright and rights of use
  - Licensing law, patent law, etc.

*********

{{6}}
****************
<span style="color:#F363F8">Data publication</span>

  - selection of datasets
  - name of the (domain-specific) repository
  - timeline of data transfer to the archive
  - time of publication (embargo, if applicable)
  - reason for restrictions
  - selection of usage licenses

*********

{{7}}
****************

<span style="color:#F363F8">Responsibilities & Ressources</span>

  - Who is responsible for RDM?

    - regulation of responsibilities
    - access control
    - training of project participants
    - data curation

  - What does RDM cost?
    - Budget at least 5% for RDM costs!

****************

## Templates & Tools

<span style="color:#F363F8">Templates</span>

* [DFG Checklist (for section 2.4 of the proposal)](https://www.dfg.de/download/pdf/foerderung/grundlagen_dfg_foerderung/forschungsdaten/forschungsdaten_checkliste_en.pdf)

* [EU Horizon Europe-Template](https://fdm.uni-koeln.de/sites/FDM-UzK/Templates/data-management-plan-template_he_en-2.docx)

* [Science Europe Template](https://www.scienceeurope.org/our-priorities/research-data/research-data-management/)

{{1}}
****************

<span style="color:#F363F8">DMP Tools</span>

[Research Data Management Organizer (RDMO) - DFG-funded](https://rdmorganiser.github.io/)

[DMPonline - Digital Curation Centre (DDC), hosted by University of Edinburgh](https://dmponline.dcc.ac.uk/)

[DMP Tool - California Digital Library](https://dmptool.org/)

****************

## Common mistakes in DMP writing

* lack of accuracy

* reuse of (generic) text blocks

* terminological inaccuracies

* lack of resource calculation


## DMP checklist

1. Determine the Research Sponsor Requirements

2. Identify the Data to Be Collected

3. Define How the Data Will Be Organized

4. Explain How the Data Will Be Documented

5. Describe How Data Quality Will Be Assured

6. Present a Sound Data Storage and Preservation Strategy

7. Define the Project’s Data Policies

8. Describe How the Data Will Be Disseminated

9. Assign Roles and Responsibilities

10. Prepare a Realistic Budget

<small>Michener WK (2015) Ten Simple Rules for Creating a Good Data Management Plan. PLoS Comput Biol 11(10): e1004525. 
https://doi.org/10.1371/journal.pcbi.1004525</small>


# Benefits of Research Data Management

- a structured process --> more time for the "real" research

- good data organisation

- easy access to your reseach process

- minimizing data loss

- makes it easier to publish data 
  --> reuse of your own data in a follow up project
  --> more visibility
  --> increasing reputation

- compliance with good scientific practice

- compliance with rules of funders

- compliance with GDPR


## RDM in a nutshell

- Systematic file and folder naming and hierarchy

- document changes

- think about metadata necessary to understand your data

- use Open Document Format (ODF)

- __Generic and open standard file formats__ last longer than proprietary file formats

- Desktop and laptop for work on current research data only

- [Creative Commons](https://creativecommons.org/): data with a necessary creation height; ideally CC0 or CC BY



## Questions

><span style="color:#F363F8">Nearly done!</span>
>![image](./media/FragezeichenTyp.png) <!--
style="width: 10%; max-width: 800px; float:right"
title="puzzle"
onclick="alert('Questions?');"
-->
>
>Time for questions!

## Acknowledgement

If not stated otherwise, all graphics and illustrations are from Cleo Michelsen

## Thank you! :-)

Please take care of your data! 🌼
---

